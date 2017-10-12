Welcome to the SocialAPI-v2-Doc wiki!

Esta documentação cobre 100% dos endpoints da SocialAPI em sua versão 2.

### Consideração inicial

Todos os endpoints exigem o JWT Token.

### Considerações sobre os endpoints que envolvem o vínculo de imagens digitalizadas à atributos da pessoa

Estes endpoints consideram que [você já fez o upload](https://github.com/BRAConsultoria/StorageAPI-Doc/wiki/Manipulando-documentos#upload-com-promise) da imagem para StorageAPI e recebeu a chave pública {file_id} que identifica o arquivo de imagem enviado. 


***


# Pessoa física

* [Pesquisando pelo CPF](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Pesquisando-pelo-CPF)
* [Obtendo o cache global de pesquisas](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Obtendo-o-cache-global-de-pessoa-f%C3%ADsica)
* [Obtendo os últimos cadastros acessados pelo usuário](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Obtendo-os-%C3%BAltimos-cadastros-acessados-pelo-usu%C3%A1rio)
* [Obtendo a classificação de um documento](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Classifica%C3%A7%C3%A3o-de-documentos-digitalizados#obtendo-a-classifica%C3%A7%C3%A3o-de-um-documento)

### Nome

* [Obtendo o nome](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Nome#obtendo-o-nome-de-uma-pessoa)
* [Alterando o nome](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Nome#alterando-o-nome-de-uma-pessoa)
* [Vinculando uma imagem](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Nome#vinculando-uma-imagem-a-um-nome)
* [Removendo uma imagem](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Nome#removendo-o-v%C3%ADnculo-de-uma-imagem-de-um-nome)

### Nome social

* [Obtendo o nome social](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Nome-social#obtendo-o-nome-social-de-uma-pessoa)
* [Alterando o nome social](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Nome-social#alterando-o-nome-social-de-uma-pessoa)
* [Vinculando uma imagem](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Nome-social#vinculando-uma-imagem-a-um-nome-social)
* [Removendo uma imagem](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Nome-social#removendo-o-v%C3%ADnculo-de-uma-imagem-de-um-nome)

### Data de nascimento

* [Obtendo a data de nascimento](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Data-de-nascimento#obtendo-a-data-de-nascimento)
* [Alterando a data de nascimento](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Data-de-nascimento#alterando-a-data-de-nascimento)
* [Vinculando uma imagem](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Data-de-nascimento#vinculando-uma-imagem-a-uma-data-de-nascimento)
* [Removendo uma imagem vinculada](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Data-de-nascimento#removendo-uma-imagem-vinculada)

### Data de óbito

* [Obtendo a data de óbito](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Data-de-%C3%B3bito#obtendo-a-data-de-%C3%B3bito)
* [Alterando a data de óbito](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Data-de-%C3%B3bito#alterando-a-data-de-%C3%B3bito)
* [Removendo uma data de óbito](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Data-de-%C3%B3bito#removendo-uma-data-de-%C3%B3bito)
* [Vinculando uma imagem](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Data-de-%C3%B3bito#vinculando-uma-imagem-a-uma-data-de-%C3%B3bito)
* [Removendo uma imagem vinculada](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Data-de-%C3%B3bito#removendo-uma-imagem-vinculada)


### Estado civil

* [Obtendo o estado civil](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Estado-civil#obtendo-o-estado-civil)
* [Alterando o estado civil](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Estado-civil#alterando-o-estado-civil)
* [Vinculando uma imagem](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Estado-civil#vinculando-uma-imagem-ao-estado-civil)
* [Removendo uma imagem vinculada](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Estado-civil#removendo-uma-imagem-vinculada)

### Escolaridade

* [Obtendo a escolaridade](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Escolaridade#obtendo-a-escolaridade)
* [Alterando a escolaridade](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Escolaridade#alterando-a-escolaridade)
* [Vinculando uma imagem](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Escolaridade#vinculando-uma-imagem-a-escolaridade)
* [Removendo uma imagem vinculada](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Escolaridade#removendo-uma-imagem-vinculada)

### Foto do perfil

* [Obtendo fotos do perfil](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Manipulando-a-foto-de-uma-pessoa-f%C3%ADsica#obtendo-fotos-de-uma-pessoa)
* [Inserindo uma foto para a pessoa](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Manipulando-a-foto-de-uma-pessoa-f%C3%ADsica#inserindo-uma-foto)
* [Alterando a foto](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Manipulando-a-foto-de-uma-pessoa-f%C3%ADsica#alterando-uma-foto)
* [Removendo a foto](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Manipulando-a-foto-de-uma-pessoa-f%C3%ADsica#removendo-uma-foto)

### Perfil

* [Inserindo uma pessoa](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Inserindo-uma-pessoa-f%C3%ADsica)
* [Obtendo o perfil de uma pessoa](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Obtendo-o-perfil-de-uma-pessoa-f%C3%ADsica)
* [Obter atualizações mais recentes](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Obter-atualiza%C3%A7%C3%B5es-mais-recentes-do-perfil)
* [Alterando o perfil de uma pessoa](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Alterando-o-perfil-de-uma-pessoa-f%C3%ADsica)

## Documentos

### Identidade

* [Obtendo a identidade](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Identidade#obtendo-a-identidade-de-uma-pessoa)
* [Inserindo a identidade](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Identidade#inserindo-uma-identidade)
* [Alterando a identidade](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Identidade#alterando-uma-identidade)
* [Vinculando uma imagem a uma identidade](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Identidade#vinculando-uma-imagem-a-uma-identidade)
* [Desvinculando uma imagem de uma identidade](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/Identidade#removendo-a-imagem-de-uma-identidade)

### CTPS

* Manipulando a CTPS

  * [Obtendo a lista de CTPS's](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/CTPS#obtendo-as-ctpss-de-uma-pessoa)
  * [Inserindo uma CTPS](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/CTPS#inserindo-uma-ctps)
  * [Alterando uma CTPS](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/CTPS#alterando-uma-ctps)
  * [Removendo uma CTPS](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/CTPS#removendo-uma-ctps)
  * [Vinculando uma imagem](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/CTPS#vinculando-uma-imagem-a-uma-ctps)
  * [Desvinculando uma imagem](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/CTPS#removendo-a-imagem-de-uma-ctps)

* Contratos de uma CTPS

  * [Obtendo os contratos](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/CTPS-Contratos#obtendo-os-contratos-de-uma-ctps)
  * [Inserindo um contrato](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/CTPS-Contratos#inserindo-um-contrato-para-uma-ctps)
  * [Alterando um contrato](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/CTPS-Contratos#alterando-um-contrato-de-uma-ctps)
  * [Removendo um contrato](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/CTPS-Contratos#removendo-um-contrato-de-uma-ctps)
  * [Vinculando uma imagem](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/CTPS-Contratos#vinculando-uma-imagem-a-um-contrato-de-uma-ctps)
  * [Desvinculando uma imagem](https://github.com/BRAConsultoria/SocialAPI-v2-Doc/wiki/CTPS-Contratos#removendo-a-imagem-de-um-contrato-de-uma-ctps)



