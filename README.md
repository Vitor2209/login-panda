🐼 Login UI – Panda Auth Screen

Uma interface moderna de login inspirada em um design minimalista, com foco em animações suaves, glassmorphism e experiência fluida.
O projeto inclui modo dark/light, avatar personalizado e simulação de backend.

🌟 Recursos do Projeto

✨ Design refinado com acabamento moderno e visual premium

🧊 Glassmorphism reforçado aplicado no container, inputs e botões

📱 Totalmente responsivo — funciona em desktop, tablet e mobile

🌗 Dark/Light Mode com persistência via LocalStorage

👤 Avatar vetorizado personalizado na área superior do card

🎬 Animações suaves usando CSS (hover, transitions, fades)

🔄 Fake Backend em JavaScript para simular autenticação real

🔧 Código organizado e fácil de editar e expandir

📁 Estrutura do Projeto
📦 login-panda-ui
├── index.html
├── assets/
│   ├── avatar.png
│   ├── bg-pattern.svg
│   └── icons/
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md

🚀 Como Executar

Clone o repositório:

git clone https://github.com/Vitor2209/login-panda-ui.git


Abra o arquivo:

index.html


Pronto! O projeto roda direto no navegador — nenhuma instalação adicional necessária.

🌗 Dark & Light Mode

Um botão no topo do formulário alterna entre os dois temas.
O tema selecionado é salvo automaticamente no localStorage, garantindo persistência da escolha do usuário.

🧪 Fake Backend (Simulação de Login)

A lógica de autenticação usa um usuário mockado no arquivo script.js:

const mockUser = {
  email: "example@gmail.com",
  password: "123456"
};


Você pode alterar, adicionar mais usuários ou integrar a uma API real futuramente.

🖼️ Avatar Personalizado

O avatar padrão da interface foi substituído por uma imagem vetorizada/PNG premium.
Para trocar por outro avatar, basta substituir o arquivo:

/assets/avatar.png

🛠️ Tecnologias Utilizadas

HTML5

CSS3

JavaScript (ES6+)

Glassmorphism

Responsividade

LocalStorage

Mock Backend

👤 Autor

Vitor Melo
🧑‍💻 Desenvolvedor Front-end

📬 Email: vitordutra1125@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/vitordutramelo/

🐙 GitHub: https://github.com/Vitor2209

