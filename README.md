"# ProjetoVia-CEP" 

### Features

[X] Executar métodos GET, POST, PUT, DELETE

[X] Validar JSON schema

### Ferramentas/Tecnologias utilizadas

[Postman](https://www.postman.com/)

[Newman](https://www.npmjs.com/package/newman)

[JavaScript](https://www.javascript.com//)

### Execução Local
Abra o terminal e vá até o diretório, em seguifa execute o seguinte comando:
```bash
C:\ProjetoViaCep> newman run Collection/APIViaCep.postman_collection.json -e Environment/ViaCep-Prod.postman_environment.json -r htmlextra
```