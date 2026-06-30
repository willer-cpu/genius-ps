# GENIUS PS — BASE DE CONHECIMENTO
Gerado em: 2026-06-25 20:00
Usuário: willer.alberto@blip.ai
Documentos: 10

---
Este arquivo é o contexto que o Genius PS usa para responder perguntas.
Não edite manualmente — é gerado automaticamente pelo Notebook C.
---
## [ID: 20260525-weekly-interno] Reunião semanal para definir arquitetura, escopo do MVP e prioridades operacionais do projeto Gênios.
**Tipo:** reunion | **Data:** 2026-05-25 | **Área:** cs, dados, engenharia, ops | **Ritual:** weekly
**Participantes:** Rafael Barreto, Vania Rodenas, Euleno Sousa, Joao Figueiredo, Willer Batista, Vinicius Bandeira
**Tags:** genius, arquitetura, gcp, mvp, roadmap, engenharia, dados, rag, blipdocs, llm, vectorsearch, embedding, produtividade, planejamento

**Resumo:** A reunião estabeleceu diretrizes para o projeto Gênios, definindo arquitetura técnica, escopo do MVP de 30 dias e prioridades operacionais, com foco na escalabilidade via Google Cloud Platform e curadoria de dados. O objetivo é centralizar conhecimentos e aumentar a produtividade operacional da equipe de PS.

**Decisões tomadas:**
- O roadmap do projeto Gênios será finalizado em uma sessão de brainstorming.
- A validação técnica da arquitetura com a equipe de plataforma é um requisito fundamental para o início do projeto.
- Vania Rodenas é a responsável pela validação da arquitetura e curadoria de dados do projeto.
- A estratégia do MVP prioriza a segmentação de casos de uso específicos e dados recentes.
- A responsabilidade pela veracidade dos documentos será das gerências das áreas.
- Serão implementados fóruns quinzenais de status report para alinhamento entre as frentes de agentes (QA, Insight, Gênios).
- A equipe buscará criar visões assíncronas do projeto para otimizar o tempo das reuniões síncronas.

**Action items:**
- **vania.rodenas@blip.ai** → Validar ferramentas GCP com o time de plataforma.
- **The group** → Construir Roadmap em sessão de brainstorming. (prazo: próxima quarta-feira)
- **rafael.barreto@blip.ai** → Agendar a sessão de brainstorming para a próxima quarta-feira.
- **rafael.barreto@blip.ai** → Compartilhar os roadmaps atuais das frentes de QA e Insight.
- **euleno.sousa@blip.ai, joao.figueiredo@blip.ai, willer.batista@blip.ai, vania.rodenas@blip.ai** → Revisar o fluxo técnico da RAG e o plano de 30 dias. (prazo: antes da reunião de quarta-feira)
- **rafael.barreto@blip.ai** → Agendar encontro semanal para a equipe.
- **rafael.barreto@blip.ai** → Desenvolver relatórios para otimizar o tempo das reuniões (visões assíncronas).

**Próximos passos:**
- Realizar sessão de brainstorming na próxima quarta-feira para definir o plano de execução e priorizar funcionalidades do projeto.
- Validar a arquitetura técnica com a equipe de plataforma.
- Estabelecer encontro semanal para a equipe.
- Implementar fóruns quinzenais de status report para alinhamento contínuo entre as frentes de agentes (QA, Insight, Gênios).
- Buscar apoio adicional com a liderança para reforçar o time de engenharia, se necessário, após a consolidação da execução.
**Produtos Blip mencionados:** Blip Docs

---

## [ID: 20260528-weekly-interno] Definição da estratégia de MVP com Gemini e Google Drive e planejamento de arquitetura robusta para o Genius PS.
**Tipo:** reunion | **Data:** 2026-05-28 | **Área:** engenharia, ops, dados, cs | **Ritual:** weekly
**Participantes:** Rafael Barreto, Vania Rodenas, Euleno Sousa, Luis Motta, Joao Figueiredo, Willer Batista, Vinicius Bandeira
**Tags:** mvp, googledrive, gemini, arquitetura, bancovetorial, tokens, governanca, gcp, azuredevops, slack, ia, llm, rag, qa, insightagents, frontend, backend, autenticacao, documentacao, planejamento

