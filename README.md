# Certificações Azure em público: playbook do piloto

Status: piloto iniciado; a primeira sessão está registrada no [diário de 30/10/2026](journal/2026-10-30.md). Nenhum vídeo publicado ou resultado de exame foi registrado ainda.

Criado em: 28 de outubro de 2026.

Documento complementar: [guia de gravações e pautas dos 16 vídeos](RECORDINGS.md).

## 1. Objetivo e limites

Testar um processo sustentável para estudar, registrar o aprendizado e explicar conceitos em português ao longo de quatro certificações: AZ-104, AZ-400, SC-500 e SC-100. Todas fazem parte do objetivo principal, inclusive SC-100. A preparação para as provas é a prioridade; o conteúdo nasce do estudo, não o contrário.

| Decisão | Plano |
|---|---|
| Estudo | 9 horas por semana: 1 hora por dia útil, 2 horas sábado e 2 horas domingo |
| Documentação e conteúdo | Até 2 horas adicionais por semana, de segunda a domingo |
| Materiais | Inglês; Microsoft Learn como base, GitHub para apoio, O'Reilly opcional |
| Publicações | Um vídeo gravado em português a cada quatro dias |
| Formato inicial sugerido | TikTok, vídeo simples de 45 a 90 segundos |
| Prática técnica | Sem execução de laboratórios nesta fase; leitura de exemplos continua permitida |
| AZ-104 | Agendada: quinta-feira, 19 de novembro de 2026, às 21:00 |
| AZ-400 | Agendada: quinta-feira, 3 de dezembro de 2026, às 21:00 |
| SC-500 | Meta proposta, ainda não agendada: quinta-feira, 17 de dezembro de 2026, às 21:00 |
| SC-100 | Meta proposta, ainda não agendada: segunda-feira, 28 de dezembro de 2026, às 09:00 |
| Horários | Horário local usado nos agendamentos; confirmar no provedor, sem presumir fuso |
| Primeira revisão do piloto | 11 de novembro de 2026 |
| Revisão intermediária proposta | 6 de dezembro de 2026, na transição para segurança |
| Retrospectiva final proposta | 30 de dezembro de 2026, após o quarto exame |

Somente AZ-104 e AZ-400 foram agendadas pelo participante. SC-500 e SC-100 ainda precisam ser agendadas quando houver disponibilidade no limite de reservas e no provedor. Datas de vídeos, rotinas, metas e critérios abaixo são propostas deste processo, não requisitos da Microsoft.

O objetivo é realizar os quatro exames até 28/12/2026, dois meses após o início. Agendamento é uma restrição operacional, não uma redução do escopo. Após realizar AZ-104, verificar a possibilidade de reservar SC-500; após AZ-400, reservar SC-100, conforme a disponibilidade real. Não há promessa de aprovação nem de crescimento de audiência.

### Visão das quatro fases

| Fase | Janela de estudo | Horas previstas | Exame / situação |
|---|---|---:|---|
| 1. Administração | 28/10-18/11 | 28 | AZ-104 em 19/11; agendada |
| 2. DevOps | 20/11-02/12 | 17 | AZ-400 em 03/12; agendada |
| 3. Engenharia de segurança | 04/12-16/12 | 17 | SC-500 em 17/12; meta a agendar |
| 4. Arquitetura de segurança | 18/12-27/12 | 14 | SC-100 em 28/12; meta a agendar |
| Total | Preparação até 27/12 | 76 | Quatro exames no escopo |

As 76 horas são disponibilidade, não estimativa de suficiência. As duas fases de segurança são especialmente apertadas, sem reserva explícita para retentativas. Os dias 24 e 25/12 mantêm apenas a hora habitual; não presumir férias ou disponibilidade extra. Se for necessário mudar uma data por preparação ou agenda, manter os quatro exames no plano e registrar a nova previsão.

