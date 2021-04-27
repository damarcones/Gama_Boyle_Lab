# <center>ESPECIFICAÇÃO DE CASOS DE USO

### Histórico de versão<br>

|Data | Versão | Descrição | Autor(es)|
| -- | -- | -- | -- |
| 24.04.2021 | 0.1 | Criação do documento |Rodrigo Oliveira|

### Participantes

* Rodrigo Oliveira

<br><br>

## UC01: Cadastrar Aluno

**Descrição:** Este caso de uso permite ao aluno se cadastrar na plataforma.

**Ator principal:** Aluno

**Pré condições:** O aluno deve estar desconectado de uma conta antes de iniciar o cadastro.

**Fluxo principal:** Este caso de uso é iniciado quando o usuário escolhe a opção de cadastrar uma nova conta.

1. O sistema redireciona o usuário para a tela de cadastro.
2. O usuário preenche os campos com as informações necessárias para realizar o cadastro.
3. O usuário confirma a realização do castro.
4. O sistema valida os dados informados pelo usuário.
5. O sistema exibe uma mensagem de cadastro efetuado com sucesso.
6. O usuário é redirecionado para a tela de *log in*.
7. O caso de uso é encerrado.

<br>

## UC02: Autenticar usuários

**Descrição:** Este caso de uso permite aos usuários se autenticarem na plataforma.

**Ator principal:** Aluno, Professor, Técnico

**Pré condições:** O usuário deve estar desconectado de uma conta antes de iniciar a autenticação.

**Fluxo principal:** Este caso de uso é iniciado quando o usuário escolhe a opção de entrar em uma conta.

1. O sistema redireciona o usuário para a tela de autenticação.
2. O usuário preenche os campos com as informações necessárias para realizar a autenticação.
3. O usuário confirma a realização de autenticação.
4. O sistema valida os dados informados pelo usuário.
5. O usuário é redirecionado para a tela principal do sistema.
6. O caso de uso é encerrado.

<br>

## UC03: Cadastrar Professor

**Descrição:** Este caso de uso permite aos técnicos cadastrarem um professor.

**Ator principal:** Técnico

**Pré condições:** O usuário deve estar autenticado em uma conta antes de iniciar o cadastro.

**Fluxo principal:** Este caso de uso é iniciado quando o usuário escolhe a opção cadastrar um novo professor.

1. O sistema redireciona o técnico para a tela de cadastro de professor.
2. O técnico preenche os campos com as informações necessárias para realizar o cadastro.
3. O técnico confirma a realização do cadastro.
4. O sistema valida os dados informados pelo técnico.
5. O sistema exibe uma mensagem de cadastro efetuado com sucesso.
6. O usuário é redirecionado para a tela principal do sistema.
7. O caso de uso é encerrado.

<br>

## UC04: Desconectar usuários

**Descrição:** Este caso de uso permite aos usuários se desconectarem da conta.

**Ator principal:** Aluno, Professor, Técnico

**Pré condições:** O usuário deve estar autenticado em uma conta antes de se desconectar.

**Fluxo principal:** Este caso de uso é iniciado quando o usuário escolhe a opção desconectar.

1. O sistema informa ao usuário se realmente deseja se desconectar.
2. O usuário confirma.
3. O usuário é redirecionado para a tela de autenticação.
4. O caso de uso é encerrado.

<br>

## UC05: Visualizar experimento

**Descrição:** Este caso de uso permite ao aluno visualizar a imagem da webcam que está monitorando um de seus experimentos que está ocorrendo.

**Ator principal:** Aluno

**Pré condições:** O aluno deve estar autenticado em uma conta antes de visualizar o experimento; o aluno deve começar um experimento; o professor deve ter começado a aula de experimentos.

**Fluxo principal:** Este caso de uso é iniciado quando o aluno escolhe a opção começar experimento.

1. O sistema redireciona o aluno para a tela de experimento.
2. Na tela de experimento, o sistema exibe a imagem da webcam transmitida.
3. O caso de uso é encerrado.

<br>

## UC06: Visualizar todos os experimentos

**Descrição:** Este caso de uso permite ao professor visualizar as imagens das câmeras que estão monitorando todos os experimentos que estão acontecendo.

**Ator principal:** Professor

**Pré condições:** O professor deve estar autenticado em uma conta antes de visualizar os experimentos.

**Fluxo principal:** Este caso de uso é iniciado quando o professor escolhe a opção mostrar todos os experimentos.