**Resumo:** A reunião definiu a estratégia do Produto Mínimo Viável (MVP) para o Genius PS, priorizando a integração com Gemini e Google Drive para testar a viabilidade em 30 dias. Paralelamente, foi acordado o planejamento e desenvolvimento de uma solução robusta com banco vetorial, com discussões sobre desafios técnicos, governança de dados e alocação de tarefas.

**Decisões tomadas:**
- Priorizar o desenvolvimento de um MVP utilizando Gemini e Google Drive para testar a viabilidade do produto.
- Acordar o desenvolvimento paralelo de uma solução robusta com banco vetorial para garantir performance e escalabilidade a longo prazo.
- Definir o prazo de 30 dias para a entrega do MVP funcional.
- Estabelecer uma governança rígida para a estruturação e manutenção dos documentos no Google Drive.
- Realizar uma reunião técnica focada para alinhar o cronograma estruturante e os passos para as duas frentes do projeto.

**Action items:**
- **joao.figueiredo@blip.ai** → Estruturar a arquitetura do Google Drive para categorizar os documentos necessários para o projeto.
- **rafael.barreto@blip.ai** → Coletar os documentos necessários com as gerências pertinentes para o preenchimento da estrutura do Drive.
- **['willer.batista@blip.ai', 'euleno.sousa@blip.ai', 'vania.rodenas@blip.ai']** → Planejar a solução robusta, definindo cronograma e passos técnicos para a solução de IA escalável utilizando Google Cloud Platform.
- **luis.motta@blip.ai** → Desenvolver a interface de usuário (front end) para a solução simplificada.
- **['euleno.sousa@blip.ai', 'vania.rodenas@blip.ai']** → Planejar a estratégia de gerenciamento de banco de dados, incluindo autenticação e controle de sessão.
- **The group** → Realizar uma reunião técnica para alinhar o cronograma estruturante e os passos para as duas frentes do projeto. (prazo: próxima terça-feira)
- **rafael.barreto@blip.ai** → Integrar o Slack com o Azure DevOps para automatizar a criação e o acompanhamento das tarefas do projeto.
- **rafael.barreto@blip.ai** → Conectar-se com Alan para alinhar as necessidades de documentos para os Insight Agents.

**Próximos passos:**
- Realizar uma reunião técnica focada na parte técnica para tangibilizar o cronograma e os passos de implementação até a próxima terça-feira.
- Próxima atualização de progresso sobre o avanço do cronograma até terça-feira, dia 2.
**Produtos Blip mencionados:** Brain, Insight Agents, QA

---

## [ID: 20260601-weekly-interno] Discussão da infraestrutura técnica e definição do MVP como base de conhecimento centralizada para o projeto Genius PS.
**Tipo:** reunion | **Data:** 2026-06-01 | **Área:** cs, engenharia, ops | **Ritual:** weekly
**Participantes:** Rafael Barreto, Vania Rodenas, Euleno Sousa, Luis Motta, Joao Figueiredo, Willer Batista, Vinicius Bandeira
**Tags:** infraestrutura, arquitetura, mvp, googledrive, ia, python, api, backend, frontend, poc, antigraft, miro, rag, gemini, professionalservices, designconversacional, delivery

**Resumo:** A reunião focou na discussão da infraestrutura técnica e na definição do MVP para o projeto Genius PS como uma base de conhecimento centralizada. Decidiu-se abandonar o EA Studio em favor de uma aplicação externa personalizada, utilizando Python e APIs para integrar a inteligência artificial com permissões de pastas do Google Drive. O MVP visa consolidar o Genius como uma base de conhecimento confiável, com validação através de uma demonstração executiva em 20 dias.

