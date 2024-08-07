# H1-Como médico, eu quero realizar consultas remotas para ter atendimento eficiente sob as demandas.

## Critérios de aceitação:
__C1. O sistema deve enviar a notificação em até 24 horas antes da consulta.__

__C2. Confirmar que a notificação contém o nome do paciente, horário da consulta e motivo da visita.__

__C3. O sistema deve oferecer um sistema de chat particular entre o paciente.__

__C4. O sistema deve permitir que o médico possa reagendar as consultas remotas.__

__C5. A interface de visualização deve conter apenas informações importantes e objetivas para melhor entendimento, permitindo ao médico
filtrar consultas por horário, tipo de consulta e status (confirmada, pendente, cancelada e finalizada).__

__C6. Garantir que o sistema mantém um histórico de todas as remarcações para fins de auditoria e planejamento.__

## Regras de Negócios:
__R1. Todas as consultas agendadas devem ser confirmadas automaticamente por um sistema eletrônico de notificação, que enviará lembretes tanto para o médico quanto para o paciente. Isso garantirá uma comunicação eficaz e reduzirá a taxa de não comparecimento, conforme a Resolução CFM nº 1.821/2007, que regulamenta a comunicação entre médicos e pacientes.__

__R2. A notificação deve ser enviada com uma antecedência mínima de 24 horas antes da consulta, conforme as melhores práticas de preparação médica.__

__R3. A notificação deve ser enviada via e-mail para o médico.__

## Tela 1

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h01.png)



__- Descrição: Esta tela proporciona ao médico uma visão geral eficiente das consultas remotas agendadas, permitindo gerenciar e interagir com cada paciente de maneira conveniente e eficaz.__

__- Oferece acesso rápido a diferentes seções do sistema, como "Consultas", "Chat" e "Notificações". Permitindo ao médico mover-se facilmente entre as diferentes funcionalidades do sistema.__



# H2-Como atendente da UBS, eu desejo poder realizar atendimentos dos pacientes remotamente, para que os mesmos possam ser informados do dia e horário de sua consulta.

## Critérios de aceitação:
__C1. As consultas e agendamentos, assim como as as respostas às dúvidas dos pacientes só estarão disponíveis para os pacientes cadastrados e que integram a UBS.__

__C2. Os atendimentos ou consultas poderão ser realizadas por perfis de atendente ou médico, podendo ser simultâneo.__

__C3. As consultas, assim como as as respostas às dúvidas dos pacientes só ocorreram nos horários e dias de funcionamentos das UBS.__

## Regras de negócio:
__R1. Seguindo o regimento da Lei nº 8.080, de 19 de setembro 1990, o atendimento oferecido pela UBS deve ser disponibilizado para todos os pacientes em que fazem parte dela.__

__R2. O sistema deve disponibilizar a solicitação de agendamento informando ao paciente os dias e horários disponíveis para que o mesmo possa definir o melhor horário em que pode realizar a consulta.__

__R3. Em casos de consultas remotas o sistema deve permitir com que o atendente possa notificar para o paciente a data e horário definidos para a realização da consulta.__

__R4. O sistema deve permitir o usuário enviar mensagens no chat para o perfil da UBS informando sua dúvida em relação aos serviços prestados.__

__- Fluxograma:__

## Tela 2A

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h02a.png)



__- Descrição: Interface geral, permite à atendente mover-se pelas funcionalidades do sistema.__


## Tela 2B

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h02b.png)



__-Descrição: Acesso ao bate-papo com pacientes juntamente com as notificações, possibilita interação direta com o paciente.__



## Tela 2C

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h02c.png)



__- Descrição: Exemplo de interação com o sistema, revelando a opção "Visualizar", que por sua vez, abre a caixa de mensagem com paciente.__



## Tela 2D

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h02d.png)



__- Descrição: Exemplo prático de interação com paciente, onde interage com uma pergunta e uma atendente oferece suporte.__



# H3-Como uma Enfermeira da Comunidade, eu quero acessar rapidamente informações clínicas e protocolos relevantes para tomar decisões informadas durante o atendimento aos pacientes.

## Critérios de Aceitação:
__C1. Deve permitir o acesso à diagnósticos, exames dos pacientes para fazer o diagnóstico.__

__C2. A plataforma deve permitir buscas rápidas por termos clínicos, diagnósticos, tratamentos e protocolos.__