1. O sistema redireciona o professor para a tela de experimentos.
2. Na tela de experimentos, o sistema exibe as imagens das câmeras transmitidas, de todos os experimentos que estão acontecendo no momento.
3. O caso de uso é encerrado.

<br>

## UC07: Iniciar aula de experimentos

**Descrição:** Este caso de uso permite ao professor iniciar uma aula de experimentos.

**Ator principal:** Professor

**Pré condições:** O professor deve estar autenticado em uma conta antes de iniciar uma aula.

**Fluxo principal:** Este caso de uso é iniciado quando o professor escolhe a opção começar aula.

1. O sistema informa ao professor se realmente deseja iniciar a aula.
2. O professor confirma.
3. O sistema redireciona o professor para a tela de de experimentos.
4. O caso de uso é encerrado.

<br>

## UC08: Encerrar aula de experimentos

**Descrição:** Este caso de uso permite ao professor encerrar uma aula de experimentos.

**Ator principal:** Professor

**Pré condições:** O professor deve estar autenticado em uma conta antes de encerrar uma aula; o professor deve ter iniciado uma aula antes de encerrar esta aula.

**Fluxo principal:** Este caso de uso é iniciado quando o professor escolhe a opção encerrar aula.

1. O sistema informa ao professor se realmente deseja encerrar a aula.
2. O professor confirma.
3. O sistema exibe uma mensagem de sucesso.
4. O sistema redireciona o professor para a tela inicial.
5. O caso de uso é encerrado.

<br>

## UC09: Visualizar a lista de alunos

**Descrição:** Este caso de uso permite ao professor ou técnico visualizar a lista de alunos.

**Ator principal:** Professor, Técnico

**Pré condições:** O professor ou técnico deve estar autenticado em uma conta antes de visualizar a lista de alunos.

**Fluxo principal:** Este caso de uso é iniciado quando o professor ou técnico escolhe a opção mostrar alunos.

1. O sistema redireciona o professor ou técnico para a tela de alunos.
2. O sistema exibe todos o alunos cadastrados.
3. O caso de uso é encerrado.

<br>

## UC10: Pausar experimento

**Descrição:** Este caso de uso permite ao professor pausar um experimento que está ocorrendo.

**Ator principal:** Professor

**Pré condições:** O professor deve estar autenticado em uma conta antes de pausar um experimento; o experimento a ser pausado deve ter sido iniciado.

**Fluxo principal:** Este caso de uso é iniciado quando o professor escolhe um experimento da tela de experimento e escolhe a opção pausar.

1. O sistema informa se o professor deseja realmente pausar o experimento.
2. O professor confirma.
3. O sistema exibe uma mensagem de sucesso.
4. O sistema bloqueia a interação do aluno com o experimento.
5. O caso de uso é encerrado.

<br>

## UC11: Retomar experimento

**Descrição:** Este caso de uso permite ao professor retomar um experimento que foi pausado.

**Ator principal:** Professor

**Pré condições:** O professor deve estar autenticado em uma conta antes de retomar um experimento; o experimento a ser retomado deve ter sido pausado.

**Fluxo principal:** Este caso de uso é iniciado quando o professor escolhe um experimento, que está pausado, da tela de experimento e escolhe a opção retomar.

1. O sistema informa se o professor deseja realmente retomar o experimento.
2. O professor confirma.
3. O sistema exibe uma mensagem de sucesso.
4. O sistema desbloqueia a interação do aluno com o experimento.
5. O caso de uso é encerrado.

<br>

## UC12: Responder dúvida

**Descrição:** Este caso de uso permite ao professor responder uma dúvida cadastrada.

**Ator principal:** Professor

**Pré condições:** O professor deve estar autenticado em uma conta antes de responder uma dúvida; a dúvida a ser respondida deve ter sido previamente cadastrada.

**Fluxo principal:** Este caso de uso é iniciado quando o professor escolhe uma dúvida da tela de dúvidas.

1. O sistema exibe a pergunta.
2. O sistema exibe um campo de resposta.
3. O professor escreve no campo de resposta.
4. O professor confirma o envio.
5. O sistema exibe uma mensagem de sucesso.
6. O sistema notifica o autor da dúvida.
7. O caso de uso é encerrado.

<br>

## UC13: Cadastrar dúvida

**Descrição:** Este caso de uso permite ao aluno cadastrar uma dúvida.

**Ator principal:** Aluno

**Pré condições:** O Aluno deve estar autenticado em uma conta antes de cadastrar uma dúvida.

**Fluxo principal:** Este caso de uso é iniciado quando o aluno escolhe a opção cadastrar dúvida.

