# OCIArchitectProfessional
Preparatório para o exame Oracle Cloud Infrastructure Architect Professional

- Este é um Guia de estudo para o exame da Oracle para a certificação OCI Architect Professional

- Isto não é Dump de prova, é um guia de estudo com alguns cenários, questões parecidas e dos exemplos das aulas que eu fiz a tradução. Creio que possa ser útil como complemento aos estudos para a certificação. Portanto, isso não substitui as aulas do curso oficial, deve ser usado como complemento de estudos.

# Dicas de Preparação do exame

- Preste muita atenção as questões, pois há algumas questões que são para não confirmação de funcionalidades, ou quais recursos não atendem determinado objetivo.
- Observe as palavras chave nas questões, quando elas falam sobre determinados recursos ou tecnologias, ferramentas e características de funcionalidades, elas podem ajudar a eliminar respostas que não são as corretas, facilitando a tomada de decisões para responder corretamente.
- Você pode encontrar 2 respostas que soam exatamente iguais, e que podem ser decididas pelas palavras chave.
- Observe muito a quantidade de respostas que são exigidas, algumas são com 1 resposta, outras 2 respostas e algumas com 3 respostas corretas.
- Não fique preso a uma questão somente, marque como revisão se tiver dúvidas e avance, depois no final volte para pensar mais sobre as questões marcadas como revisão.
- Nunca deixe de responder, mesmo que chutando se não souber, antes uma tentativa que pode ter 50% de chance ao invés de 100% de erro.
- Procure sempre restringir o cenário para 1 ou 2 respostas.


# Exemplo de uma pergunta do exame


Um cliente quer implemtnar um service de sergurança global que protege aplicações de atividades maliciosas e tráfego não desejado da internet de Cross Site Script e SQL Injections.

Qual das seguintes soluções podem ser usadas para esta situação?

- <b><i> A: OCI Web Application Firewall </i></b>
- B: OCI DNS Service
- C: OCI Load Balancer
- D: OCI DNS Service com OCI Load Balance Service


# -----------


# Algumas questões para estudo com a resposta correta.

1 - Um cliente quer implemtnar um service de sergurança global que protege aplicações de atividades maliciosas e tráfego não desejado da internet de Cross Site Script e SQL Injections.

Qual das seguintes soluções podem ser usadas para esta situação?

- OCI Web Application Firewall.


2 - Uma organização de mídia global está trabalhando em um projeto que permite que os usuários façam upload de vídeos para o site. Depois do upload completo, o vídeo deve ser automaticamente processado por um algoritmo de IA. O algoritmo deverá tentar reconhecer certas ações nos vídeos em que podem ser usados para mostrar publicidades relacionadas no futurno. O time de desenvolvimento quer focar em escrever o código de IA e não quer se preocupar com a infraestrutura subjacente em alta-disponibilidade, escalabilidade, segurança e monitoramento.

Quais serviçoes do OCI devem ser recomendados para este projeto?

- Utilize Object Storage para armazenar os vídeos, OCI Events services e OCI Functions.
- (Use Object Storage to storing videos, OCI Events services and OCI Functions).


3 - Um cliente está em processo de mudar seu aplicativo baseado em web de vendas de seu próprio Data Center localizado no US West para a região OCI India West (Mumbai). Eles querem fazer de uma maneira controlada e inicialmente só 1% do tráfego deverá ser direcionado (steered) para os servidores no OCI. Depois de verificar que tudo está funcionando como o esperado, a companhia está planejando gradualmente aumentar a taxa até que estejam confortáveis com a total migração de todo o tráfego para o OCI.

Quais das seguintes soluções podem ser usadas nesta situação?

- OCI DNS e Gerenciamento de Tráfego com política de Direção de Load Balancer.
- (OCI DNS and Traffic Management with Load Balancer Steering policy).


4 - Um cliente dos Estados Unidos quer parar um vazamento de previdência social e parar uploads de executáveis via formulários de entrada.

Quais das seguintes soluções podem ser usadas nesta situação?

- Web Application Firewall com regras de proteção.
- (Web Application Firewall with protection rules).


