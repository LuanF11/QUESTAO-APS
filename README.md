# QUESTAO-APS

## Questão 1
**Resposta:** O professor, ao visualizar a solicitação pronta, decide verificar o histórico de suas solicitações. O sistema, então, realiza as seguintes etapas para realizar a busca e apresentar o histórico de solicitações para o professor:

1. **Passo 1:** O professor fornece ao sistema as informações necessárias para a busca, ou apenas inicializa a busca sem ser preciso inserir especificações.
2. **Passo 2:** O sistema usa as informações fornecidas pelo professor para consultar o banco de dados.
3. **Passo 3:** O sistema recupera os registros das solicitações do professor do banco de dados.
4. **Passo 4:** O sistema apresenta os registros das solicitações do professor para o professor.

## Questão 2
**Resposta:** Implementar um mecanismo de cache, o sistema busca os dados das solicitações no banco de dados toda vez que um usuário solicita uma visualização ou um histórico. Isso pode ser ineficiente, especialmente para solicitações que são visualizadas ou consultadas com frequência. Essa melhoria tornaria o sistema mais eficiente para solicitações que são visualizadas ou consultadas com frequência. Isso seria útil para tarefas como verificar o status de uma solicitação ou visualizar o histórico de solicitações.

## Questão 3
**Resposta:** 
1. **Passo 1:** O coordenador de curso acessa o sistema e seleciona a solicitação que deseja analisar.
2. **Passo 2:** O coordenador de curso analisa os dados da solicitação e verifica se ela atende aos requisitos.
3. **Passo 3:** Se a solicitação atende aos requisitos, o coordenador de curso aprova a solicitação.
4. **Passo 4:** O sistema atualiza o status da solicitação para "Aprovado" no banco de dados.

*Interações:*
- **Passo 5:** O sistema envia uma notificação ao professor informando que a solicitação foi aprovada.

*Interações:*
- O coordenador de curso interage com o sistema para acessar a solicitação, analisar os dados e aprovar a solicitação.
- O sistema interage com o professor para enviar uma notificação sobre a aprovação da solicitação.

## Questão 4
**Resposta:** A validação do documento é necessária para garantir que o documento esteja em um formato válido e que contenha todas as informações necessárias. Isso é importante para o funcionamento adequado do sistema, pois garante que as cópias sejam produzidas corretamente. Ao realizar a validação dentro do componente documento, o sistema pode garantir que o documento esteja válido antes de ser enviado para a etapa de cópia. Isso ajuda a evitar erros e retrabalho, e melhora a qualidade das cópias produzidas.

## Questão 5
**Resposta:** 
O professor é o componente principal, que inicia o processo de solicitação de cópias. Ele interage com o sistema para criar uma solicitação, que é então enviada para a coordenação do curso para análise. A coordenação de curso pode aprovar ou rejeitar a solicitação, e suas decisões são enviadas para o sistema, que então atualiza o status da solicitação no banco de dados.

A reprografia é o componente responsável por produzir as cópias. Ela recebe as solicitações aprovadas do sistema e as processa de acordo com as instruções da solicitação. As cópias produzidas e notificam o professor.

O banco de dados é o componente responsável por armazenar os dados das solicitações. Ele é usado por todos os outros componentes para acessar e modificar as informações das solicitações.

A comunicação entre esses componentes é essencial para o funcionamento adequado do sistema.

*Entre professor e sistema:* O professor pode fornecer mais informações sobre as solicitações usando um formulário de solicitação mais completo. Isso pode ajudar a coordenação de curso a tomar decisões mais informadas sobre as solicitações.

*Entre reprografia e sistema:* A reprografia pode informar ao sistema sobre o andamento das solicitações usando um sistema de status. Isso pode ajudar o professor a acompanhar o status de suas solicitações após chegar na reprografia.
