# Youpay - Entrevista
Vaga: **Desenvolvedor Node.js**

Este repositório contém os arquivos necessários para realizar a entrevista com live coding.

## Desafio
1. Crie uma REST API em Node.js que atenda os endpoints da tabela abaixo;
1. A API deve ser capaz de cumprir as etapas básicas do CRUD e retornar os HTTP responde codes corretamente;
1. Utilize Docker;
1. Utilize um banco de dados de sua preferência;

### Endpoints
| Método | Rota |
| -------|-------|
| GET    | /tasks      |
| GET    | /tasks/{id} |
| POST   | /tasks      |
| PUT    | /tasks/{id} |
| DELETE | /tasks/{id} |

### Observações
- Para ajudar, colocamos na pasta `postman` os jsons da collection e do environment;
- O environment está apontando para a seguinte rota: `https://localhost:8000`;
- Você pode pesquisar na internet, caso necessário;
- Você também pode utilizar uma biblioteca de sua preferência;

### Exemplo de Model: Task

| Atributo    | Tipo    |
| ------------|---------|
| id          | integer |
| description | string  |
| done        | boolean |
| creator_id  | integer |
| created_at  | datetime|


### Boa sorte!