AZ-104 atende ao requisito de certificação associada do caminho DevOps Engineer Expert [S17]. Cloud and AI Security Engineer Associate, obtida pelo caminho SC-500, é uma das certificações aceitas como pré-requisito de Cybersecurity Architect Expert [S14]. Distinguir realizar a prova, ser aprovado e receber a certificação completa; o agendamento não comprova nenhum dos dois últimos.

Twitch fica no backlog. Não adicionar lives, outra rede, automação, identidade visual ou edição elaborada durante o piloto.

## 2. Hipóteses que queremos testar

1. Consigo preservar o tempo de estudo enquanto publico a cada quatro dias.
2. Explicar um conceito em português revela lacunas que a leitura em inglês não mostrou.
3. Um registro curto permite revisar e compartilhar o processo sem virar uma segunda obrigação.

Público inicial proposto: pessoas de tecnologia que estudam para certificações Azure com tempo limitado. O posicionamento é "aprendendo em público", não "instrutor com aprovação garantida".

## 3. Rotina de estudo

### Sessão de uma hora em dia útil

| Minutos | Atividade |
|---|---|
| 00-10 | Recordar o tema anterior sem consultar notas |
| 10-40 | Ler a teoria ligada ao objetivo do dia |
| 40-60 | Resolver questões e revisar respostas, inclusive acertos por palpite |

### Sábado: duas horas

60 minutos de teoria, 40 minutos de questões e 20 minutos de revisão de erros.

### Domingo: duas horas

60 minutos de questões mistas ou avaliação, 45 minutos revisando explicações e 15 minutos escolhendo lacunas para a semana seguinte.

Em uma avaliação que exigir mais tempo, substituir a divisão normal; não correr para caber numa quantidade arbitrária de questões. Continuar a revisão na próxima sessão se necessário.

Usar uma fonte principal por tópico. GitHub ou O'Reilly substituem parte da leitura quando ajudam a resolver uma dúvida; não acrescentar um segundo curso completo.

### Critério para considerar um tópico revisado

- Explicar a decisão em palavras próprias.
- Identificar por que pelo menos uma alternativa plausível está errada.
- Interpretar um pequeno exemplo de configuração, quando aplicável.
- Marcar dúvidas restantes, sem declarar domínio apenas por ter terminado um vídeo.

## 4. Calendário AZ-104

Estimativa: 28 horas de estudo entre 28/10 e 18/11. As sessões de fim de semana duram duas horas; as demais, uma.

Os temas seguem o guia oficial [S1]. A sequência e o tempo são escolhas deste piloto. Consultar os subtópicos do guia para evitar tratar esta tabela como uma lista exaustiva.

| Data (2026) | Horas | Tema e entrega da sessão |
|---|---:|---|
| 28/10 | 1 | Avaliação inicial; listar três lacunas |
| 29/10 | 1 | Entra ID: usuários, grupos, convidados e licenças |
| 30/10 | 1 | RBAC e escopos; comparar com governança |
| 31/10 | 2 | Policy, locks e tags; revisar exemplos e questões |
| 01/11 | 2 | Subscriptions, management groups, custos; revisar identidade |
| 02/11 | 1 | Storage: tipos e redundância |
| 03/11 | 1 | Storage: chaves, SAS e políticas de acesso |
| 04/11 | 1 | Storage: acesso de rede e identidade |
| 05/11 | 1 | Blob: tiers, lifecycle, versioning e proteção |
| 06/11 | 1 | Azure Files; questões de storage e lacunas |
| 07/11 | 2 | VMs: disponibilidade, escala, discos e proteção |
| 08/11 | 2 | App Service e containers; interpretar ARM/Bicep |
| 09/11 | 1 | VNets, subnets, peering e rotas |
| 10/11 | 1 | NSGs, endpoints e Bastion |
| 11/11 | 1 | DNS, load balancing e cenários de conectividade |
| 12/11 | 1 | Monitor, logs, métricas e alertas |
| 13/11 | 1 | Backup, recuperação e Site Recovery |
| 14/11 | 2 | Questões mistas e revisão das explicações |
| 15/11 | 2 | Avaliação e checkpoint de preparação |
| 16/11 | 1 | Reforçar o objetivo mais fraco |
| 17/11 | 1 | Reforçar a segunda lacuna; cenários mistos |
| 18/11 | 1 | Revisão leve do registro de erros; nada novo |
| 19/11 | 0 | Prova às 21:00; sem produção de conteúdo |

