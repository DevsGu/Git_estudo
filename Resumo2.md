# 🐱Configurando Git

 Nessa etapa básicamente entendemos qual a função do git config. De forma geral ,  o git config permite visualizar e definir variaveis(variaveis de armazenamento) de configuração do git.

- git config -- global : Configuração do Usuario
- git config -- System : Configuração do Sistema
- git Config -- local : Configuração de algum repositorio em especifico

## Definindo Nome , Email e Nome da Branch principal

- git config --global user.name = "Gustavo"
- git config --global user.email =  "guga2323@gmail.com"
- git config init.defaultBranch (retorna nome da Branch principal)
- git config --global init.defaultBranch (nome da Branch desejado)

## Ver todas as alterações feitas
- git config --global --list
