---
published: false
---

## [Tutorial] Instalando e preparando o Oracle Linux 6 para rodar o Oracle 11g ou 12c

Para esse tutorial, iremos usar um host Windows e criar uma máquina virtual no VirtualBox rodando Oracle Linux 6.5 e já prepara-la para rodar um banco 11g ou 12c.

**Configuração da máquina virtual:**
![](http://i.imgur.com/ZogFkmL.png)
**- Nome da máquina:** [OracleLinux]

**- Sitema operacional:** Oracle(64bit)

**- Memória:** 1024Mb

**- CPU:** 1 core

**- Tamanho do disco:** 42Gb

## Iniciando a instalação


**1-**Essa é a tela de boas vindas de instalação do Oracle Linux 6.5, nela devemos selecionar a opção **Install or upgrade an existing system** .
![](http://i.imgur.com/H06AEza.png)



**2-**Caso queiram verificar a integridade do disco gravado, selecione a opção **Ok**, mas aviso que essa operação é muito demorada e não recomendada, por isso vamos selecionar a opção **Skip** .
![](http://i.imgur.com/NlfWNAo.png)



**3-**Existem diversas máquinas que são suportadas de forma oficial pelo Oracle Linux, em nosso ambiente essa mensagem vai ser apresentada, informando que nossa máquina não é homologada.

Em um ambiente de produção, isso deve  ser levado em conta, se vamos usar o Oracle linux ou instalar uma outra distribuição que seja homologada para o banco de dados Oracle.

No nosso ambiente de teste, vamos dar um enter e prosseguir com a instalação.
![](http://i.imgur.com/nqA4ieh.png)

**4-** Depois dos passos inicias, somos apresentados a tela do inicio da instalação do Oracle Linux, ela é semelhante as telas de outras distribuições(Red Hat, CentOS, etc).
![](http://i.imgur.com/pF91SBx.png)


