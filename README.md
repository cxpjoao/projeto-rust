# projeto-rust
📽️ Projeto Locadora de Filmes - FILME-TESTE
📋 Descrição do Projeto
O FILME-TESTE é uma aplicação desenvolvida como exercício de aula utilizando as linguagens Rust, JavaScript, HTML e CSS.
O projeto simula uma locadora de filmes online, na qual o usuário pode:

Acessar a plataforma

Escolher um filme

Realizar o pagamento

Assistir ao conteúdo adquirido

Importante: O modelo de negócios é pay-per-view, ou seja, o usuário paga apenas pelos filmes que deseja assistir, sem mensalidade fixa.

🛠️ Tecnologias Utilizadas

Tecnologia	Descrição
Rust	Backend responsável por servir os arquivos HTML e lógica de controle
HTML5	Estrutura das páginas da aplicação
CSS3	Estilização visual das páginas
JavaScript	Dinamismo das páginas e validações no lado do cliente
🏗️ Estrutura do Projeto

FILME-TESTE/
├── .vs/                # Configurações do Visual Studio
├── src/
│   └── main.rs         # Código principal em Rust (servidor e lógica)
├── static/
│   ├── img/            # Imagens utilizadas nos sites
│   ├── assistir.html   # Página para assistir ao filme
│   ├── escolher.html   # Página para escolher um filme
│   ├── login.html      # Página de login do usuário
│   └── pagamento.html  # Página para pagamento do filme escolhido
├── target/             # Diretório de build do cargo (compilação)
├── .gitignore          # Arquivos ignorados pelo git
├── Cargo.lock          # Dependências travadas do projeto Rust
├── Cargo.toml          # Configurações do projeto Rust
└── README.md           # Arquivo de documentação
📄 Funcionalidades
Login de Usuário: Página de login simples para validar o acesso.

Escolha de Filme: Página que lista os filmes disponíveis para aluguel.

Sistema de Pagamento: Página de pagamento para compra individual do filme selecionado.

Assistir ao Filme: Após o pagamento, o usuário é redirecionado para a página de exibição do filme.

🚀 Como Executar o Projeto
Pré-requisitos:

Ter o Rust instalado na máquina

Ter um navegador web atualizado (Chrome, Firefox, Edge, etc.)

Clone o projeto:
git clone <URL-do-repositório>
cd FILME-TESTE
Compile e execute o servidor Rust:

bash
Copy
Edit
cargo run
Acesse via navegador:

Normalmente o servidor local é iniciado em http://localhost:8000/ (depende da configuração no main.rs).

📦 Estrutura das Páginas HTML

Página	Função
login.html	Formulário de login do usuário
escolher.html	Tela com a lista de filmes disponíveis para compra
pagamento.html	Tela de pagamento por filme
assistir.html	Tela de reprodução do filme comprado
🧩 Melhorias Futuras
Implementar autenticação de usuários de forma segura (com banco de dados)

Integrar métodos de pagamento reais (como Stripe ou PayPal)

Criar um sistema de histórico de filmes assistidos

Adicionar filtros de busca por gênero, ano, etc.

Implementar responsividade total usando CSS moderno (Flexbox / Grid)

👨‍💻 Sobre
Este projeto foi desenvolvido como parte de um curso prático de Rust.
Visa aplicar conceitos de back-end básico, manipulação de arquivos estáticos, rotas HTTP, além de integração com front-end usando HTML, CSS e JavaScript.

📢 Observação
Este é um projeto educacional, sem fins comerciais.

📑 Exemplo de Fluxo do Usuário
O usuário acessa a página de login (login.html) e faz o login.

Após o login, é redirecionado para a página de escolha do filme (escolher.html).

Escolhido o filme, é levado para a página de pagamento (pagamento.html).

Finalizado o pagamento, o usuário pode assistir ao filme (assistir.html).