__C3. As informações clínicas e protocolos devem ser categorizados por áreas de especialização, tipos de doenças, sintomas e tratamentos.__

__C4. A plataforma deve suportar alguns tipos de arquivos incluindo textos, imagens.__

__C5. A enfermeira deve poder marcar informações e protocolos como favoritos para acesso rápido em consultas futuras.__

## Regras de Negócios:
__R1. A enfermeira deve ter acesso a um sistema de prontuário eletrônico integrado que permita a visualização rápida e fácil das informações clínicas dos pacientes durante o atendimento.__

__R2. Protocolos clínicos e diretrizes devem ser categorizados por especialidade e tipo de atendimento para facilitar a busca e consulta.__

__R3. A enfermeira deve ter acesso a uma base de dados centralizada contendo protocolos clínicos e diretrizes atualizadas para diferentes condições de saúde.__

__R4. O acesso a informações clínicas e protocolos deve ser protegido por medidas de segurança robustas para garantir a confidencialidade e integridade dos dados.__

__R5. Todas as decisões clínicas baseadas em protocolos e informações acessadas devem ser registradas no prontuário eletrônico do paciente para referência futura e auditoria.__

# H4-Como uma Enfermeira da Comunidade, eu quero registrar de forma eficiente as informações coletadas durante visitas domiciliares para manter um histórico completo e garantir a continuidade do cuidado.

## Critérios de Aceitação:
__C1. A plataforma deve permitir o registro de informações clínicas detalhadas, incluindo sintomas, diagnósticos, tratamentos administrados, e recomendações.__

__C2. A plataforma deve exibir o histórico completo de visitas e registros anteriores de cada paciente, permitindo uma visão holística do cuidado ao paciente.__

__C3. A plataforma deve ser otimizada para uso em campo, com capacidade de funcionar offline e sincronizar os dados automaticamente quando a conexão for restabelecida.__

__C4. A plataforma deve realizar backups automáticos regulares para evitar perda de dados.__

__C5. Deve haver um processo claro e eficiente para a recuperação de dados em caso de falha ou perda de dispositivo.__

__C6. As informações registradas durante as visitas domiciliares devem ser automaticamente atualizadas no prontuário eletrônico do paciente.__

## Regras de Negócio:
__R1. A enfermeira deve coletar informações detalhadas durante cada visita domiciliar, incluindo dados vitais, sintomas relatados, medicamentos em uso, e observações gerais.__

__R2. Dispositivos móveis devem estar configurados para funcionar offline, permitindo a entrada de dados mesmo em locais sem conexão à internet, com sincronização automática assim que a conexão for restabelecida.__

__R3. As informações coletadas devem seguir um formato estruturado e padronizado, garantindo a consistência e a facilidade de acesso e análise dos dados.__

__R4. O acesso ao sistema de prontuário eletrônico deve ser controlado por autenticação segura, e o dispositivo móvel deve ter medidas de proteção, como senhas e criptografia.__

__- Fluxograma H9 e H10:__

## Tela 3A

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h03a.png)



__- Descrição:  Interface geral, permite à enfermeira mover-se pelas funcionalidades do sistema.__



## Tela 3B

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h03b.png)



__- Descrição: Histórico de pacientes, acesso a dados clínicos juntamente com seus protocolos.__



## Tela 3C

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h03c.png)



__- Descrição: Exemplo de interação com a interface, revelando a opção "Visualizar", que por sua vez, revela os dados clínicos de pacientes.__



## Tela 4A

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h04a.png)



__- Descrição: Exemplo de retorno ao menu principal, possibilitando escolha de nova funcionalidade.__



## Tela 4B

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h04b.png)



__- Descrição: Ficha de cadastro de paciente vazia para dados clínicos, possibilitando agendamento de visitas.__



## Tela 4C

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h04c.png)



__- Descrição: Exemplo de possível preenchimento da ficha, contendo dados clínicos de pacientes, possibilitando o agendamento de visitas domiciliares, assim como o acesso ao estado dos pacientes.__



## Tela 4D

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h04d.png)



__- Descrição: Exemplo de salvamento de ficha de paciente, garantindo registro de dados.__



# H5-Como ACS eu quero registrar fichas de pacientes para requisitar visitas domiciliares para pacientes para que seja requisitada equipe qualificada.

## Critérios de aceitação:
__C1. deve ser registrado nome, endereço, idade, CPF e condição do paciente.__