1. O sistema redireciona o aluno para a tela de dúvidas.
2. O sistema exibe um campo para o título e outro para descrição.
3. O aluno preenche as informações.
4. O aluno confirma o cadastro.
5. O sistema exibe uma mensagem de sucesso.
6. O sistema notifica o professor.
7. O caso de uso é encerrado.

<br>

## UC14: Controlar equipamento experimental

**Descrição:** Este caso de uso permite ao aluno controlar o equipamento do experimento.

**Ator principal:** Aluno

**Pré condições:** O Aluno deve estar autenticado em uma conta antes de cadastrar uma dúvida; o aluno deve ter iniciado um experimento.

**Fluxo principal:** Este caso de uso é iniciado quando o aluno escolhe algumas opções de controle no experimento.

1. O aluno escolhe uma ação para executar.
2. O sistema informa ao aluno se realmente deseja efetuar a ação escolhida.
3. O aluno confirma.
4. O sistema exibe uma mensagem informando a ação que está sendo executada.
5. O sistema  redireciona a ação para o equipamento.
6. O caso de uso é encerrado.

<br>

## UC15: Concluir experimento

**Descrição:** Este caso de uso permite ao aluno concluir um experimento.

**Ator principal:** Aluno

**Pré condições:** O Aluno deve estar autenticado em uma conta antes de concluir um experimento; o aluno deve ter iniciado um experimento.

**Fluxo principal:** Este caso de uso é iniciado quando o aluno escolhe a opção concluir experimento.

1. O sistema informa ao aluno se realmente deseja concluir o experimento.
2. O aluno confirma.
3. O sistema exibe uma mensagem informando a ação que o experimento foi concluído.
4. O sistema redireciona o aluno para a tela inicial.
5. O caso de uso é encerrado.

<br>

## UC16: Solicitar auxílio do técnico

**Descrição:** Este caso de uso permite ao aluno solicitar o auxílio de um técnico.

**Ator principal:** Aluno

**Pré condições:** O Aluno deve estar autenticado em uma conta antes de solicitar auxílio; o aluno deve ter iniciado um experimento.

**Fluxo principal:** Este caso de uso é iniciado quando o aluno escolhe a opção falar com técnico.

1. O sistema redireciona o aluno para a tela de bate papo com o técnico.
2. O sistema notifica o técnico.
3. O caso de uso é encerrado.

<br>

## UC17: Regular equipamento

**Descrição:** Este caso de uso permite ao técnico regular o equipamento do experimento.

**Ator principal:** Técnico

**Pré condições:** O Técnico deve estar autenticado em uma conta antes de regular um equipamento.

**Fluxo principal:** Este caso de uso é iniciado quando o Técnico escolhe a opção regular equipamento.

1. O sistema redireciona o técnico para a tela de equipamentos.
2. O técnico seleciona um dos equipamentos.
3. O sistema redireciona o técnico para a tela do equipamento.
4. O sistema exibe as possibilidades de regulagem.
5. O técnico seleciona quais ele deseja efetuar.
6. O sistema informa se o técnico realmente deseja realizar a regulagem.
7. O técnico confirma.
8. O sistema exibe uma mensagem de sucesso.
9. O sistema começa a rotina de regulagem com os parâmetros informados pelo técnico.
10. O caso de uso é encerrado.

<br>

## UC18: Responder solicitação

**Descrição:** Este caso de uso permite ao técnico responder uma solicitação de auxílio feita por algum aluno.

**Ator principal:** Técnico

**Pré condições:** O Técnico deve estar autenticado em uma conta antes de responder uma solicitação; um aluno deve ter solicitado auxílio.

**Fluxo principal:** Este caso de uso é iniciado quando o Técnico escolhe a opção responder solicitações.

1. O sistema redireciona o técnico para a tela de solicitações.
2. O técnico seleciona uma das solicitações.
3. O sistema redireciona o técnico para a tela de bate papo com o autor da solicitação.
4. O caso de uso é encerrado.

<br>

## UC19: Pausa de emergência

**Descrição:** Este caso de uso permite ao técnico pausar um experimento em caso de emergência.

**Ator principal:** Técnico

**Pré condições:** O Técnico deve estar autenticado em uma conta antes de pausar um experimento; um experimento deve sido iniciado.

**Fluxo principal:** Este caso de uso é iniciado quando o Técnico escolhe a opção parada de emergência na tela do experimento.

1. O sistema bloqueia as ações do aluno.
2. O sistema notifica o aluno que o experimento teve uma parada de emergência.
3. O caso de uso é encerrado.