Não transformar a sequência em regra rígida: se a avaliação inicial mostrar conhecimento sólido num tema, transferir parte desse tempo para um objetivo fraco e registrar a mudança.

## 5. Calendário AZ-400

Estimativa: 17 horas de estudo entre 20/11 e 02/12.

O guia oficial [S2] é a referência de escopo. A sequência abaixo prioriza pipelines, mas não exclui os outros domínios.

| Data (2026) | Horas | Tema e entrega da sessão |
|---|---:|---|
| 20/11 | 1 | Avaliação inicial; separar lacunas técnicas e de terminologia |
| 21/11 | 2 | Azure Pipelines/GitHub Actions: YAML, triggers, jobs e agentes |
| 22/11 | 2 | Templates, variáveis, stages, ambientes e aprovações |
| 23/11 | 1 | Artifacts, feeds, dependências e versionamento |
| 24/11 | 1 | Testes, cobertura e quality gates |
| 25/11 | 1 | Estratégias de deployment e IaC; interpretar exemplos |
| 26/11 | 1 | Identidades, service connections, segredos e scanning |
| 27/11 | 1 | Processos, rastreabilidade, comunicação e métricas |
| 28/11 | 2 | Source control, recuperação, instrumentação e questões |
| 29/11 | 2 | Avaliação mista e checkpoint de preparação |
| 30/11 | 1 | Maior lacuna; revisar cenários |
| 01/12 | 1 | Segunda lacuna; questões mistas |
| 02/12 | 1 | Revisão leve; nada novo |
| 03/12 | 0 | Prova às 21:00; sem produção de conteúdo |

## 6. Calendário SC-500

Estimativa: 17 horas de estudo entre 04/12 e 16/12. Meta proposta de prova: 17/12 às 21:00, ainda não agendada.

Usar o guia atual [S10] e o curso [S11]. A tabela é um roteiro de revisão, não substitui os subtópicos oficiais nem presume que conteúdo antigo de AZ-500 cubra o exame.

| Data (2026) | Horas | Tema e entrega da sessão |
|---|---:|---|
| 04/12 | 1 | Mapear objetivos e lacunas; revisar identidade |
| 05/12 | 2 | PIM, Conditional Access, apps, managed identities e Key Vault |
| 06/12 | 2 | Governança, papéis, Policy e proteção de storage |
| 07/12 | 1 | Segurança de bancos e auditoria |
| 08/12 | 1 | Firewall, endpoints e controles de rede |
| 09/12 | 1 | Proteção de servidores, VMs e híbrido |
| 10/12 | 1 | Containers, aplicações, WAF e APIs |
| 11/12 | 1 | Segurança de IA: identidades de agentes e proteção de dados |
| 12/12 | 2 | Defender for Cloud, postura, proteção de IA e guardrails |
| 13/12 | 2 | Sentinel, Security Copilot e checkpoint por cenários |
| 14/12 | 1 | Maior lacuna; questões disponíveis |
| 15/12 | 1 | Segunda lacuna; revisão mista |
| 16/12 | 1 | Revisão leve; nada novo |
| 17/12 | 0 | Prova proposta às 21:00; sem produção de conteúdo |

Na consulta de 28/10, a avaliação gratuita SC-500 não estava disponível [S12]. Revalidar em 04/12. Se continuar indisponível, usar knowledge checks disponíveis e cenários próprios vinculados aos objetivos. Não apresentar isso como simulado validado nem gerar uma porcentagem de preparação comparável. Material pago só entra se identificar claramente SC-500 e permitir verificar sua cobertura.

## 7. Calendário SC-100

Estimativa: 14 horas de estudo entre 18/12 e 27/12. Meta proposta de prova: 28/12 às 09:00, ainda não agendada. SC-100 é parte do objetivo, não um bônus opcional.

