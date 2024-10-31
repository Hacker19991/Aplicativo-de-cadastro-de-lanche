# **AppProva3 (Aplicativo de cadastro de lanche)**

> Um aplicativo Android desenvolvido para cadastrar novos usuários e fazer pedidos de lanche neste aplicativo.

## Descrição
O **AppProva3** permite ao usuário poder cadastra e logar seus dados e poder fazer pedidos atrávez do catalogo e acessar o Whatszapp para fazer o seu pedido.

## Funcionalidades
- [x] Entrada de dados de consumo
- [x] Cálculo e exibição de estatísticas de consumo
- [x] Gráficos interativos para visualização dos dados
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes tipos de recursos (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   https://github.com/Hacker19991/Aplicativo-de-cadastro-de-lanche
   
2. Abra o projeto no Android Studio.
   
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projeto

```
── app
   ├── src
   │   ├── main
   │   │   ├── java/com/example/appconsumo
   │   │   │   ├── CadastroActivity.java # Ativiade onde será executado o cadastro com os devidos
   │   │   │   ├── CatalogoActivity # Atividade onde mostrara o catalogo da lanchonete e terá o acesso ao Whatszapp da lanchonete
   │   │   │   ├── DataBaseHelper # Onde a DataBase ira amarzenar os dados do usuário e salvos para caso o usuário queira entrar de novo  
   │   │   │   ├── LoginActivity.java # Atividade onde o usuário podera logar com seus dados e acessar o catalogo e poder cadastrar seus dados
   │   │   ├── res
   │   │   │   ├── layout
   │   │   │   │   ├── activity_cadastro.xml # Layout onde o usuário podera cadastrar seus dados
   │   │   │   │   ├── activity_catalogo.xml # Layout onde o usuário podera ver o catalogo da lanchonete e acessar o Whatszapp
   │   │   │   │   ├── activity_Login.xml # Layout onde o usuário podera logar com seus dados e acessar o catalogo e poder cadastrar seus dados
   │   │   │   └── values
   │   │   │       ├── strings.xml # Strings usadas no app
   │   │   │       ├── colors.xml # Cores definidas no projeto
   └── build.gradle # Configuração do Gradle
```

## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

> Tela Login

![image](https://github.com/user-attachments/assets/1115f801-3638-443e-b48d-7d181f9111f5)

Uma tela simples, as imagens são opicionais "Elas são colocadas por imagemView e selecione a pasta com as imagens pré-selecionadas", 2 EditText para, o Email cadastro do usuário e a senha criada para o usuário poder acessar o catalogo, 2 botões para acessar o catalogo e poder cadastrar seus dados para serem logados mais tarde quando quiser acessar o catalogo, e no final o TextView para ser usado como titulo principal da tela.

> Tela Cadastro

![image](https://github.com/user-attachments/assets/3083c845-cec5-427e-a2c3-8660680233c0)

Uma tela simples, as imagens são opicionais "Elas são colocadas por imagemView e selecione a pasta com as imagens pré-selecionadas", 4 EditText para, Nome do usuário, o Email do usuário, Telefone do usuário e a senha do usuário assim sendo salvo no DataBase, um botão para salvar os dados de maneira correta para serem usados no login assim acessando o catalogo.

> Tela Catalogo

![image](https://github.com/user-attachments/assets/0e552375-64db-4148-af0f-50d5af6307aa)

Uma tela simples, as imagens são opicionais "Elas são colocadas por imagemView e selecione a pasta com as imagens pré-selecionadas, neste caso o catalogo é uma imagem montada e usada como ImagemView", um LinearLayout onde dentro tera um botão para acessar o Whatszapp da lanchonete(o número pode ser trocado para qual quiser apenas trocando no código) e um TextView para ser usado como titulo para o catalogo.

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
