Calculadora Simples em Python 🐍
Este é um projeto com o código de uma calculadora básica feita em Python. Aqui você vai aprender como:

Copiar este projeto para o seu computador,
Criar um atalho para rodar a calculadora (usando o CMD no Windows ou o Terminal no Linux/Mac),
Fazer esse atalho funcionar,
E ajustar quem pode ou não mexer nesse atalho.
Como Rodar a Calculadora
Siga estes passos:

Copiar o Projeto
Primeiro, copie todos os arquivos deste projeto para o seu computador.

Achar a Pasta do Projeto
Depois de copiar, vá até a pasta onde você salvou os arquivos. Use o comando cd seguido do caminho da pasta. Por exemplo:

Bash

cd caminho/para/sua/pasta
Criar o Atalho calculadora.sh
Vamos criar um arquivo que vai servir como um atalho para abrir a calculadora. Digite no seu terminal:

Bash

nano calculadora.sh
Isso vai abrir um editor de texto simples chamado "nano". Dentro desse editor, cole o seguinte texto:

Bash

#!/bin/bash
# Este comando vai rodar a calculadora Python
python3 calculadora.py
Depois, salve e feche o editor (no nano, geralmente é Ctrl+X, depois Y e Enter).

Fazer o Atalho Funcionar
Para que o computador entenda que esse arquivo pode ser "executado" (ou seja, rodado), você precisa dar uma permissão especial a ele. Digite:

Bash

chmod +x calculadora.sh
Isso basicamente diz: "Ei, computador, este arquivo calculadora.sh pode ser rodado!".

Ajustar Quem Pode Usar o Atalho
Para mais segurança, vamos definir quem pode fazer o quê com esse arquivo. Com o comando abaixo, só o dono do arquivo poderá alterá-lo, e as outras pessoas só poderão ler e rodar:

Bash

chmod 744 calculadora.sh
Rodar a Calculadora! 
Agora sim! Para abrir sua calculadora Python, é só digitar no terminal:

Bash

./calculadora.sh
O que Você Precisa Ter
Python 3.10 (ou uma versão mais nova)
Um Terminal (se você usa Linux ou Mac) ou o Git Bash (se você usa Windows)