---
title:  "Startup e shutdown de uma instância Oracle"
date:   2015-09-21 09:20:00
categories: posts
layout: post
---

Entender como uma instância pode ser iniciada ou parada no banco de dados oracle é muito importante para um administrador de banco de dados, existem alguns problemas que podem ser resolvidos em determinado stagio da instância.

Para iniciar uma instância podemos usar o comando startup no sqlplus, mas atenção a essa parte pois o usuário deve ter permissões de DBA.
Podemos usar varias combinações de startup:
<ul><li>startup</li><li>startup nomount</li><li>startup mount</li></ul>

h1. O que acontece em cada estágio:

*startup nomount*

Nesse estágio o Oracle lê o arquivo de inicialização, que pode ser o init_sid.ora ou o spfileSID.ora, onde ele encontra alguns parametros que vão ser usados na configuração da instância.
Depois de ter lido o arquivo, as áreas de memória são configuradas de acordo com o que estava no arquivo de parâmetro e os processos de background são startados.

*startup mount*

Caso o banco já esteja no modo nomount, você pode executar um comando _alter database mount_
