# login-systemReactJS

## Sistema de Login em reactJS com autenticação de usuário

### Crie uma pasta para ficar o projeto e utilize o seguinte código:

`npx create-react-app ./`

### Instale as seguintes extensões

`yarn add styled-components react-router-dom`

### Após isso apague todos arquivos do public, exceto o index.html e crie um src novo com app.js e index.js, configurando da mesma forma projeto

#### nessa parte o index.js estará fazendo um root para geração da pagina web, puxando o id do projeto index.html, já o arquivo app.js que estará as funcionalidades do nosso código

### `yarn start` para rodar na porta local 3000

![projetoapp](https://user-images.githubusercontent.com/79342387/218337056-9c20d1b0-5995-4812-ad52-1ad50338f72f.png)


### Após isso dentro de src é criado as seguintes pastas:

### styles/global
### pages
* Home
* Signin
* Signup
### routes

#### No routes é onde fica nossas rotas, é nele que é responsavel pelo direcionamento de telas e por privar o usuario de alguma tela em específico

![routes](https://user-images.githubusercontent.com/79342387/218342484-8250c278-17e0-412e-9e93-14a365bd221e.png)

#### É sempre importante fazer o import e o export!

### Após isso na pasta src crie o contexts para ser feita todas as autenticações de token e usuários do banco

![context](https://user-images.githubusercontent.com/79342387/218574511-936e0010-3fbe-48cd-82ed-b5d1bf39894f.png)

### feito isso é criado uma pasta chamada hooks que vai ser responsável por utilizar toda a nossa autenticação

### finalizando esse processo é preciso importar o `AuthProvider` para o arquivo app.js

![provider](https://user-images.githubusercontent.com/79342387/218574595-4ed2e7f1-088f-4584-8553-c12952e5c2f4.png)