Seguir os objetivos vigentes desde 21/10/2026 [S13]. A diferença nesta fase é justificar decisões e trade-offs de arquitetura, em vez de apenas identificar controles. A revisão não substitui experiência de arquitetura.

| Data (2026) | Horas | Tema e entrega da sessão |
|---|---:|---|
| 18/12 | 1 | Avaliação inicial e mapa dos quatro domínios |
| 19/12 | 2 | Zero Trust, MCRA, benchmarks e resiliência |
| 20/12 | 2 | Operações, identidade, acesso privilegiado e compliance |
| 21/12 | 1 | Postura de segurança híbrida e multicloud |
| 22/12 | 1 | Endpoints, plataformas e arquitetura de rede |
| 23/12 | 1 | Aplicações, DevSecOps e cadeia de fornecimento |
| 24/12 | 1 | Proteção de dados e requisitos de IA |
| 25/12 | 1 | Cenários integrados; lacunas e trade-offs |
| 26/12 | 2 | Avaliação mista e checkpoint de preparação |
| 27/12 | 2 | Revisão leve de decisões e erros; nada novo |
| 28/12 | 0 | Prova proposta às 09:00; sem produção de conteúdo |

Usar o curso oficial [S15] como apoio e a avaliação indicada na página da certificação [S14]. Para cada cenário próprio, registrar requisito, ameaça, decisão, alternativa rejeitada e limitação. Comparar materiais mais antigos com o guia atual.

## 8. Materiais e como escolher

| Uso | Fonte | Regra |
|---|---|---|
| Checklist AZ-104 | [Guia oficial AZ-104][S1] | Validar os objetivos antes de cada bloco |
| Teoria AZ-104 | [Curso Microsoft Learn AZ-104][S3] | Seguir o estudo autodirigido; não assumir que os "4 dias" do curso são o tempo pessoal necessário |
| Checklist AZ-400 | [Guia oficial AZ-400][S2] | Conferir subtópicos, além dos títulos da tabela |
| Teoria AZ-400 | [Curso Microsoft Learn AZ-400][S4] | Ler os módulos relevantes, sem executar exercícios nesta fase |
| Checklist SC-500 | [Guia oficial SC-500][S10] | Conferir cada objetivo e as lacunas de IA |
| Teoria SC-500 | [Curso Microsoft Learn SC-500][S11] | Usar leitura e módulos disponíveis; sem executar laboratórios |
| Checklist SC-100 | [Guia oficial SC-100][S13] | Usar objetivos vigentes, não apenas resumos antigos |
| Teoria SC-100 | [Curso Microsoft Learn SC-100][S15] | Selecionar leitura para os objetivos e cenários fracos |
| Questões | [Practice Assessments Microsoft][S5] | Verificar disponibilidade por exame; registrar lacunas |
| Revisão AZ-104 | [John Savill: CertificationMaterials][S6] | Consultar whiteboard e vídeos pontuais |
| Apoio DevOps | [John Savill: DevOpsMC][S7] | Consultar explicações e exemplos; comparar com o guia atual |
| Revisão SC-100 | [John Savill: CertificationMaterials][S6] | Consultar o índice SC-100; conferir diferenças de versão |
| Cenários SC-100 no GitHub | [MicrosoftLearning: SC-100][S16] | Leitura opcional das instruções e situações; sem execução |
| Apoio SC-500 no GitHub | Materiais de segurança já listados, apenas para conceitos sobrepostos | Não foi selecionado um repositório específico SC-500 com cobertura validada; Learn continua sendo a base |
| O'Reilly, opcional | Buscar AZ-104/AZ-400/SC-500/SC-100 no catálogo disponível | Conferir código, versão e objetivos antes de escolher um trecho; não presumir oferta de todos |

Uma opção de livro é "Exam Ref AZ-104 Microsoft Azure Administrator, 2nd Edition", de Charles Pluta, publicado em 2024 [S8]. É complementar: comparar com o guia atual. Não há necessidade de comprar assinatura ou livro para começar.