**Decisões tomadas:**
- Abandonar o EA Studio em favor de uma aplicação externa personalizada para garantir maior controle sobre o sistema.
- Armazenar metadados simples no Google Drive, evitando o processamento pesado de arquivos complexos como vídeos e ZIPs.
- Implementar controle de acesso através da autenticação Google, lendo as permissões de pasta do usuário para a Inteligência Artificial.
- Focar o MVP em consolidar o Genius como uma base de conhecimento confiável, atuando como um "segundo cérebro".
- Realizar uma demonstração executiva do MVP em até 20 dias, simulando o fluxo operacional para apresentar o valor da ferramenta.
- Utilizar o próprio projeto Genius como piloto para validar a estrutura proposta e a viabilidade técnica.
- **** → 
- Focar inicialmente nas personas de "Insight Agents" (Design Conversacional) e "Delivery" para validar a solução.
- Estabelecer o Genius como a fonte única de verdade para a área de Professional Services.
- Utilizar a plataforma Miro para centralizar links e rascunhos de design da interface.

**Action items:**
- **rafael.barreto@blip.ai** → Solicitar ao desenvolvedor Marcio a criação de 2 máquinas virtuais, uma dedicada ao front end e outra ao back end.
- **rafael.barreto@blip.ai** → Conversar com Vinicius sobre a necessidade de alocar um desenvolvedor para realizar uma consultoria de arquitetura no projeto.
- **willer.batista@blip.ai** → Desenvolver a estrutura de prova de conceito (PoC) baseada no documento de referência utilizando softwares gratuitos para validação.
- **luis.motta@blip.ai** → Realizar testes com a ferramenta Antigraft e focar no desenvolvimento da interface front end para a demonstração do Genius.
- **luis.motta@blip.ai** → Organizar os links no Miro para facilitar o acesso e a organização da equipe.
- **luis.motta@blip.ai** → Desenhar a interface e a estrutura navegável do projeto para refletir a realidade do produto.
- **['luis.motta@blip.ai', 'joao.figueiredo@blip.ai']** → Criar um rascunho da estrutura navegável do site para validar o melhor caminho para a versão 1.
- **rafael.barreto@blip.ai** → Enviar as anotações da reunião da última quinta-feira para Luis Motta via canal de mensagens.
- **joao.figueiredo@blip.ai** → Apresentar a arquitetura proposta e a estrutura de pastas para Marcio durante a reunião diária.

**Próximos passos:**
- Realizar uma demonstração executiva do MVP em até 20 dias.
- Continuar a concepção do produto final, que utilizará bancos de dados vetoriais e RAG (Retrieval-Augmented Generation) para maior robustez, substituindo a dependência do Google Drive a longo prazo.
- João Figueiredo alinhar a arquitetura desenhada e os requisitos técnicos com Márcio em reuniões diárias.

---

## [ID: 20260612-weekly-ginius] Alinhamento do projeto Ginius, definindo roteiro de entregas de 30 e 90 dias e resolução de desafios técnicos.
**Tipo:** reunion | **Data:** 2026-06-12 | **Cliente:** ginius | **Área:** ops, engenharia, dados | **Ritual:** weekly
**Participantes:** Marcio, Lari, Rafael Barreto, Eduardo, Vania Rodenas, Euleno Sousa, Daniel Alves, Luis Motta, Joao Figueiredo, Bia, Willer Batista, Vinicius Bandeira
**Tags:** ginius, mvp, roadmap, googlecloudplatform, gcp, terraform, ingestaodedados, googledrive, airflow, cloudrun, bigquery, googlecloudstorage, rag, servicedesign, figma, backend, frontend, infraestrutura, monitoramento, dataplex, databricks, vpn, blipinternal

**Resumo:** A reunião semanal do projeto Ginius alinhou o roteiro de entregas para 30 e 90 dias, focando na estratégia de MVP e na arquitetura ideal no Google Cloud Platform. Foram discutidos desafios técnicos de infraestrutura, ingestão de dados e o cronograma de lançamento do MVP para 13 de julho.

**Decisões tomadas:**
- O lançamento do Mínimo Produto Viável (MVP) foi decidido para 13 de julho.
- A estratégia do MVP equilibrará soluções rápidas com o desenvolvimento da arquitetura ideal no Google Cloud Platform.
- A ingestão de dados priorizará o Google Cloud Storage.
- A estrutura de pastas para o projeto foi validada pela equipe.
- Foi decidido agendar uma reunião com Márcio na segunda-feira para validar o plano de backend e alinhar os esforços do roadmap.

