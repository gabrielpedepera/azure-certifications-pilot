# Guia de gravações: quatro certificações em público

[Voltar ao plano de estudos](README.md)

Documento de trabalho em português, criado em 28/10/2026. Todos os vídeos abaixo estão planejados; nenhum foi marcado como gravado ou publicado.

## Como usar

O [playbook](README.md) define o estudo, as datas das provas e o orçamento de tempo. Este guia transforma o calendário editorial em pautas concretas.

Cada vídeo apresenta uma única ideia que nasceu do estudo. O objetivo é explicar um aprendizado, uma dúvida ou um ajuste de método, não dar uma aula completa nem comentar questões reais de prova.

- Público proposto: pessoas de tecnologia estudando Azure com tempo limitado.
- Linguagem: português, preservando nomes técnicos em inglês quando necessário.
- Formato proposto: 45-90 segundos, celular na vertical, um enquadramento.
- Produção: no máximo 40 minutos por vídeo, dentro das duas horas adicionais por semana.
- Gravação: no máximo duas tentativas; tópicos ao lado da câmera, sem memorizar parágrafos.
- Fontes: conferir o ponto técnico no material indicado antes de gravar.
- Se houver dúvida não resolvida: publicar uma reflexão sobre o método ou usar o tema reserva; não improvisar uma resposta técnica.

O texto de um gancho pode ser adaptado. Não dizer "eu confundia", "eu aprendi" ou anunciar um resultado se isso não aconteceu.

## Índice de pautas

Datas de publicação propostas em 2026, com intervalo de quatro dias. Os títulos são pautas de trabalho, não promessas de resultados.