Os guias consultados indicam objetivos de AZ-104 vigentes desde 17/04/2026 e AZ-400 desde 27/07/2026 [S1][S2]. Revalidar antes das provas, especialmente se o idioma do exame for diferente do material.

As avaliações gratuitas não reproduzem as questões reais nem toda a complexidade da prova [S5]. Questões reconhecidas de uma tentativa anterior não contam como evidência independente de preparação.

Os materiais GitHub são apoio de estudo, não autorização para republicar imagens ou trechos. O README de DevOpsMC reserva direitos sobre o conteúdo [S7]. Compartilhar o link e criar explicações e visuais próprios.

## 9. Checkpoints de preparação

Datas: 15/11 para AZ-104, 29/11 para AZ-400, 13/12 para SC-500 e 26/12 para SC-100.

Quando houver um banco de questões adequado, o critério pessoal proposto é buscar 80-85% em questões pouco familiares, explicar as alternativas e não deixar um domínio inteiro sem revisão. Esse intervalo não é um critério oficial nem garantia de aprovação. Para SC-500 sem avaliação disponível, usar cobertura dos objetivos e explicações fundamentadas dos cenários, não uma nota inventada.

Quando não houver questões novas, explicar cenários próprios e registrar que a tentativa foi repetida, em vez de tratar a nota como previsão.

Se houver lacunas importantes:

1. Reservar as sessões restantes para os objetivos fracos.
2. Simplificar ou pular um vídeo; não retirar horas do estudo.
3. Avaliar a manutenção da data conforme a preparação e as regras do agendamento.

A ausência de laboratórios é uma escolha desta fase, não uma afirmação de que experiência prática seja desnecessária ou de que a prova não possa incluir tarefas práticas [S5].

## 10. Processo: estudar, registrar, explicar, publicar, revisar

### Etapa A: estudar

Executar a sessão planejada. Não abrir o editor de vídeo durante o horário de estudo.

### Etapa B: registrar em até dois minutos

Depois da sessão, registrar o tema, uma decisão aprendida, uma lacuna e a fonte. Usar notas locais até decidir o que compartilhar.

```text
Data:
Exame / objetivo:
Minutos estudados:
Fonte e seção:
Regra que consigo explicar:
Lacuna ou erro conceitual:
Próxima revisão:
Ideia de conteúdo, se houver:
```

### Etapa C: selecionar

Escolher apenas um conceito por vídeo. Preferir uma confusão real do estudo, não pesquisar um tema novo para alimentar o calendário.

Fila simples: ideia -> roteiro -> gravado -> pronto -> publicado.

### Etapa D: produzir em até 40 minutos por vídeo

| Atividade | Minutos |
|---|---:|
| Escolher a ideia, conferir a fonte e escrever tópicos | 8 |
| Gravar, com no máximo duas tentativas | 10 |
| Cortar pausas e adicionar legendas simples | 12 |
| Preparar legenda, fonte e publicar | 5 |
| Registrar o link e uma observação | 5 |
| Total | 40 |

Proposta de formato: celular na vertical, voz clara, um enquadramento e um único conceito. Duração de 45-90 segundos é uma escolha editorial do piloto, não um limite técnico da plataforma.

Se ultrapassar 40 minutos, simplificar o vídeo seguinte. Não comprar equipamento nem ferramentas antes da primeira revisão.

### Etapa E: revisar o processo uma vez por semana

Reservar 20 minutos para verificar horas, fila, dúvidas e um aprendizado sobre comunicar. Responder apenas aos comentários que couberem nesse tempo.

Orçamento máximo típico: dois vídeos de 40 minutos + sete registros de 2 minutos + revisão de 20 minutos = 114 minutos. Sobram 6 minutos de margem no limite semanal de 120 minutos. Preparar um vídeo antecipadamente consome o orçamento da semana em que o trabalho ocorrer.

Publicar manualmente; este plano não configura agendadores nem publica em contas.

## 11. Calendário editorial proposto

Primeira publicação sugerida: 31/10. A partir dela, intervalo de quatro dias. Os temas podem mudar conforme o aprendizado; não os resultados das provas.