__C2. visitas devem ser agendas para serem realizadas em no máximo uma semana.__

__C3. ao registrar deve-se incluir a equipe juntamente com a quantidade de membros.__

__C4. ao fim da visita deve-se registrar ou não, serviços adicionais como fisioterapia.__

## Regras de Negócio:
__R1. as visitas domiciliares devem ser agendadas para ocorrer dentro de um prazo máximo de uma semana a partir da data do registro da ficha do paciente.__

__R2. o sistema deve manter um histórico detalhado de todas as fichas de pacientes registradas, visitas realizadas e serviços adicionais prestados.__

__- Fluxograma:__

## Tela 5A

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h05a.png)



__- Descrição:  Interface geral, permite ao ACS mover-se pelas funcionalidades do sistema.__



## Tela 5B

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h05b.png)



__- Descrição: Interface que permite a visualização e registro de visitas domiciliares, juntamente com seus respectivos estados.__



## Tela 5C

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h05c.png)



__- Descrição: Exemplo de interação com o sistema revelando a opção "Visualizar Solicitação", que por sua vez, permite acesso ao requerimento de visita.__



## Tela 5D 

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h05d.png)



__- Descrição: Exemplo de  registro de solicitação de visita, oferece visualização dos dados dos pacientes, juntamente com suas condições de saúde e endereços.__



## Tela 5E

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h05e.png)



__- Descrição: Exemplo de confirmação de solicitação de visita, garante que os pacientes serão atendidos no tempo estipulado e também oferece opção de mensagem de confirmação ao paciente.__



# H6-Como técnico de enfermagem eu quero administrar medicamentos aos pacientes de acordo com prescrição médica para que o tratamento seja adequado.

## Critérios de aceitação:
__C1. as prescrições devem conter dosagem, horários de aplicações juntamente com as instruções de uso.__

__C2. medicamentos devem conter os dados do paciente associado juntamente com o médico que as prescreveu.__

__C3. os pacientes devem ser verificados antes da aplicação dos medicamentos.__

__C4. os medicamentos devem conter os possíveis efeitos colaterais que possam causar.__

__- Fluxograma:__

## Tela 6A

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h06a.png)



__- Descrição: Interface inicial para administração de medicamentos, possibilita aos enfermeiros entregar medicamentos aos pacientes de acordo com prescrição médica.__



## Tela 6B

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h06b.png)



__- Descrição: Acesso a lista de pacientes, para administração de medicação, oferece visualização da prescrição médica, juntamente com o estado de cada.__



## Tela 6C

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h06c.png)



__- Descrição: Exemplo de interação com o sistema revelando a opção "Verificar", que por sua vez, revela a prescrição médica de determinado paciente, possibilitando administração de medicamentos.__



## Tela 6D

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h06d.png)



__- Descrição: Exemplo de administração de medicamentos via prescrição médica, apresenta a medicação recomendada pelo médico juntamente com suas respectivas instruções e acesso a possíveis efeitos colaterais.__



## Tela 6E

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h06e.png)

__- Descrição: Exemplo de atualização de estatus, confirmando que as devidas medicações já foram administradas via prescrição médica.__



# H7-Como supervisor, gostaria de cadastrar a UBS em que ministro para fazer parte do portal.

## Critérios de Aceitação:
__C1. A UBS deve estar cadastrada no CNES, que é o registro oficial das unidades de saúde no Brasil.__

__C2. O sistema deve exibir um formulário de cadastro que permita ao supervisor inserir os seguintes dados da UBS: nome da UBS, endereço completo (incluindo cidade, estado e CEP), telefone de contato, e-mail, e nome do responsável.__

__C3. O formulário deve validar os campos obrigatórios e exibir mensagens de erro apropriadas se os dados não estiverem preenchidos corretamente.__

__C4. Após a aprovação do cadastro, o sistema deve exibir uma mensagem de confirmação na interface do portal e enviar um e-mail de confirmação ao supervisor.__

__C5. Somente usuários com permissões de supervisor devem ter acesso ao formulário de cadastro de UBS.__

## Regras de Negócio:
__R1. O sistema deve permitir que apenas supervisores autenticados possam cadastrar novas Unidades Básicas de Saúde (UBS) no portal.__

__R2. O cadastro da UBS deve incluir campos obrigatórios como nome da UBS, endereço completo e telefone de contato, garantindo que informações essenciais sejam fornecidas.__

