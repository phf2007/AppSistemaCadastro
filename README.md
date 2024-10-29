# App Sistema Cadatro

> Um aplicativo Android simples para cadastras e listar contas.

## 📱 Descrição

O **AppSistemaCadastro** permite ao usuário criar uma conta e ver listar contas foram logadas no aplicativo com nome, cpf e número de telefone.

## 🔧 Funcionalidades

- [x] 2 Telas, uma para listar e a outra para criar usuários
- [x] Áreas para preencher com seu telefone, nome e cpf, além de botões para entrar na tela de listagem de usuários e para salvar o usuário
- [x] Exibição dos usuários cadastrados com uma ArrayList
- [x] Interface simples e intuitiva
- [ ] Tema claro e escuro (planejado para futuras versões)

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **Button** e **EditText**

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:


1. Clone este repositório:
    ```bash
    git clone https://github.com/phf2007/AppSistemaCadastro/AppSistemaCadastro.zip
    ```

2. Abra o projeto no Android Studio.

3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

AppSistemaCadastro
├── app
│   ├── main
│   │   ├── java/br.ulbra.AppSistemaCadastro
│   │   │   ├── MainActivity.java                  # Atividade principal com login
│   │   │   ├── PessoaDB.java                      # Atividade que puxa as pessoas do banco de dados pra lista
│   │   │   ├── ListarPessoaActivity.java          # Atividade que lista as pessoas
│   │   │   ├── Pessoa.java                        # Atividade que registra as pessoas no banco de dados
│   │   ├── res
│   │   │   ├── layout
│   │   │   │   ├── activity_main.xml              # Layout da tela principal
│   │   │   │   ├── activity_listar_pessoa.xml     # Layout da tela de listar pessoas
│   │   │   └── values
│   │   │       ├── strings.xml                    # Strings usadas no app
│   │   │       ├── colors.xml                     # Cores definidas no projeto
│   └── build.gradle                               # Configuração do Gradle
└── README.md                                      # Este arquivo



## 🎨 Design e Prototipagem 

A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela. 

O design é minimalista e fácil de usar, com foco na simplicidade.

 ## 🖥️ Telas do Aplicativo

**Tela Principal** 

Na tela principal, teremos três caixas de textos, uma alfabética para escrever seu nome, e duas numéricas para escrever seu cpf e telefone, abaixo delas teremos dois botões, um para salvar o usuário e outra para listar os usuários já cadastrados nela

**Tela Secundária** 

Na tela secundária, teremos uma lista de todos os usuários que se cadastraram nela e um botão para voltar para a tela inicial

## 👨‍💻 Desenvolvedores – 
Pedro Henrique Fontes - Desenvolvedor - [GitHub](https://github.com/phf2007)