Para preparar cada publicação, abrir o [guia de gravações](RECORDINGS.md): ele contém pautas detalhadas, perguntas para desenvolver, sugestões visuais, fontes e um cartão de produção. O primeiro vídeo tem um roteiro inicial completo. Este playbook continua sendo a referência das datas de estudo e provas.

| # | Publicar em 2026 | Tema sugerido | Gancho em português |
|---|---|---|---|
| 01 | 31/10, sábado | [Apresentar o experimento](RECORDINGS.md#video-01) | "Nove horas de estudo por semana: vou documentar o que funciona." |
| 02 | 04/11, quarta | [Acesso a storage](RECORDINGS.md#video-02) | "Acesso pela rede e permissão nos dados não são a mesma pergunta." |
| 03 | 08/11, domingo | [Comparar opções de compute](RECORDINGS.md#video-03) | "Antes de decorar um serviço, estou aprendendo a comparar as opções." |
| 04 | 12/11, quinta | [Organizar o raciocínio sobre rede](RECORDINGS.md#video-04) | "Uma distinção de rede que eu precisava explicar sem consultar notas." |
| 05 | 16/11, segunda | [Checkpoint antes de AZ-104](RECORDINGS.md#video-05) | "O que minha revisão mostrou e como vou usar os últimos dias." |
| 06 | 20/11, sexta | [Retrospectiva AZ-104](RECORDINGS.md#video-06) | "O que eu manteria e mudaria no meu jeito de estudar." |
| 07 | 24/11, terça | [Do commit ao artefato](RECORDINGS.md#video-07) | "Decorar YAML não substitui entender o fluxo." |
| 08 | 28/11, sábado | [Identidades de pipelines](RECORDINGS.md#video-08) | "Quem precisa fazer o quê?" |
| 09 | 02/12, quarta | [Revisão na véspera](RECORDINGS.md#video-09) | "Na véspera, meu plano é revisar, não começar outro curso." |
| 10 | 06/12, domingo | [Transição para SC-500](RECORDINGS.md#video-10) | "O plano continua com segurança." |
| 11 | 10/12, quinta | [Ameaça e controle](RECORDINGS.md#video-11) | "Qual ameaça esse controle realmente reduz?" |
| 12 | 14/12, segunda | [Segurança de IA](RECORDINGS.md#video-12) | "Depois de identificar quem acessa, qual pergunta vem a seguir?" |
| 13 | 18/12, sexta | [Transição para SC-100](RECORDINGS.md#video-13) | "Agora a pergunta muda: como justificar uma arquitetura?" |
| 14 | 22/12, terça | [Decisão de Zero Trust](RECORDINGS.md#video-14) | "Qual requisito justifica esta decisão de segurança?" |
| 15 | 26/12, sábado | [Revisar alternativas de arquitetura](RECORDINGS.md#video-15) | "Além da solução escolhida, estou revisando a alternativa rejeitada." |
| 16 | 30/12, quarta | [Retrospectiva das quatro etapas](RECORDINGS.md#video-16) | "O que mudou no meu estudo e no processo de compartilhar." |

O vídeo 06 pode mencionar um resultado apenas se já conhecido e se o participante quiser compartilhá-lo; o roteiro não presume aprovação. Não discutir questões da prova.

Os vídeos 10 e 13 também devem distinguir etapa realizada, resultado conhecido e certificação obtida; não presumir aprovação.

Proteção de agenda: deixar o vídeo de 02/12 pronto em 30/11 ou 01/12 e o de 26/12 pronto até 23/12, preservando a revisão final. Nas datas de prova, nenhuma obrigação de conteúdo. Se atrasar, pular e retomar a próxima data; não criar uma dívida de vídeos. Manter as retrospectivas mesmo se uma prova for reagendada, explicando a mudança.

## 12. Estrutura de um vídeo

| Parte | Duração sugerida | Conteúdo |
|---|---|---|
| Gancho | 0-5 s | Uma dificuldade específica |
| Contexto | 5-15 s | O que estava estudando |
| Explicação | 15-55 s | Uma distinção e um exemplo próprio |
| Conclusão | 55-75 s | O que mudou no entendimento |
| Fechamento opcional | 75-90 s | Próximo tópico ou pergunta genuína |

Manter nomes técnicos em inglês quando isso evitar ambiguidade. Explicar o conceito em português; não traduzir slides inteiros.

### Primeiro vídeo: roteiro pronto para adaptar

O [vídeo 01 no guia de gravações](RECORDINGS.md#video-01) contém o roteiro e a legenda iniciais. Mantê-los naquele arquivo para evitar versões divergentes. Adaptar a fala ao estado real dos agendamentos e incluir a fonte pública ao explicar um conceito técnico.

## 13. O que documentar e compartilhar

O registro público deve ser útil e honesto: tempo aproximado, conceito aprendido, dúvida, fonte e ajuste de plano. Números ausentes ficam como "não medido", não como zero.

```text
## Revisão semanal
Período:
Horas de estudo planejadas / realizadas:
Minutos de documentação e conteúdo:
Objetivos revisados:
Maior lacuna:
O que funcionou:
O que mudar:
Vídeos publicados / planejados:
Links publicados:
Próximo foco:
```

```text
## Registro de conceito
Exame / objetivo:
Minha interpretação inicial:
Regra correta, em palavras próprias:
Exemplo fictício:
Fonte pública:
Revisado em:
Status: preciso revisar | consigo explicar | consigo aplicar a um cenário
```

Não copiar enunciados de bancos de questões para o registro público. Registrar apenas a lacuna conceitual em palavras próprias.

### Proteção do conteúdo

Gravar somente antes ou depois das sessões de estudo, nunca durante a prova ou seu check-in. O acordo da Microsoft proíbe divulgar conteúdo confidencial das provas [S9].

Usar explicações, exemplos e visuais próprios. Não publicar páginas de livros, questões de simulados, aulas pagas ou materiais de terceiros sem a permissão necessária.

Não mostrar sistemas de trabalho, dados de clientes, credenciais, notificações pessoais ou detalhes privados de agendamento. Antes de compartilhar um arquivo, revisar seu conteúdo; antes de gravar uma tela, fechar o que não pertence ao piloto.

## 14. Como avaliar o piloto

Metas propostas, não promessas:

| Indicador | Como medir | Critério de decisão |
|---|---|---|
| Estudo preservado | Horas realizadas / planejadas no período | Buscar pelo menos 80%; se ficar abaixo, reduzir conteúdo |
| Limite de produção | Somar os minutos de segunda a domingo | Não exceder 120 minutos |
| Cadência sustentável | Vídeos publicados / previstos até a revisão | Buscar pelo menos 80%, sem compensação em dobro |
| Clareza | Explicar sem ler e conferir uma regra na fonte | Corrigir dúvidas antes de publicar |
| Utilidade percebida | Registrar uma pergunta útil ou melhoria na explicação | Avaliação qualitativa, sem meta de seguidores |
| Audiência, opcional | Consultar visualizações/retenção disponíveis uma vez por semana | Aprender com o formato; não usar como meta principal |

Em 11/11, haverá três publicações previstas até então: 31/10, 04/11 e 08/11. Decidir entre manter, simplificar ou pausar. Não adicionar Twitch nessa revisão apenas por entusiasmo: primeiro verificar tempo e preparação.

Em 06/12, fazer uma revisão intermediária após a etapa AZ-400. SC-500 e SC-100 continuam no escopo; decidir apenas ajustes de rotina, cadência e datas conforme preparação. Não transformar a revisão em autorização para incluir as duas certificações: elas já fazem parte do objetivo.

Em 30/12, revisar as quatro etapas e as 16 publicações previstas. Registrar provas realizadas, reagendamentos, resultados conhecidos e requisitos de certificação ainda pendentes separadamente. Decidir se a rotina continua e se faz sentido testar uma live em uma fase posterior.

Uma reprovação não significa automaticamente que o piloto de documentação falhou. Avaliar preparação e processo separadamente; em ambos os casos, documentar o que mudar.

## 15. Primeiros passos

### 28/10

- Fazer a sessão AZ-104 inicial de uma hora.
- Registrar as três principais lacunas em até dois minutos.
- Ler e ajustar o roteiro de apresentação dentro do orçamento de conteúdo.

### Até 31/10

- Gravar o primeiro vídeo sem tentar resolver toda a identidade do projeto.
- Conferir áudio, legenda e conteúdo antes de publicar.
- Publicar apenas após decisão do participante; registrar o link.

### Depois

Manter um conceito em reserva para a próxima publicação. Não criar uma lista enorme de temas que exija pesquisa adicional.

Após realizar AZ-104, verificar e reservar SC-500 para a meta proposta, se disponível. Após AZ-400, fazer o mesmo para SC-100. Atualizar o status no início deste arquivo somente depois da confirmação; não confundir data desejada com reserva.

## 16. Repositório e preparação para publicação

Este arquivo é o playbook do repositório `azure-certifications-pilot`, hospedado no GitHub, com histórico de commits e branch padrão `main`.

A estrutura atual contém `README.md`, `RECORDINGS.md` e `journal/`. Para ampliar o registro público, manter uma estrutura simples:

```text
README.md          Este playbook, ajustado para apresentação pública
RECORDINGS.md      Pautas dos vídeos, roteiro inicial e processo de gravação
journal/           Revisões semanais escolhidas para compartilhar
concepts/          Explicações próprias com fontes
content/           Roteiros e links publicados, sem arquivos de vídeo
```

As pastas `concepts/` e `content/` são sugestões futuras e ainda não foram criadas. Não é necessário configurar Actions, site, domínio ou ferramenta de métricas para validar o piloto.

## Licença

O conteúdo original deste repositório é disponibilizado sob a licença [Creative Commons Atribuição 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). O texto completo está em [LICENSE](LICENSE).

Você pode copiar, adaptar e redistribuir esse conteúdo, inclusive para fins comerciais, desde que atribua crédito a gabrielpedepera e aos demais autores identificados, inclua um link para a licença e indique as alterações realizadas.

Exemplo de atribuição: "Adaptado de azure-certifications-pilot, por gabrielpedepera e colaboradores, disponível em https://github.com/gabrielpedepera/azure-certifications-pilot, sob CC BY 4.0. Alterações: [descrever]."

A licença não abrange materiais de terceiros referenciados ou vinculados, que continuam sujeitos às respectivas licenças e permissões.

## Fontes

Consultadas em 28/10/2026. A sequência de estudo, os roteiros e as metas são propostas próprias; não são um programa oficial.

[S1]: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-104
[S2]: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-400
[S3]: https://learn.microsoft.com/en-us/training/courses/az-104t00
[S4]: https://learn.microsoft.com/en-us/training/courses/az-400t00
[S5]: https://learn.microsoft.com/en-us/credentials/certifications/practice-assessments-for-microsoft-certifications
[S6]: https://github.com/johnthebrit/CertificationMaterials
[S7]: https://github.com/johnthebrit/DevOpsMC
[S8]: https://www.microsoftpressstore.com/store/exam-ref-az-104-microsoft-azure-administrator-9780138345938
[S9]: https://learn.microsoft.com/en-us/credentials/support/certification-exam-candidate-agreement
[S10]: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/sc-500
[S11]: https://learn.microsoft.com/en-us/training/courses/sc-500t00
[S12]: https://learn.microsoft.com/en-us/credentials/certifications/cloud-and-ai-security-engineer-associate/
[S13]: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/sc-100
[S14]: https://learn.microsoft.com/en-us/credentials/certifications/cybersecurity-architect-expert/
[S15]: https://learn.microsoft.com/en-us/training/courses/sc-100t00
[S16]: https://github.com/MicrosoftLearning/SC-100-Microsoft-Cybersecurity-Architect
[S17]: https://learn.microsoft.com/en-us/credentials/certifications/devops-engineer/