5 - Um arquiteto de soluções do OCI está trabalhando em uma solução que consiste na carga de dados e análise de dados de triagens clínicas de uma companhia farmacêutica. Os dados são altamente confidenciais e por razões de governança o hardware não pode ser multi-tenant. A manutenção do banco de dados deve requerer mínimas habilidades do DBA e oferecer mais alta disponibilidade com RTO de alguns poucos minutos e zero potencial de perda de dados.

Qual opção de banco de dados é o melhor conjunto?

- Autonomous Database com Exadata Infrasestrutura Dedicada com Data Guard.
- (Autonomous Database with Exadata Dedicated Infrastructure with Data Guard).


6 - Um arquiteto de soluções do OCI está trabalhando em um banco de dados que pode escalar automaticamente para combinar com a carga de trabalho correta. Nós queremos minimizar o custo se dado uma escolha.

Quais opções de conjunto de banco de dados são melhores. Escolha 2?

- Autonomous Database com Infraestrutura Exadata Compartilhada.
- (Autonomous Database Shared Exadata Infrastructure).
- Habilitar o Auto Scaling de OCPU.
- (Enable the Autoscaling of OCPU).


7 - Você está trabalhando como um consultor de segurança com uma organização global de seguros que está usando o Microsoft Azure Active Directory como um provedor de identidade para gerenciar logins/senhas dos usuários. Quando os usuários fazem login no OCI Console, eles devem obter usuários autenticados do Azure AD.

Quais passos são requiridos para configurar no lado da OCI na ordem para que esteja habilitado esta função de login?

- Confgure o Azure AD como Provedor de Identidade, mapeie os Azure AD groups para o OCI groups, configure as políticas IAM para controlar o acesso do Azure AD groups.
- (Set up AD as an Identity Provider, map Azure Ad groups to OCI groups, set up the IAM policies to govern access to Azure AD groups).


8 - Você está implementando a infraestrutura Roving Edge no OCI. Como você deverá sincronizar os dados de Roving Edge Device (RED) com o OCI Object Storage na tenância OCI?

- Você pode sincronizar seu conjunto de dados RED object storage com sua tenância do OCI depois o nó de borda é reconectado a sua região home do OCI.
- (You can synchronize your RED object storage datasets with your Oracle Cloud Infrastructure tenancy after the edge node is reconnected to your home OCI region.


9 - Uma companhia de manufaturamento está planejando migrar cargas de trabalho de bancos de dados on-premise para o OCI e contratou você para a migração. O cliente forneceu as seguintes informações sobre o seu seu banco de dados on-premise:

Versão do banco de dados, database character set, storage for data staging, acceptable lenght of system outage.

Qual informação adicional você precisa do cliente para recomendar o método de migração adequado?

- Sistema operacional do host on-premises e a versão
- (On-premises host operating system and version).
- Tipos de dados usados no banco de dados on-premises
- (Data types used in the on-premises database).


10 - Uma empresa financeira está planejando migração de um banco de dados de 200GB para o OCI. O cliente está procurando por uma migração de tempo de inatividade zero e online.

Quail opção você deverá escolher para migrar o banco de dados.

- Use o serviço OCI Database Migration com Online e Exporte para a opção transferir dados médios.
- (Use OCI Database Migration service with Online and Export to data transfer medium option).


11 - Um companhia de seguros está armazenando dados financeiros críticos em um OCI Block Volume. Este volume está autualmente encriptado usando Oracle-managed keys. Devido a regulamentações de compliance, o cliente quer encriptar os dados usando as chaves que ele pode controlar e não as chaves controladas pela Oracle.

Quais os seguintes etapas de tarefas são requeridas para encriptar o block volume usando customer-managed keys?

- Crie um Vault, crie uma chave de encriptação mestra no Vault, atribua a chave mestra de encriptação ao block volume.
- (Create a Vault, create a master encryption key in the Vault, assign this master encryption key to the block volume).


12 - Ao configurar o serviço de vulnerabilidade do OCI. Quais opções ou passos são executadas para que o serviço funcione e atinja os objetivos requeridos nos hosts alvo? (Três opções).

- Política IAM para Administradores para recursos VSS-FAMILY)
- (IAM policy for Administrators for VSS_FAMILY resources).
- O serviço de escaneamento precisa estar habilitado para ler a VNIC na instância de computação alvo.
- (The Scanning service must also be able to read the VNIC on your target compute instances).
- Crie o host alvo.
- (Create the host target).

