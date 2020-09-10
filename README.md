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
