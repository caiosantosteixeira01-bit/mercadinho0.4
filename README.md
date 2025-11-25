📦 Mercadinho App – Sistema de Gerenciamento de Mercado

Um sistema completo para controle de produtos, usuários, autenticação, estoque e interface gráfica utilizando Python + PyQt5.
O objetivo do projeto é oferecer uma aplicação simples, organizada e funcional para uso em pequenos mercados ou mercearias.

🔧 Tecnologias e Ferramentas Utilizadas

Python 3

PyQt5 (Interface gráfica)

SQLite (Banco de dados local)

Qt Designer (Criação das telas)

Pillow (PIL) (Quando necessário para manipular imagens)

Git & GitHub (Controle de versão)

VSCode / PyCharm (Recomendado para edição)

BCrypt 

📁 Estrutura do Projeto
Mercadinho_App/
│  main.py
│  models.py
│  auth.py
│  seed.py
│
├── ui/
│    login_window.py
│    main_window.py
│    product_dialog.py
│    user_dialog.py
│
└── assets/
       logo.png
       
📝 Descrição do Sistema

O Mercadinho App é dividido em módulos para facilitar manutenção e organização:

✔ Autenticação (Login)

Tela de acesso com validação de usuário.

Exibição da logo na tela inicial.

Controle de permissões (Admin / Comum).

✔ Tela Principal

<img width="304" height="336" alt="Captura de tela 2025-11-25 140938" src="https://github.com/user-attachments/assets/4feee0ee-d6e0-43d8-afae-9b17c8c71073" />
<img width="234" height="144" alt="Captura de tela 2025-11-25 141008" src="https://github.com/user-attachments/assets/c346560d-3947-4fbd-a44a-8a593cd094cc" />

Menu lateral com navegação simples.

Listagem de produtos.

Listagem de usuários (para admins).

Acesso rápido às funções principais do sistema.

✔ Gestão de Produtos

<img width="796" height="632" alt="Captura de tela 2025-11-25 141024" src="https://github.com/user-attachments/assets/9d7adf4a-f99b-431d-b004-729af460cf65" />
<img width="174" height="196" alt="Captura de tela 2025-11-25 141120" src="https://github.com/user-attachments/assets/a9d709c2-7be4-4b02-bdf6-841fd478c6af" />

Adicionar, editar e excluir produtos.

Campos de nome, preço, quantidade, categoria, descrição.

Atualização automática na tabela principal.

✔ Gestão de Usuários

<img width="593" height="426" alt="Captura de tela 2025-11-25 141037" src="https://github.com/user-attachments/assets/f793c3a8-1294-4502-af26-7c4d32f38113" />
<img width="215" height="143" alt="Captura de tela 2025-11-25 141108" src="https://github.com/user-attachments/assets/65a8ae97-0cff-4b60-8b82-2c34eefafa11" />

Criar novos usuários com tipo (Administrador ou Funcionário).

Ativar/desativar usuários.

Edição simplificada.

✔ Seed Inicial

Criação automática do banco e usuários padrão caso não existam.

🖼️ Prints das Telas (adicione aqui suas imagens)

Basta colocar seus prints na pasta /assets e substituir pelos links abaixo.

📌 Tela de Login

📌 Tela Principal

📌 Tela de Produtos

📌 Tela de Usuários

▶️ Como Executar o Sistema

1. Instale as dependências
pip install pyqt5

2. Execute o projeto
python main.py

3. Caso seja a primeira execução, o sistema criará automaticamente o banco de dados e o usuário Admin inicial.

📌 Usuário Padrão (Primeira Execução)

Email: admin@admin.com

Senha: admin123

(Você pode alterar isso no seed.py)

🛠️ Melhorias Futuras

Relatórios em PDF

Controle financeiro

Controle de vendas

Dashboard com gráficos

🤝 Contribuindo

Fique à vontade para abrir issues ou enviar pull requests!

📜 Licença

Este projeto é de uso livre para fins educacionais.