__R3. O sistema deverá conter no máximo 2 perfis de supervisor.__

__- Fluxograma:__

## Tela 7A

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h07a.png)



__- Descrição: Interface inicial para registro de uma UBS, permite que os supervisores registrem as UBSs que ministram.__



## Tela 7B

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h07b.png)



__- Descrição: Exemplo de ficha vazia para cadastro de uma UBS.__



## Tela 7C

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h07c.png)



__- Descrição: Exemplo de interação com interface revelando a opção de acesso ao registro da UBS.__



## Tela 7D

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h07d.png)



__- Descrição: Exemplo de possível preenchimento de ficha para registro de UBS, juntamente com a confirmação de registro.__



## Tela 7E

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h07e.png)



__- Descrição: Exemplo de acesso ao segundo supervisor para registro de uma UBS.__



## Tela 7F

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h07f.png)



__- Descrição: Exemplo de interação com interface revelando a opção de acesso ao registro da UBS feita pelo segundo supervisor.__



## Tela 7G

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h07g.png)



__- Descrição: Exemplo de possível preenchimento de ficha para registro de UBS, juntamente com a confirmação de registro feita pelo segundo supervisor__



# H8-Como supervisor, gostaria de cadastrar os principais serviços que minha UBS oferece para manter os pacientes cientes de quais benefícios prestamos.

## Critérios de Aceitação:
__C1. O sistema deve exibir um formulário de cadastro que permita ao supervisor inserir os seguintes dados de cada serviço: nome do serviço, descrição detalhada, horários de atendimento, requisitos para acesso (se houver), e nome do responsável pelo serviço.__

__C2. O formulário deve validar os campos obrigatórios e exibir mensagens de erro como "Preencha os campos obrigatórios" e exibir tons avermelhados em campos onde os dados não estiverem preenchidos corretamente.__

__C3. O supervisor deve ter a capacidade de editar as informações dos serviços cadastrados, incluindo nome, descrição, horários e requisitos.__

__C4. Após a submissão, o sistema deve validar os dados e, em caso de sucesso, publicar os serviços no portal, tornando-os visíveis aos pacientes.
O supervisor deve receber uma notificação de confirmação por e-mail sobre a publicação dos serviços cadastrados.__

__- Fluxograma:__

## Tela 8A

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h08a.png)



__- Descrição: Interface geral, permite ao supervisor mover-se pelas funcionalidades do sistema.__



## Tela 8B

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h08b.png)



__- Descrição: Após cadastro de UBS, o supervisor pode cadastrar os serviços prestados pela mesma.__



## Tela 8C

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h08c.png)



__- Descrição: Exemplo de possível preenchimento de ficha de cadastro de serviço.__



## Tela 8D

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h08d.png)



__- Descrição: Exemplo de ficha preenchida e aprovada com a adição de um novo signo para edição da mesma.__



# H9-Como paciente gostaria de acessar minha caderneta de vacina digitalmente para visualizar meu histórico de vacinas rapidamente.

## Critérios de Aceitação:
__C1. O sistema deve garantir que apenas o paciente autenticado possa visualizar seu histórico de vacinas.__

__C2. Cada entrada no histórico deve incluir informações detalhadas sobre a vacina, como nome da vacina, data de administração, dose, local de aplicação, e nome do profissional de saúde responsável.__

__C3. O paciente deve ter a capacidade de filtrar e pesquisar seu histórico de vacinas por diferentes critérios, como nome da vacina, data de administração, ou tipo de vacina (por exemplo, vacina infantil, vacina de reforço).__

__C4. O paciente deve ter a opção de baixar e/ou imprimir sua caderneta de vacina digital em um formato PDF.__

## Tela 9

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h09.png)



__- Descrição: Exemplo de acesso a caderneta de paciente. Possibilitando paciente visualizar seu histórico de vacinas digitalmente, juntamente com os dados de cada uma, e ainda possibilidade de download da mesma, garantindo acessibilidade.__



# H10-Como paciente, gostaria de receber lembretes de doação de sangue para que eu possa ficar ciente de quando doar sangue.

## Critérios de Aceitação:
__C1. O paciente deve ter a opção para receber lembretes de doação de sangue, podendo escolher a frequência dos lembretes (por exemplo, a cada 3 meses, 6 meses, ou 12 meses).__

