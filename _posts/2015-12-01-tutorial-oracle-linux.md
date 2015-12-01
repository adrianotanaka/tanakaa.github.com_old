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

**5-** Agora devemos selecionar o idioma e o layout do teclado, aqui recomendo já selecionar a opção ABNT2, pois depois do sistema instalado é meio confuso para trocar essa configuração.


![](http://i.imgur.com/spop0Xg.png)![](http://i.imgur.com/F5LnMNx.png)

**6-** Nesse momento, as configurações vão ser especificas do seu ambiente, agora iremos configurar opções de disco.

Em nosso ambiente, iremos selecionar a primeira opção **Basic storage devices**, clique nela e depois em **Next**
![](http://i.imgur.com/dRtUmyg.png)

**7-** Um alerta de que estamos zerando o disco vai ser exibido, clique em **Yes, discard any data** e prossiga
![](http://i.imgur.com/QkgcM8C.png)

**8-** Devemos selecionar o nome da nossa máquina, caso você possua um dominio, siga esse padrão para definir o nome da máquina: **nome_da_maquina.dominio**

Opcionalmente a rede já pode ser configurada, em nosso ambiente isso não é necessário pois iremos pegar um ip a partir de um dhcp.
![](http://i.imgur.com/VWAt7yA.png)

**9-** Selecione o local onde o servidor estará, isso irá ajustar o fuso horário da máquina.
Selecione a cidade e clique em Next.
![](http://i.imgur.com/Lvixsmi.png)

**10-** 
## IMPORTANTE##
Aqui a senha do usuário root deve ser entrada, coloque uma senha que você vai se lembrar, apesar de todo o gerenciamento do banco de dados ser feito com o usuário Oracle(por padrão), iremos precisar do usuário root para realizar algumas configurações.
![](http://i.imgur.com/SlT7tUG.png)

Caso a senha seja fraca, um alerta vai ser exibido, basta clicar em **Use anyway** que a instalação vai continuar.
![](http://i.imgur.com/IVarXov.png)

