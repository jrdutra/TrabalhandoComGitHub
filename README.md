# Trabalhando com GitHub - Guia Básico

Nesse guia eu registro as instruções básicas para trabalhar com GITHUB pelo terminal do LINUX

## Instalando o GIT no LINUX

### Comando de instalação no terminal LINUX

```
sudo apt-get install git
```

## Criando o reposítório

### Passos

+ Acessar o link da [Home do GitHub](https://github.com/).
+ Clicar no botão verde onde está escrito **new**.
+ Informar o nome do repositório no campo **Repository name**.
+ Lembrar de marcar o *Add a README File*.
+ Por fim, clicar no botão **Create repository**.

## Clonando o repositório na máquina

### Passos

+ Para clonar o repositório, você precisar pegar o link no repositório a ser clonado no site .
do github ( [Exmeplo deste repositório](https://github.com/jrdutra/TrabalhandoComGitHub) ).
+ Abrir o terminal em uma pasta onde deseja que o repositório seja clonado.
+ Digitar o seguinte comando(Nesse caso mostro o exemplo para esse repositório): ```git clone https://github.com/jrdutra/TrabalhandoComGitHub```.

## Configurando o repositório

### Passos

+ Abra o terminal dentro da pasta do repositório clonado.
+ Digite o seguinde comando para configurar usuário e senha: ```git remote set-url origin https://username:password@github.com/jrdutra/TrabalhandoComGitHub```
(Exemplo deste repositório).

## Adicionando modificações, comitando e enviando pelo terminal LINUX

### Passos

+ Abra o terminal dentro da pasta do repositório clonado.
+ Para adicionar as modificações: ```git add --all```
+ Para comitar as modificações adicionadas: ```git commit -m "Sua Mensagem"
+ Para enviar as modificações comitadas: ```git push```

### Alternativa prática para a sequência de comantos anteriores

Se caso você não quiser digitar esses comandos todas as vezes que precisar enviar uma modificação, basta criar um arquivo com a extensão **.sh** *(Ex.: commit.sh)*
no diretório do repositório com o seguinte código:
```
#!/bin/bash
git add --all
git commit -m "Passos-GitHub"
git push
read
```

E então dar a permissão de execução para o arquivo, que pode ser feita pelo comando:
```
sudo chmod 777 commit.sh
```

Nesse ponto basta clicar no arquivo que ele executa todos os procedimentos de adicionar, commitar e enviar.

**Possível problema**
Pode acontecer do seu linux não estar configurado para abrir o arquivo .sh com o terminal, muitas das vezes ele abre em um programa editor de texto.
Para resolver esse problema, você precisa abrir esse arquivo com o terminal e setar isso como padrão, isso varia de versão de linux para linux.


