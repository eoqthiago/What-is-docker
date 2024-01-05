# What-is-docker
O que é docker? What is docker?
baseado no livro: [Docker - Do básico à Certificação Docker DCA](https://leanpub.com/dockerdca)
<br>
autor: Caio Delgado

## O que é Docker?
<p>Docker é uma plataforma Open Source escrita em Go, que ajuda na criaçãoe e na administração de ambientes isolados</p>
<p>Com a criação do docker podemos gerenciar toda infraestrutura de uma aplicação</p>

<P>O docker trabalha com uma virtualização a nivel do sistema operacional, onde o mesmo utiliza de recurso como o kernel
 do sistema hospedeiro para executar seus containers. Diferentes do modelo tradicional de maquinas virtuais, o docker não necessita de uma instalação de um sistema operacional por completo, e sim apenas dos arquivos necessarios para a aplicação ser executada.</p>

<img width=600px src="https://images.contentstack.io/v3/assets/blt300387d93dabf50e/bltb6200bc085503718/5e1f209a63d1b6503160c6d5/containers-vs-virtual-machines.jpg">


## Por que usar Docker?
<p>Em 2013, docker trouxe uma maneira simples, rápida e eficiente de executar aplicações sem uma maquina virtual. Docker garante um ecossistema consistente</p>

## O que é um container?
<p>Um container consiste de um ambiente completo (uma aplicação e todos suas dependencias, bibliotecas, binarios, arquivos de configurações) em um unico pacote,
É onde se guarda as dependencias do projeto, assim podemos iniciar o projeto em outra maquina e ira funcionar normalmente, o tempo que se gastaria com a instalação de depencias seria zero, diferente do tempo que se gastaria da forma manual.</p>