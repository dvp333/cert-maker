# cert-maker

Este script tem como objetivo criar os certificados e keystores necessários para se configurar uma autenticação mútua.

### Pré Requisitos

OpenSSL instalado

## Iniciando

Para executar o script basta executar o arquivo cert-maker.bat como administrador.

## Informações Importantes

* O common-name (CN) do certificado do servidor deve ser preenchido com o nome do host do servidor (Ex.: localhost, meudominio.com.br);
* O arquivo keystore.jks gerado contém o certificado do servidor;
* O arquivo cacerts.jks gerado contém o certificado da Autoridade Certificador de Teste (CA);
* Ao todo são gerados 3 certificados: ca, servidor e cliente.