**Action items:**
- **daniel.alves@blip.ai** → Enviar a transcrição da reunião do Flow para Rafael.
- **rafael.barreto@blip.ai** → Criar cartões no sistema de gestão com todos os pontos pendentes discutidos.
- **daniel.alves@blip.ai** → Adicionar comentários e informações detalhadas nos cartões criados pelo Rafael.
- **daniel.alves@blip.ai** → Fornecer prazos e expectativas macro sobre os itens do projeto via Slack.
- **daniel.alves@blip.ai** → Corrigir o repositório de Terraform para restabelecer a sincronização da infraestrutura. (prazo: imediato)
- **daniel.alves@blip.ai** → Realizar o provisionamento do ambiente após o desbloqueio da esteira de Terraform.
- **daniel.alves@blip.ai** → Contatar Google para discutir orientações iniciais sobre agentes com a equipe do Google. (prazo: próxima terça-feira)
- **luis.motta@blip.ai** → Avaliar se é possível dispensar o desenvolvimento de um frontend para o MVP do Drive ou iniciar a construção caso seja necessário.
- **rafael.barreto@blip.ai** → Realizar a curadoria dos materiais de Service Design (SD) para o projeto.
- **willer.batista@blip.ai** → Determinar o processo de gestão de Figma e realizar a curadoria dos materiais de Figma.
- **joao.figueiredo@blip.ai** → Realizar a curadoria dos materiais de Service Design (SD), solicitando ajuda de Bia e Lari conforme necessário.
- **marcio@blip.ai** → Realizar pesquisa inicial sobre a viabilidade técnica e requisitos do backend para o projeto.
- **joao.figueiredo@blip.ai** → Organizar uma reunião durante a daily de segunda-feira com Márcio e Rafa para apresentar e validar a proposta do cronograma de trabalho. (prazo: próxima segunda-feira)

**Próximos passos:**
- Reunião com Márcio e Rafa na daily de segunda-feira para validar o plano de backend e o cronograma.
- Contato com a equipe do Google na próxima terça-feira para discutir orientações sobre agentes.
- Daniel Alves continuará detalhando o cronograma para garantir a administração das prioridades.
- Vinícius Bandeira reportará o progresso do cronograma de 30 e 90 dias ao Eduardo na segunda-feira.
**Produtos Blip mencionados:** Genius PS

---

## [ID: 20260615-weekly-genius] Equipe valida cronograma do MVP do Google Drive e define estratégias para desenvolvimento e interface do Genius PS.
**Tipo:** reunion | **Data:** 2026-06-15 | **Área:** engenharia, ops, dados | **Ritual:** weekly
**Participantes:** Rafael Barreto, Vania Rodenas, Euleno Sousa, Daniel Alves, Marcio Curvello, Luis Motta, Joao Figueiredo, Willer Batista, Vinicius Bandeira
**Tags:** googledrive, mvp, frontend, backend, metadados, ingestao, cronograma, golive, figma, gemini, mcp

**Resumo:** A equipe validou o cronograma do MVP do Google Drive, formalizou a fase de Discovery, e decidiu priorizar o desenvolvimento de uma interface dedicada para o produto Genius, com foco no lançamento beta até 13 de julho.

**Decisões tomadas:**
- Formalização da fase de Discovery para documentar esforços prévios de criação e estruturação do Drive.
- Priorização do desenvolvimento de uma interface dedicada (frontend) para garantir uma experiência de produto diferenciada.
- Atribuição da tarefa de desenvolver a interface (frontend) a Luis Motta (Motinha).
- Decisão de trabalhar em um ciclo de interação onde a curadoria de materiais específicos precede e é seguida pela ingestão e classificação de metadados.
- Lançamento em versão beta para um público selecionado, incluindo lideranças e clientes prioritários como o Mercado Pago, até 13 de julho.
- Documentação do projeto será realizada paralelamente, com Luis Motta responsável pelo frontend e Marcio Curvello, João Figueiredo e Euleno Sousa pela parte estrutural.
- Atualização do cronograma para incluir a fase de Discovery e ajustar o início da classificação de metadados para 22 de julho.