__C2. O sistema deve permitir que o paciente escolha o método de recebimento dos lembretes (por exemplo, e-mail, SMS, ou notificações push).
Os lembretes enviados ao paciente devem conter informações relevantes, como a data sugerida para a próxima doação, os benefícios de doar sangue, e instruções sobre como e onde doar.__

__C3. Os lembretes devem ser enviados de acordo com a última data de doação do paciente e as diretrizes de intervalo mínimo entre doações (por exemplo, a cada 3 meses para homens e a cada 4 meses para mulheres, conforme as regulamentações locais).__

## Tela 10

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h10.png)



__- Descrição: interface para doação de sangue, onde possibilita pacientes se voluntariarem como doadores e ainda serem notificados de possíveis doações.__



# H11-Como paciente, gostaria de acessar as informações e serviços dos quais a UBS oferece para que eu possa estar informado das características daquele estabelecimento.

## Critérios de Aceitação:
__C1. O paciente deve poder acessar a página "Mais UBSs" no portal, que contenha informações detalhadas sobre a unidade, incluindo endereço completo, horário de funcionamento, telefone de contato e e-mail.__

__C2. A página da UBS deve exibir uma lista completa dos serviços oferecidos pela unidade, como consultas médicas, exames laboratoriais, campanhas de vacinação, programas de saúde preventiva, entre outros.__

__C3. As informações sobre a UBS e os serviços oferecidos devem ser mantidas atualizadas pelo supervisor daquele estabelecimento, com um processo definido para revisão e atualização periódica.__

__C4. Cada serviço listado deve incluir uma breve descrição, horários de atendimento, requisitos para acesso (se houver), e qualquer informação adicional relevante (como nome dos profissionais responsáveis).__

## Tela 11A

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h11a.png)



__- Descrição: Interface geral, permite ao paciente mover-se pelas funcionalidades do portal.__



## Tela 11B 

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h11b.png)



__- Descrição: Exemplo de interação com a interface do portal, revelando os serviços prestados por determinada UBS.__



## Tela 11C 

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h11c.png)



__- Descrição: Avanço na interface do portal, para a opção "Enfermagem", releva os serviços relacionados à enfermagem prestados pela UBS.__



## Tela 11D

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h11d.png)



__- Descrição: Exemplo de interação com o portal sem ter login prévio, resultando em erro de Acesso Restrito.__



## Tela 11E

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h11e.png)



__- Descrição: Exemplo de interação com o portal com login prévio revelando a opção "Realizar Agendamento", que por sua vez, possibilita o paciente agendar uma consulta em determinda UBS.__



## Tela 11F

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h11f.png)



__- Descrição: Exemplo de interação com o portal, onde revela a mensagem "Consulta Agendada", comunicando que a consulta já está efetivamente marcada.__



# H12-Como paciente, gostaria de cadastrar meus dados no portal para estar conectado ao sistema.

## Critérios de Aceitação:
__C1. O portal deve exibir um formulário de cadastro que permita ao paciente inserir os seguintes dados: nome completo, número do SUS, data de nascimento, endereço, telefone de contato, e-mail, CPF (ou documento de identificação equivalente), e senha.__

__C2. Após o preenchimento do formulário, o sistema deve enviar um e-mail ou SMS de confirmação para o endereço/telefone fornecido pelo paciente. No e-mail, o paciente deve clicar em um link de verificação para confirmar sua inscrição e ativar sua conta no portal.__

__C3. O sistema deve garantir que todos os dados pessoais do paciente sejam armazenados de forma segura, utilizando criptografia da comunicação de rede e restrição do intervalo de endereços IPs autorizados para acessar.__

__C4. O portal deve estar em conformidade com as regulamentações de proteção de dados (como a LGPD no Brasil) e informar ao paciente sobre a política de privacidade e os termos de uso durante o processo de cadastro.__

__C5. Após a confirmação do cadastro, o paciente deve poder fazer login no portal utilizando seu número do SUS e senha.__

__- Fluxograma:__

## Tela 12A

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h12a.png)



__- Descrição: Interface geral de cadastro, permite ao paciente mover-se pelas funcionalidades de cadastro do portal.__



## Tela 12B

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h12b.png)



__- Descrição: Exemplo de tela de cadastro do portal, o mesmo estipula os passos a serem realizados para formulação do cadastro.__



## Tela 12C

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h12c.png)



__- Descrição: Exemplo de login bem-sucedido, apresentando a interface geral do portal.__



