# Global Solution - DSA

## Sobre a Atividade

Esta atividade foi desenvolvida para a Global Solution da disciplina de DSA, com o objetivo de simular o monitoramento básico de uma missão espacial.

---

## Funcionalidades

- Inserção de dados da missão:
  - Temperatura
  - Energia
  - Comunicação

- Visualização do status atual da nave

- Análise automática das condições da missão

- Histórico das leituras cadastradas

---

## Regras de Análise

| Condição | Resultado |
|-----------|-----------|
| Temperatura > 80 | Alerta de superaquecimento |
| Energia < 20 | Economia de energia ativada |
| Comunicação = 0 | Falha de comunicação |

Caso nenhuma das condições acima seja identificada, o sistema informa que a missão está funcionando normalmente.

---

## Explicação da Lógica Utilizada

Iniciamos o funcionamento do sistema permitindo que o usuário informe os valores de temperatura, energia e comunicação da nave. Antes de salvar os dados, utilizamos uma verificação para garantir que todos os campos foram preenchidos corretamente. Caso algum campo esteja vazio, exibimos uma mensagem solicitando o preenchimento das informações.

Após essa validação, armazenamos os dados em um histórico de leituras. Dessa forma, conseguimos manter todas as informações cadastradas anteriormente para futuras consultas.

Também criamos uma função de visualização de status, responsável por exibir os dados da última leitura cadastrada. Nessa etapa, realizamos uma verificação da comunicação da nave para informar se ela está funcionando normalmente ou se existe alguma falha.

Na parte de análise, utilizamos estruturas condicionais para verificar possíveis situações de risco na missão. As verificações realizadas foram:

- Temperatura acima de 80;
- Energia abaixo de 20;
- Comunicação igual a 0.

Quando alguma dessas condições é atendida, exibimos os alertas correspondentes para o usuário. Caso nenhuma situação de risco seja encontrada, o sistema informa que a missão está funcionando normalmente.

Também adicionamos uma função de histórico de leituras, permitindo visualizar todas as informações cadastradas anteriormente. Para isso, utilizamos uma estrutura de repetição para percorrer todos os dados armazenados e exibi-los na tela.

---

## Demonstração

Coloacamos um vídeo no repositório com a simulação do programa. Além disso, também incluímos o fluxograma desenhado para a GS.

---

## 👨‍💻 Integrantes

- Leonardo Gabriel Sá Duarte - RM 569029
- Enzo Vieira de Nadai - RM 569985
