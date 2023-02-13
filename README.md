Painel de Login

- Nome do usuário;
- Senha do usuário;
- Email do usuário;
- Interface de Login e Registro;
- Esqueceu a senha/Recuperar senha;
- Alterar a senha;
- Conta inexistente/dados inv´álidos.

Nome de usuário [x]

Usado para identificar o usuário.

Senha do usuário [x]

Usado para logar na conta do usuário.

Email do usuário [x]

Usado como forma de registro para caso haja uma perca de senha ou solicitação
de alteração da mesma, enviarmos um código ao email utilizado.

Interface [x]

Todo o design composto pela interface que o usuário terá acesso ao fazer login/registro.

Esqueceu a senha [x]

Utilizado como uma forma de recuperar a senha da conta, caso tenha esquecido/perdido.

Alterar a senha [x]

Uma opção para o usuário, caso deseje alterar a senha.

Conta inexistente/dados inválidos [x]

Mensagem na tela informando dados inválidos/conta inexistente.

----------------------------

Possibilidades:

CreateMoreThanOneAccount? = false;
ChangePassword? = true;
DeleteAccount? = only admin;

---------------------------

    1. Ao usuário adentrar ao servidor, depois da loadscreen, será a primeira tela que o usário terá acesso;
    2. Na interface o usuário terá a opção de logar (caso tenha uma conta) ou se registrar (caso não tenha conta).
    3. Caso tenha esquecido/perdido a senha, o usuário pode recuperá-la.
    4. O usuário poderá solicitar a alteração da senha.
    5. Mensagens de erros serão exibidas caso algo não esteja de acordo com o esperado.
    6. Uma conta poderá ser deletada apenas por um ADMIN.

---------------------------

STACKS:
    LUA: Eventos
    Design: Figma
    (Não faço ideia se tá certo)