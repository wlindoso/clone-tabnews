# Projeto de aprendizado geral utilizando o Clone do Tabnews

## Verificando a versão Node.js e NVM instalados na nossa máquina

```
node -v // retorna versão Node.js
nvm -v // retorna versão Node Version Manager(nvm)

```

## Instalando NVM e Node.js

### No Linux / MacOS

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

### No Windows

- Devemos baixar o
  [script de instalação do NVM e Node.js](https://github.com/coreybutler/nvm-windows/releases)
- Em assets devemos baixar a versão: nvm-setup.exe
- Instalar o NVM em nosso PC

## Verificando versões do Node.js instalados na nossa máquina

```
nvm ls // Lista as versões instaladas em nosso computador.
nvm ls-remote // Lista todas as versões disponíveis no repositório do Node.js
nvm ls available // Lista todas as versões disponíveis no repositório do Node.js

```

## Instalando uma versão do Node.js

```
nvm install 18.14.2 // instala uma versão '18.14.2' do Node.js
nvm use 18.14.2 // Seta a versão '18.14.2' do Node.js, como versão atual.

```

## Tipos de instalação de pacotes utilizados no projeto

```
npm install next // Instala o pacote 'next' de forma local: aparece no package.json
npm install next -g // Instala o pacote 'next' como pacote global
npm install next -D // Instala o pacote 'next' como pacote de desenvolvimento.
npm install next -D -g // Instala o pacote 'next' como pacote global e de desenvolvimento.
```

## Rodando o projeto

Necessário adicionar scripts abaixo no arquivo **package.json**

```
npm run dev // Roda o projeto em modo de desenvolvimento.
npm run start // Roda o projeto em modo de produção.
npm start // Também roda o projeto em modo de produção.
npm test // Roda os testes do projeto.
```

## Lista de comandos Git

```
git log // listar os commits do repositório.
git log --stat // mostra o historico do repositório.
git add // sobe alterações para a staging area.
git commit // realiza novos commits.
git commit --amend // subsitui o commit anterior por um novo, mas aproveita as alterações dele.
git diff // calcula a diferença entre as versões/alterações dos arquivos.
git status // verifica o status do repositório.
```

## Etapas para realização de um commit

```
git add . // Adiciona todos os arquivos do projeto.
ex.: git add .
git add file_name // Adiciona um arquivo especifico.
ex.: git add README.md
git commit -m // Adicionando novas funcionalidades no projeto.
ex.: git commit -m "Adicionando novas funcionalidades no projeto"
git push origin master // Faz o push do projeto para o repositório.
ex.: git push
```

##
