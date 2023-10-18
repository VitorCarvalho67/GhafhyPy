# GRAFHY (social media)

GRAFHY is a virtual communication platform that enables users to exchange messages, posts, and images. Furthermore, it offers features such as creating conversation groups, user login and registration, real-time encrypted messaging, message and post notifications, user profiles with photos, and encrypted passwords. Its MySQL database ensures efficient management of user interactions, making it a comprehensive and secure platform for online communication.

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


