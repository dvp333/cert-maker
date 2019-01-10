# Script de Criação de Certificados

Este script tem como objetivo criar os certificados e keystores necessários para se configurar uma autenticação mútua.


## Requisitos

* Ser administrador da máquina
* OpenSSL instalado


## Iniciando

* Executar o CMD como administrador
* Ir para o caminho do arquivo cert-maker.bat 
* Executar o comando: cert-maker.bat


## Campo Common Name (CN)

### Certificado do Servidor

Deve ser preenchido com o nome do host do servidor (Ex.: localhost, meudominio.com.br)


## Informações Importantes

* O arquivo keystore.jks gerado contém o certificado do servidor
* O arquivo cacerts.jks gerado contém o certificado da Autoridade Certificador de Teste (CA)
* Ao todo são gerados 3 certificados: ca, servidor e cliente