**Action items:**
- **rafael.barreto@blip.ai** → Monitorar chamado para verificar o status do chamado aberto para listar os proprietários de drives.
- **joao.figueiredo@blip.ai** → Planejar metadados e definir o processo de classificação dos metadados dos arquivos.
- **joao.figueiredo@blip.ai** → Buscar auxílio de Euleno Sousa para a definição dos processos de metadados.
- **rafael.barreto@blip.ai** → Cobrar Willer Alberto Batista sobre o andamento da ingestão do Figma.
- **marcio.curvello@blip.ai** → Realizar pesquisa pré-desenvolvimento e obter acessos necessários para a API do Drive.
- **luis.motta@blip.ai** → Criar a interface visual (frontend) para o projeto.
- **marcio.curvello@blip.ai, luis.motta@blip.ai** → Realizar alinhamento entre as expectativas do backend e do frontend. (prazo: após 2026-07-19)
- **O grupo** → Mapear habilidades e identificar perguntas chaves para treinar as capacidades do agente.
- **marcio.curvello@blip.ai** → Realizar alinhamento da linha 28 com a equipe. (prazo: a partir da próxima segunda-feira)
- **vinicius.bandeira@blip.ai** → Planejar o cronograma de Go Live, incluindo estratégias de comunicação para as lideranças e as partes interessadas.
- **vinicius.bandeira@blip.ai** → Realizar a demonstração do projeto e comunicar a disponibilização da primeira versão para os testadores definidos. (prazo: 2026-07-13)
- **luis.motta@blip.ai** → Documentar a parte de frontend do projeto.
- **marcio.curvello@blip.ai, joao.figueiredo@blip.ai, euleno.sousa@blip.ai** → Documentar a parte estrutural do projeto.
- **marcio.curvello@blip.ai** → Conectar o Genius aos agentes (DC, Inside e Brain) utilizando módulos MCP.
- **joao.figueiredo@blip.ai** → Pesquisar e desenvolver o processo de classificação de metadados e definição de banco de dados para a ingestão de arquivos.
- **rafael.barreto@blip.ai** → Obter os dados do chamado de criação e estruturação do drive para preencher as datas de conclusão no cronograma.
- **marcio.curvello@blip.ai** → Avaliar a necessidade de persistência de dados (banco de dados) durante a etapa de pesquisa pré-desenvolvimento.

**Próximos passos:**
- Reunião de alinhamento entre Luis Motta, Marcio Curvello e Daniel Alves após o dia 19 de julho.
- Revisão dos próximos passos e do plano para o projeto de 90 dias na reunião agendada para a próxima quinta-feira.
**Produtos Blip mencionados:** Genius, Model Context Protocol (MCP), DC, Insight, Brain

---

## [ID: 20260618-weekly-interno] Reunião semanal sobre estratégias de infraestrutura, governança de custos e desenvolvimento do MVP1 do Genius PS.
**Tipo:** reunion | **Data:** 2026-06-18 | **Área:** engenharia, ops, dados, cs | **Ritual:** weekly
**Participantes:** Rafael Barreto, Bella Trindade, Vania Rodenas, Euleno Sousa, Daniel Alves, Marcio Curvello, Luis Motta, Joao Figueiredo, Willer Batista, Vinicius Bandeira
**Tags:** infraestrutura, governancadecustos, mvp1, googlecloudplatform, bigquery, inteligenciaartificial, metadados, servicedesign, testesa/b, api, gemini

**Resumo:** A reunião definiu estratégias de infraestrutura, governança de custos e o desenvolvimento do Produto Mínimo Viável 1 (MVP1) do Genius PS. Problemas de infraestrutura no GCP foram resolvidos, e o design do MVP1 prioriza usabilidade simples e transparência das fontes documentais, com classificação de metadados avançando com IA. A decisão principal foi manter o desenvolvimento próprio do MVP1 para autonomia, avaliando futura integração com o sistema Brain.

**Decisões tomadas:**
- Problemas de infraestrutura no Google Cloud Platform foram resolvidos.
- O controle de custos tornou-se prioridade devido aos riscos de performance.
- A implementação de alertas de custo é essencial.
- O design do Produto Mínimo Viável 1 prioriza a usabilidade simples e a transparência das fontes documentais.
- A classificação de metadados avança com protótipos usando Inteligência Artificial.
- Manter o desenvolvimento próprio do Produto Mínimo Viável 1 para garantir autonomia.
- Testes comparativos avaliarão a integração com o sistema Brain futuramente.
- O MVP1 manterá funcionalidades simples, evitando gerenciamento complexo de sessões, mas garantindo que a IA indique claramente as fontes dos documentos consultados.
- O prazo para a entrega do MVP1 está definido para o dia 13.
- A estratégia definida é manter o desenvolvimento do MVP próprio para garantir flexibilidade e autonomia, enquanto se avalia a integração com o Brain.

