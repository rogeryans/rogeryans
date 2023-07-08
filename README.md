- 👋 Hi, I’m @rogeryans
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
rogeryans/rogeryans is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Banco de dados de usuários
database = {
    'user1': 'password1',
    'user2': 'password2',
    'user3': 'password3'
}

def login():
    username = input("Digite seu nome de usuário: ")
    password = input("Digite sua senha: ")

    # Verificar se o usuário existe e a senha está correta
    if username in database and database[username] == password:
        print("Login bem-sucedido!")
        # Resto da lógica do seu aplicativo após o login
    else:
        print("Nome de usuário ou senha incorretos.")

# Exemplo de uso
login()

