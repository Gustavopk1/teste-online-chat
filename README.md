*Bem-vindo ao Aplicativo de Chat Online!*

Este projeto é uma plataforma de chat em tempo real que permite aos usuários se comunicarem de forma simples e eficiente através da web.

*Como clonar o projeto*
Siga as etapas abaixo para clonar o repositório:

1- Abra o terminal ou prompt de comando no seu computador.
2- Execute o seguinte comando para clonar o repositório: git clone https://github.com/yourusername/online-chat.git

3- Acesse a pasta do projeto: cd online-chat

4- Rode o projeto: python main.py

*Para hospedar no versel*

5- Crie o arquivo requirements.txt dentro da raiz do projeto: pip freeze > requirements.txt

6- Crie na raiz do projeto o arquivo (vercel.json) e cole a seguinte informação:

{
  "version": 2,
  "builds": [
    {
      "src": "app.py",
      "use": "@vercel/python"
    }
  ],
  "routes": [
    {
      "src": "/(.*)",
      "dest": "app.py"
    }
  ]
}

7- suba todas as informações para seu repositório no github

*Email:* samuelvitoopo@gmail.com
*GitHub:* vitorreplit