**Action items:**
- **daniel.alves@blip.ai** → Provisionar a infraestrutura necessária e realizar a subida do pull request para viabilizar testes no ambiente.
- **daniel.alves@blip.ai** → Configurar o alerta de custos do ambiente e alinhar o nível de gastos aceitável com a equipe.
- **joao.figueiredo@blip.ai** → Enviar o link do mural para a Bela e liberar o acesso à arquitetura do drive.
- **joao.figueiredo@blip.ai** → Criar um script para classificação de metadados utilizando inteligência artificial e apresentar o protótipo na próxima reunião.
- **rafael.barreto@blip.ai** → Entrar em contato com o Márcio para confirmar se ele obteve os acessos necessários para o desenvolvimento.
- **bella.trindade@blip.ai** → Analisar a viabilidade técnica da integração do projeto com o Brain junto com a Ju e trazer um retorno na próxima reunião.
- **rafael.barreto@blip.ai** → Escalar o chamado de suporte técnico pendente referente à liberação da chave de API do Gemini para o ambiente de produção.
- **vinicius.bandeira@blip.ai** → Realizar um teste AB comparando o desempenho com e sem o Brain e com e sem a interface proprietária para avaliar a eficácia e a flexibilidade.
- **O grupo** → Desenvolver um produto proprietário inicial para garantir flexibilidade e manutenção independente enquanto se avalia a integração com o Brain.

**Próximos passos:**
- João Figueiredo apresentará um script para classificação de metadados utilizando IA na próxima segunda-feira.
- João Figueiredo apresentará o protótipo funcional para a classificação de metadados na próxima segunda-feira.
- Bella Trindade coordenará com seu time a avaliação técnica para verificar a viabilidade de integrar o Brain à solução, trazendo um retorno sobre essa possibilidade na próxima reunião.
- Bella Trindade conduzirá descobertas técnicas nos próximos dois dias para decidir qual modelo de linguagem utilizar.
- Avaliar a possibilidade futura de monetização de conectores caso a integração com o Brain seja adotada.
**Produtos Blip mencionados:** Genius PS

---

## [ID: 20260622-weekly-interno] Reunião semanal do Genius PS para definir estrutura de tarefas de backend e avaliar progresso técnico.
**Tipo:** reunion | **Data:** 2026-06-22 | **Área:** engenharia, dados, ops | **Ritual:** weekly
**Participantes:** Rafael Barreto, Bella Trindade, Vania Rodenas, Euleno Sousa, Daniel Alves, Marcio Curvello, Luis Motta, Joao Figueiredo, Willer Batista, Vinicius Bandeira
**Tags:** backend, frontend, ia, metadados, classificacao, python, googledrive, figma, conectores, cronograma, desenvolvimento

**Resumo:** A reunião definiu a estrutura de tarefas do back-end e avaliou o progresso técnico do projeto. As tarefas de desenvolvimento foram divididas em unidades menores e houve discussões sobre classificação de metadados, interface conversacional e avaliação de ferramentas de IA e conectores.

**Decisões tomadas:**
- Marcio Curvello criará tarefas menores para o desenvolvimento do backend, baseadas em estimativas de 80 horas, para melhor gestão do cronograma.
- Os membros concordaram em enviar os links dos arquivos para João Figueiredo para que ele realize o processamento local de classificação de metadados.