## Tela 12D

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h12d.png)



__- Descrição: Exemplo de ficha de cadastro de dados no sistema, estipula os dados necessários a serem preenchidos para concluir cadastro.__



## Tela 12E

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h12e.png)



__- Descrição: Exemplo de possível preenchimento da ficha de cadastro, juntamente com o botão de Finalizar Cadastro.__



## Tela 12F

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h12f.png)



__- Descrição: Exemplo de conclusão de cadastro, a confirmação do mesmo foi enviado para o e-mail do paciente.__



# H13-Como paciente, gostaria de desconectar minha conta do portal para sair do sistema.

## Critérios de Aceitação:
__C1. O botão de logout deve ser facilmente identificável, com um ícone e/ou texto descritivo (por exemplo, "Sair" ou "Logout").__

__C2. A mensagem deve solicitar a confirmação do paciente para sair do sistema e oferecer a opção de cancelar ou confirmar a ação.__

__C3. O paciente deve ser redirecionado para a página inicial do portal ou uma página de login após a desconexão, com uma mensagem de confirmação de que saiu do sistema com sucesso.__

__C4. O sistema deve garantir que todos os dados temporários da sessão do paciente sejam limpos após o logout, incluindo cookies, caches, e qualquer informação sensível armazenada temporariamente no navegador.__

## Regras de Negócio:
__R1. O sistema deve permitir que pacientes autenticados possam desconectar suas contas a qualquer momento, garantindo que a ação seja repentina.__

__R2. Ao desconectar a conta, apenas a sessão ativa do portal devem ser encerrada imediatamente para proteger a segurança e privacidade dos dados.__

__- Fluxograma:__

## Tela 13A

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h13a.png)



__- Descrição: Interface geral do portal para gerenciamento de perfil, permite ao paciente mover-se pelas funcionalidades de perfil do portal.__



## Tela 13B

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h13b.png)



__- Descrição: Exemplo de mensagem exibida após a seleção de logout de conta, garantindo acessibilidade aos usuários.__



# H14-Como paciente, gostaria de alterar meu perfil para atualizar algum dado antigo.

## Critérios de Aceitação:
__C1. O paciente deve poder acessar uma página dedicada à edição de perfil a partir do portal, que pode ser acessada através de um link ou botão visível e claramente identificado, como "Editar Perfil".__

__C2. O sistema deve permitir que o paciente edite campos específicos de seu perfil, como nome, endereço, telefone de contato, e-mail, data de nascimento, e qualquer outro dado pessoal relevante.__

__C3. O sistema deve garantir que somente o paciente autenticado possa acessar e editar seu próprio perfil, protegendo os dados contra acesso não autorizado.__

## Tela 14

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h14.png)



__- Descrição: Interface para alteração de dados, dados antigos poderão ser alterados por novos, garantindo usabilidade.__



# H15-Como paciente, gostaria de selecionar a ubs mais perto da minha residência onde queira realizar os serviços Para facilitar a seleção da UBS mais próxima.

## Critérios de aceitação:
__C1. As informações sobre as UBSs incluem endereço, telefone e especialidades disponíveis.__

__C2. O sistema possui uma funcionalidade de localização que sugere a UBS mais próxima da residência do paciente com base na sua localização.__

__C3. O paciente pode filtrar a busca por UBSs com base em especialidades e serviços oferecidos.__

__C4. O sistema permite ao paciente visualizar a distância aproximada e o tempo estimado de deslocamento para cada
UBS.__

## Regras de negocio:
__R1. O sistema vai está sempre atualizando as informações das ubs, incluindo telefone, endereço, e isso deve garanti que o paciente encontre uma ubs mais rápida.__

__- Fluxograma:__

## Tela 15A

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h15a.png)



__- Descrição: Interface geral de procura do portal, permite ao paciente localizar a unidade mais próxima a sua casa.__



## Tela 15B

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h15b.png)



__- Descrição: Exemplo de interação com a interface de busca de UBSs, releva a seleção de bairros ao paciente, garantindo busca eficiente.__



## Tela 15C

![](https://github.com/JoaoCarlos22/TP-UBServices/blob/main/docs/rastreabilidade_requisitos/images/tela_h15c.png)



__- Descrição: Exemplo de resultados da busca de acordo com o bairro especificado, além de ter opção de alteração de região, garantindo mais eficiência na busca por UBSs.__