| Vídeo | Publicação | Pauta | Tipo |
|---|---|---|---|
| [01](#video-01) | 31/10 | Quatro certificações, uma rotina possível | Apresentação |
| [02](#video-02) | 04/11 | Storage: acesso pela rede versus permissão | Conceito AZ-104 |
| [03](#video-03) | 08/11 | Como estudar as opções de compute sem decorar listas | Conceito AZ-104 |
| [04](#video-04) | 12/11 | Como estou organizando o raciocínio sobre rede | Conceito AZ-104 |
| [05](#video-05) | 16/11 | Meu checkpoint antes de AZ-104 | Processo |
| [06](#video-06) | 20/11 | O que manter e mudar depois da etapa AZ-104 | Retrospectiva |
| [07](#video-07) | 24/11 | Pipeline: do commit ao artefato | Conceito AZ-400 |
| [08](#video-08) | 28/11 | Como estou estudando identidades de pipelines | Conceito AZ-400 |
| [09](#video-09) | 02/12 | O que cabe na véspera de uma prova | Processo |
| [10](#video-10) | 06/12 | Da administração e DevOps para segurança | Transição SC-500 |
| [11](#video-11) | 10/12 | Qual ameaça justifica este controle? | Conceito SC-500 |
| [12](#video-12) | 14/12 | Segurança de IA: uma pergunta além da identidade | Conceito SC-500 |
| [13](#video-13) | 18/12 | De escolher controles a justificar arquitetura | Transição SC-100 |
| [14](#video-14) | 22/12 | Uma decisão de Zero Trust, um requisito | Conceito SC-100 |
| [15](#video-15) | 26/12 | A alternativa que eu rejeitaria e por quê | Checkpoint SC-100 |
| [16](#video-16) | 30/12 | O que funcionou no experimento | Retrospectiva final |

## Video 01

**Publicar:** 31/10. **Título:** Quatro certificações, uma rotina possível.

**Objetivo:** apresentar o experimento, o limite de tempo e o que a audiência pode acompanhar.

**Gancho:** "Quero estudar para quatro certificações Microsoft com nove horas por semana. Vou documentar o que realmente conseguir fazer."

**Três pontos:** sequência AZ-104 -> AZ-400 -> SC-500 -> SC-100; duas provas agendadas e duas a reservar; materiais em inglês, explicações em português.

**Visual:** falar para a câmera; opcionalmente mostrar uma lista própria com os quatro códigos. Não mostrar a confirmação do agendamento.

**Roteiro inicial para adaptar:**

> Comecei um experimento: estudar para AZ-104, AZ-400, SC-500 e SC-100 com nove horas por semana.
>
> As duas primeiras provas estão agendadas. As outras duas também fazem parte do plano; ainda preciso reservá-las.
>
> Vou estudar principalmente com Microsoft Learn e materiais públicos em inglês. Aqui, vou explicar em português um conceito, uma dificuldade ou uma mudança no método a cada quatro dias.
>
> Nesta fase, o foco é teoria e questões de prática, sem laboratórios. Isso tem limitações, e não estou prometendo aprovação.
>
> Quero descobrir um processo que eu consiga manter e mostrar os ajustes, não uma rotina perfeita.

**Legenda:** "Começando um piloto de estudo em público: quatro certificações, materiais em inglês e explicações em português. Vou registrar o processo e ajustar o plano conforme aprender. #Azure #Certificacoes"

**Fonte:** [plano e restrições do piloto](README.md).

## Video 02

**Publicar:** 04/11. **Título:** Storage: acesso pela rede versus permissão.

**Objetivo:** explicar uma distinção de acesso usando um exemplo fictício.

**Gancho:** "Quando uma aplicação não acessa um storage, estou separando duas perguntas antes de escolher uma solução."

**Três pontos:** o caminho de rede permite a conexão? Qual identidade ou credencial a aplicação usa? Essa forma de acesso permite a operação desejada?

**Visual:** dois cartões próprios, "caminho de rede" e "acesso aos dados". Não abrir o portal nem desenhar uma topologia complexa.

**Exemplo a preparar:** uma aplicação fictícia precisa ler um arquivo. Escolher uma única configuração estudada e conferir seu comportamento antes de descrevê-lo.

**Fechamento:** "Meu exercício agora é justificar qual pergunta cada configuração responde."

**Fonte para conferir:** objetivos e referências de storage no [guia AZ-104][AZ104].

## Video 03

**Publicar:** 08/11. **Título:** Como estudar as opções de compute sem decorar listas.

**Objetivo:** mostrar uma forma de comparar escolhas, não listar todos os serviços.

**Gancho:** "Em vez de decorar nomes, estou tentando responder quais requisitos mudam a escolha."

**Três pontos:** escolher um cenário fictício; comparar apenas duas opções revisadas, como VM e App Service; explicar um critério e uma limitação da escolha.

**Visual:** uma tabela própria com duas opções e duas perguntas: "o que preciso controlar?" e "o que quero deixar de administrar?".

**Exemplo a preparar:** uma aplicação web simples, com requisitos explicitamente descritos. Não declarar uma opção universalmente melhor.

**Fechamento:** "Se eu mudar esse requisito, minha decisão ainda faz sentido?"

**Fonte para conferir:** objetivos de compute e suas referências no [guia AZ-104][AZ104].

## Video 04

**Publicar:** 12/11. **Título:** Como estou organizando o raciocínio sobre rede.

**Objetivo:** explicar a ordem das perguntas que ajudam a entender conectividade.

**Gancho:** "Antes de procurar uma configuração, estou tentando desenhar o caminho da conexão."

**Três pontos:** identificar origem e destino; separar resolução de nome, rota e regras de acesso; escolher uma dúvida já resolvida durante o estudo.

**Visual:** desenho próprio com três caixas e uma seta; destacar apenas o ponto discutido.

**Exemplo a preparar:** um cenário fictício de aplicação acessando um recurso. Não apresentar a sequência como diagnóstico completo para qualquer incidente.

**Fechamento:** "O que eu precisaria verificar para testar essa hipótese?"

**Fonte para conferir:** objetivos de networking no [guia AZ-104][AZ104].

## Video 05

**Publicar:** 16/11. **Título:** Meu checkpoint antes de AZ-104.

**Objetivo:** mostrar como a revisão altera as últimas sessões de estudo.

**Gancho:** "Faltam poucos dias para a prova. Meu foco agora não é terminar outro curso."

**Três pontos:** um objetivo que consigo explicar; uma lacuna real; como distribuí as sessões restantes.

**Visual:** três tópicos próprios, sem screenshots ou enunciados de simulados.

**Dados a preparar:** horas efetivamente estudadas e avaliação de 15/11, se realizada. Distinguir tentativa nova de repetida; se não mediu, dizer isso.

**Fechamento:** "Vou usar os próximos dias para revisar essa lacuna, não só repetir o que já conheço."

**Fonte:** checkpoint AZ-104 no [playbook](README.md).

## Video 06

**Publicar:** 20/11. **Título:** O que manter e mudar depois da etapa AZ-104.

**Objetivo:** registrar o método sem revelar conteúdo da prova nem presumir aprovação.

**Gancho:** "Depois desta etapa, eu manteria uma parte da rotina e mudaria outra."

**Três pontos:** o que funcionou no estudo; o que consumiu tempo sem ajudar; a mudança escolhida para AZ-400.

**Visual:** cartões "manter" e "mudar".

**Antes de gravar:** confirmar se a prova foi realizada, reagendada ou ainda está pendente. Resultado é opcional e só deve ser mencionado se conhecido.

**Fechamento:** "Agora vou testar esse ajuste na preparação para DevOps."

**Fonte:** registro pessoal de estudo; não usar lembranças de questões da prova.

## Video 07

**Publicar:** 24/11. **Título:** Pipeline: do commit ao artefato.

**Objetivo:** explicar uma parte do fluxo, sem ensinar YAML completo.

**Gancho:** "Ler YAML ficou mais útil quando comecei a desenhar o que precisava acontecer."

**Três pontos:** qual evento inicia o exemplo? O que precisa ser validado? Qual saída deve ficar disponível para a próxima etapa?

**Visual:** desenho próprio "commit -> validação -> artefato". Se usar um exemplo de configuração, escrevê-lo ou verificar a licença e a fonte.

**Exemplo a preparar:** selecionar uma pequena parte de um pipeline de estudo; não é necessário executá-lo.

**Fechamento:** "Qual saída eu esperaria dessa etapa, e como saberia que ela falhou?"

**Fonte para conferir:** objetivos de build/release no [guia AZ-400][AZ400].

## Video 08

**Publicar:** 28/11. **Título:** Como estou estudando identidades de pipelines.

**Objetivo:** explicar uma pergunta de segurança sem mostrar credenciais.

**Gancho:** "Antes de perguntar onde guardar um segredo, estou perguntando quem precisa fazer o quê."

**Três pontos:** identificar o ator do cenário; definir ação e escopo necessários; comparar a forma de autenticação estudada com uma alternativa.

**Visual:** diagrama próprio "pipeline -> identidade -> recurso".

**Exemplo a preparar:** um pipeline fictício que precisa publicar uma aplicação. Conferir os requisitos e limites da opção escolhida; não afirmar que uma solução serve para todos os contextos.

**Fechamento:** "Essa permissão está limitada ao que o processo realmente precisa?"

**Fonte para conferir:** objetivos de segurança e service connections no [guia AZ-400][AZ400].

## Video 09

**Publicar:** 02/12. **Preparar:** 30/11 ou 01/12.

**Título:** O que cabe na véspera de uma prova.

**Objetivo:** compartilhar a estratégia de revisão, sem criar trabalho na véspera.

**Gancho:** "Este vídeo ficou pronto antes: hoje eu quero revisar, não produzir conteúdo."

**Três pontos:** revisar o registro de erros; evitar um curso novo; conferir o próprio agendamento e descansar.

**Visual:** checklist próprio com três itens; não mostrar dados de reserva.

**Fechamento:** "Depois da etapa, vou avaliar se esse fechamento funcionou para mim."

**Fonte:** rotina pessoal no [playbook](README.md). Usar essa fala apenas se o vídeo realmente tiver sido preparado antes.

## Video 10

**Publicar:** 06/12. **Título:** Da administração e DevOps para segurança.

**Objetivo:** mostrar que o plano continua pelas quatro certificações.

**Gancho:** "As duas primeiras etapas não eram o plano inteiro. Agora o foco é segurança."

**Três pontos:** informar o estado real de AZ-104/AZ-400; apresentar o foco de SC-500; escolher uma lacuna para a semana.

**Visual:** lista dos quatro exames, com estados honestos: planejado, agendado, realizado ou resultado conhecido.

**Antes de gravar:** confirmar o agendamento de SC-500; não apresentar 17/12 como reserva se continuar sendo meta.

**Fechamento:** "A próxima pergunta é como proteger os ambientes que eu estava estudando."

**Fonte:** plano atualizado e [guia SC-500][SC500].

## Video 11

**Publicar:** 10/12. **Título:** Qual ameaça justifica este controle?

**Objetivo:** relacionar uma necessidade de proteção a um único controle estudado.

**Gancho:** "Estou tentando parar de decorar controles e começar pela ameaça."

**Três pontos:** descrever um risco fictício; escolher um controle já revisado; explicar uma limitação ou dependência.

**Visual:** três cartões: "risco", "controle", "limite".

**Exemplo a preparar:** selecionar um caso de identidade, rede ou aplicação que já tenha sido estudado. Não tentar cobrir todas as camadas no mesmo vídeo.

**Fechamento:** "O que esse controle não resolve sozinho?"

**Fonte para conferir:** domínio correspondente no [guia SC-500][SC500].

## Video 12

**Publicar:** 14/12. **Título:** Segurança de IA: uma pergunta além da identidade.

**Objetivo:** explicar uma pergunta de proteção que surgiu no estudo, sem prometer segurança completa.

**Gancho:** "Depois de identificar quem acessa, qual outra pergunta de segurança eu preciso responder?"

**Três pontos:** escolher um cenário fictício com IA; selecionar apenas uma pergunta sobre dados, conteúdo ou postura; apresentar a resposta conferida e seu limite.

**Visual:** "cenário -> pergunta -> controle -> limite", usando no máximo quatro termos.

**Exemplo a preparar:** um caso pequeno ligado a um objetivo SC-500 revisado. Se não conseguir verificar a explicação, usar o tema reserva e relatar a lacuna no checkpoint.

**Fechamento:** "Esse é o ponto que ainda preciso revisar antes da prova."

**Fonte para conferir:** objetivos de IA no [guia SC-500][SC500].

## Video 13

**Publicar:** 18/12. **Título:** De escolher controles a justificar arquitetura.

**Objetivo:** apresentar a mudança de raciocínio para a etapa SC-100.

**Gancho:** "Agora não quero só identificar uma opção: quero justificar por que ela atende ao requisito."

**Três pontos:** estado real de SC-500; uma pergunta que exige trade-off; como será a revisão de arquitetura.

**Visual:** "requisito -> decisão -> alternativa -> limitação".

**Antes de gravar:** confirmar o estado de SC-100 e mencionar 28/12 como meta se ainda não estiver agendada.

**Fechamento:** "Vou tentar explicar também por que rejeitaria a alternativa."

**Fonte:** registro pessoal e [guia SC-100][SC100].

## Video 14

**Publicar:** 22/12. **Título:** Uma decisão de Zero Trust, um requisito.

**Objetivo:** tornar uma decisão de arquitetura compreensível num exemplo pequeno.

**Gancho:** "Se eu só disser 'Zero Trust', ainda não expliquei minha decisão."

**Três pontos:** declarar um requisito fictício; selecionar uma decisão revisada; explicar um trade-off.

**Visual:** dois caminhos com uma escolha destacada e o requisito acima.

**Exemplo a preparar:** cenário próprio de acesso ou infraestrutura, com contexto suficiente para não tratar uma escolha como universal.

**Fechamento:** "Se o requisito mudasse, eu precisaria rever a decisão?"

**Fonte para conferir:** objetivos de Zero Trust e infraestrutura no [guia SC-100][SC100].

## Video 15

**Publicar:** 26/12. **Preparar:** até 23/12.

**Título:** A alternativa que eu rejeitaria e por quê.

**Objetivo:** mostrar o método de revisão de arquitetura sem interromper o checkpoint final.

**Gancho:** "Para revisar arquitetura, estou tentando explicar também a opção que eu não escolheria."

**Três pontos:** requisito de um cenário próprio; decisão proposta; motivo para rejeitar uma alternativa.

**Visual:** duas opções, um requisito e um trade-off.

**Antes de gravar:** usar apenas objetivos já estudados até 23/12; não antecipar uma nota ou conclusão do checkpoint de 26/12.

**Fechamento:** "Hoje é dia de revisão. O resultado dessa preparação fica para a retrospectiva."

**Fonte:** método pessoal e [guia SC-100][SC100].

## Video 16

**Publicar:** 30/12. **Título:** O que funcionou no experimento.

**Objetivo:** fechar o ciclo com resultados reais de estudo e produção.

**Gancho:** "O experimento terminou com alguns números e algumas mudanças de plano."

**Três pontos:** situação de cada prova; tempo de estudo e produção efetivamente registrado; uma decisão sobre continuar ou mudar o formato.

**Visual:** quadro próprio com "planejado", "realizado" e "próximo ajuste".

**Dados a preparar:** publicações reais, horas registradas e resultados conhecidos. Se uma prova tiver sido reagendada, dizer isso; não chamar o objetivo de concluído automaticamente.

**Fechamento:** "O que eu repetiria é [X]. O que vou mudar é [Y]."

**Fonte:** registros pessoais; não preencher lacunas com números estimados apresentados como medidos.

## Tema reserva

**Título:** Como transformo uma dúvida em plano de revisão.

**Gancho:** "Hoje não vou explicar um conceito que ainda não consegui verificar."

**Pontos:** nomear a lacuna sem copiar uma questão; indicar a fonte que vai consultar; mostrar a próxima ação de revisão.

Esse formato é útil quando a pauta técnica ainda não está pronta. Também é válido pular uma publicação e retomar a próxima data, sem vídeo extra de compensação.

## Cartão de produção reutilizável

```text
Vídeo:
Data planejada:
Status: ideia | roteiro | gravado | pronto | publicado | pulado
Objetivo do estudo relacionado:
Uma frase que quero explicar:
Gancho:
Três pontos:
Exemplo fictício:
Fonte e seção verificadas:
Visual:
Fechamento:
Legenda:
Minutos gastos:
Link publicado, somente depois da publicação:
Uma melhoria para o próximo:
```

## Antes de publicar

- Confirmar que as falas descrevem o que realmente aconteceu.
- Conferir a explicação técnica na fonte e indicar a referência na legenda quando aplicável.
- Usar materiais próprios; não exibir questões de prova, simulados, aulas pagas ou dados de trabalho.
- Ouvir o áudio e conferir as legendas, especialmente nomes de serviços.
- Verificar se há dados privados no enquadramento ou na tela.
- Registrar tempo de produção e link depois da publicação.

Não é necessário adotar todas as sugestões visuais nem terminar todas as pautas. Uma ideia clara por vídeo é suficiente para testar o processo.

## Referências de estudo

Estes links apontam para as mesmas fontes do playbook. O guia de gravações propõe perguntas e formatos; não substitui a documentação técnica.

[AZ104]: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-104
[AZ400]: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-400
[SC500]: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/sc-500
[SC100]: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/sc-100