**Action items:**
- **marcio.curvello@blip.ai** → Ajustar a quantidade de horas e a estrutura das tarefas do backend no cronograma.
- **marcio.curvello@blip.ai** → Realizar a reunião de 30 minutos de contexto com Daniel e Motta sobre o plano de 90 dias.
- **marcio.curvello@blip.ai** → Conversar com GRZ sobre o início do desenvolvimento do backend para não restringir o prazo.
- **joao.figueiredo@blip.ai** → Trabalhar nas melhorias do script Python de classificação de metadados para torná-lo mais robusto.
- **rafael.barreto@blip.ai** → Encaminhar os links das pastas do Google Drive para que a classificação dos arquivos seja realizada.
- **luis.motta@blip.ai** → Concluir a descrição funcional e a ideação detalhada de cada tela do front end.
- **bella.trindade@blip.ai** → Verificar com Ju o status técnico dos conectores no Brain e reportar na próxima reunião.
- **rafael.barreto@blip.ai** → Conversar com Willer sobre o progresso dos testes de conversão de design no Figma.

**Próximos passos:**
- Marcio Curvello agendou uma reunião de alinhamento com Daniel e Luis Motta para tratar do plano de backend de 90 dias.
- Marcio Curvello planeja discutir com a equipe de GRZ sobre o início do desenvolvimento de backend para otimizar o prazo de entrega do MVP 1.
- A confirmação sobre o escopo dos conectores (Google Drive ou outras APIs externas) será esclarecida em reuniões futuras.
**Produtos Blip mencionados:** Brain

---

## [ID: 20240625-figma-claro-tv] Suporte técnico Claro TV
**Tipo:** figma | **Data:** 2026-06-25 | **Cliente:** Claro TV | **Área:** dc
**Tags:** figma, jornada, suporte, claro-tv, telecom, atendimento

**Resumo:** Este fluxo detalha a jornada conversacional para o suporte técnico da Claro TV, abrangendo desde problemas de sinal e canais até questões de equipamentos e recarga, com opções de autoatendimento e direcionamento para atendimento humano.

**Validações backend:**
- Validação de código de erro (entre 700 e 999) para direcionamento de solução.
- Verificação de elegibilidade para troca de equipamento/controle remoto.
- Verificação de pacote de canais e pagamentos pendentes.
- Verificação de status de recarga.

**Tratamento de exceções:**
- Erro de código não reconhecido na tela direciona para agendamento de visita técnica ou pergunta de resolução.
- Problemas persistentes após autoatendimento direcionam para atendimento humano ou agendamento de visita técnica.

**Transições de flow:**
- Falar com atendente (implica transferência para atendimento humano)

---

## [ID: 20240730-figma-netempresas] Menu Suporte Técnico NET e Empresas
**Tipo:** figma | **Data:** 2024-07-30 | **Cliente:** net-e-empresas | **Área:** dc
**Tags:** figma, jornada, menu, suporte, net, empresas, telecom

**Resumo:** Este fluxo descreve o menu principal de suporte técnico para clientes NET e Empresas, permitindo a seleção de diferentes categorias de suporte e direcionando para serviços específicos como mudança de endereço, com tratamento para inputs inesperados.

**Tratamento de exceções:**
- O bloco `InputInesperado` trata entradas do usuário que não correspondem às opções esperadas, retornando ao bloco `EscolherServico` para uma nova tentativa.

**Transições de flow:**
- Transição para sub-fluxo de Suporte & inaent.
- Transição para sub-fluxo de Suporte a TV.
- Transição para sub-fluxo de Suporte telefone fixo.
- Transição para sub-fluxo de Menu suporte net Empresas.
- Transição para sub-fluxo de Mudança de endereço.

---

## [ID: 20240730-figma-interno] [P] Peer Nomination
**Tipo:** figma | **Data:** 2024-07-30 | **Área:** dc
**Tags:** figma, jornada, peer-nomination, rh, avaliação, engajamento

**Resumo:** Este fluxo permite que um usuário indique um colega de trabalho, fornecendo o nome do indicado e o motivo da nomeação, com validações para evitar indicações duplicadas e garantir a precisão dos dados.

**Validações backend:**
- **** → 
- **** → 

**Tratamento de exceções:**
- Se o usuário já nomeou a pessoa, ele é direcionado para indicar outra pessoa.
- Se o usuário já nomeou o par específico, ele é direcionado para indicar outra pessoa.
- Se o nome da pessoa indicada não for confirmado, o fluxo retorna para a etapa de solicitação do nome.
- Se o motivo da indicação não for confirmado, o fluxo retorna para a etapa de solicitação do motivo.