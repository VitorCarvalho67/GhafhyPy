# GRAFHY (Rede social)

Ambiente virtual para comunicação de usuarios através de mensagens, posts e imagens.
Além disso o usuário pode criar grupos de conversa e adicionar outros usuários.
Possui um sistema de login e cadastro de usuários.
Ambiente de postagem de imagens e mensagens.
Possui um sistema de verificação de usuários online.
Mensagens em tempo real e criptografadas.
Sistema de notificações de mensagens e posts.
Perfil de usuário com informações e foto de perfil.
Senhas criptografadas.
Banco de dados em MySQL.

<p align="center">
  <img src="https://github.com/Daniel-Alvarenga/Grafhy_Py/assets/128755697/0b79591f-2d8d-4e0d-865a-4ff90a3fcd36"/>
</p>

## How To Use

```bash
git clone https://github.com/VitorCarvalho67/GrafhyPy.git
```

Navigate to the project directory on sever side
```bash
cd GrafhyPy/server
```

Create a virtual environment (venv) for the project
```bash
python -m venv venv
```

Activate the virtual environment.
On Windows:
```bash
.\venv\Scripts\activate
```

On macOS and Linux:
```bash
source venv/bin/activate
```

Install the project's dependencies from requirements.txt.
```bash
pip install -r requirements.txt
```

## Running the server side
```bash
uvicorn main:app --reload
```
Navigate to the project directory on client side
```bash
cd ../client
```
## Running the cclient side
```bash
npm run dev
```


