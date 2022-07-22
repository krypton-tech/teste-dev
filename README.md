# Teste desenvolvedor web

#### Introdução
- Criar um repositório aqui no github para entrega das tarefas abaixo.
- Apreciamos a entrega da tarefa em PHP, porém não é requisito. Você pode fazer na sua linguagem web.
- Você pode fazer utilizando ou não algum framework, fica a sua escolha.
- Não há necessidade de utilizar banco de dados.
- Para fazer a entrega, enviar o link do seu repositório para o email test-dev@kryptontech.com.br


#### Tarefa 1
Você deverá consumir o endpoint GET http://apiintranet.kryptonbpo.com.br/test-dev/exercise-1 da nossa API e construir a tela da listagem do carro com seu respectivo motor, a tela para inserir um novo carro com o seu motor e a exclusão do carro com o seu motor.

O retorno é um JSON com os dados de carros e de motores que está vinculado pelo motor_id, veja o exemplo baixo:

###### Carro
```
{
  "id":1,
  "marca":"chevrolet",
  "modelo":"prisma",
  "cor":"vermelho",
  "motor_id":7,
}
```

###### Motor
```
{
  "id":7,
  "posicionamento_cilindros":"linha",
  "cilindros":4,
  "litragem":1000,
  "observacao":null,
}
```
#### Tarefa 2
Criar uma API que será consultado utilizando method POST e que retorne em formato json os dados das atividades ordenado por hora.

O retorno deverá estar paginada e exibir até 5 registros por página e permitir ao desenvolvedor que for consumir a sua API escolher qual página ele irá exibir.

Link das atividades: https://github.com/krypton-tech/teste-dev/blob/main/atividades.json
