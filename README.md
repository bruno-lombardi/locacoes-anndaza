# Sistema de Automação para Locações

Sistema desenvolvido para empresa de locações de andaimes e outros produtos na área de construção civil. Este sistema não funciona
sem conexão ativa com a Internet. No entanto, é preciso também adquirir um servidor HTTP, pois este cliente se comunica com uma
API para realizar todas as operações.

## Onde adquirir ou fazer download?
É possível [fazer o download deste sistema gratuitamente](https://bintray.com/bruno-lombardi/automacao-comercial/AutomacaoComercial#).
No entanto, notará que o acesso as funcionalidades é restrito, por dois motivos:
- O sistema está em fase de desenvolvimento
- É preciso uma API (Application Programming Interface) do sistema, que é solicitada no momento em que o sistema é inicializado. Sem
esta API é impossível utilizar o sistema. Além de uma API, é necessário um usuário e senha cadastrados.

### O que é uma API?
Conforme explicitado acima, este sistema se comunica com um servidor HTTP para processar os dados. Assim, todos os dados são salvos
na Internet, de modo que este sistema funciona em arquitetura cliente <-> servidor. Enquanto estiver em desenvolvimento, nenhuma API
será disponibilizada.

## Como adquirir uma API?
O acesso à APIs será através de assinaturas pagas, cujo valor ainda é indefinido, e método de compra ou assinatura também é indefinido.
Mais informações serão liberadas com o desenvolvimento do programa.

## Cadê o código fonte?
Este repositório é apenas para informar sobre o status do software, bem como fazer o download do mesmo. Abaixo estão as principais
tecnologias usadas para desenvolver este software.

- [ElectronJS](https://github.com/electron/electron)
