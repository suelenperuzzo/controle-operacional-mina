# Controle Operacional de Mina

> Ferramenta de controle de efetivo para operação de mineração — o espelho diário de quem está trabalhando, em qual equipamento, em qual área, e onde falta mão de obra.

---

## O problema

Uma operação de mina precisa rodar todos os dias para produzir e entregar as metas acordadas com o cliente. Para isso, é preciso ter total controle sobre o efetivo: as pessoas, os equipamentos e as áreas de atuação.

A operação envolve uma frota diversa — caminhões, comboios, pipas e equipamentos de linha amarela (máquinas) — além das diferentes frentes de trabalho e do dimensionamento exigido pelo cliente. Antes de existir uma ferramenta central, faltava uma visão clara e diária de:

- Quem está trabalhando em cada equipamento e em cada área
- Quem está presente e quem está ausente a cada dia
- Onde há falta de mão de obra
- Como as demandas de RH (admissões, demissões, substituições, aumento de quadro e férias) impactam o efetivo disponível

Sem essa visão consolidada, os problemas do dia a dia da operação só apareciam tarde demais — quando já estavam afetando a produção.

## O que a ferramenta faz

O **Controle Operacional de Mina** é o espelho do que acontece diariamente na operação. Ela reúne, num só lugar, o controle completo do efetivo e permite agir rapidamente sobre os problemas identificados.

Principais funções:

- **Controle de efetivo diário:** mostra quem está trabalhando em cada equipamento, em cada área, a cada dia — e quem está ausente.
- **Identificação de falhas de cobertura:** aponta onde falta mão de obra, permitindo agir antes que a produção seja afetada.
- **Controle de RH integrado:** acompanha admissões, aprovação de demissões, substituições, aumento de quadro e férias, conectando as demandas de pessoal ao efetivo real da operação.
- **Reportes da operação:** líderes das frentes e instrutores registram diretamente na ferramenta quando algo não está conforme, alimentando o controle com informação de campo em tempo real.
- **Visão para toda a hierarquia:** consolida os dados para que cada nível da empresa acompanhe a operação a partir da sua ótica.

## Como funciona

A ferramenta é um painel operacional interativo (dashboard) que roda no navegador. Ela recebe informação de múltiplos usuários — os reportes preenchidos pelos líderes e instrutores — processa e consolida os dados, e devolve uma visão atualizada e visual do efetivo da operação, com gráficos e filtros.

O fluxo é, em resumo:

1. Os dados de efetivo, equipamentos e áreas são mantidos e atualizados.
2. Líderes e instrutores registram reportes quando identificam algo fora do conforme.
3. A ferramenta consolida tudo e apresenta a visão diária da operação.
4. A gestão atua sobre os problemas identificados para mantê-los sob controle.

## Impacto

O Controle Operacional de Mina se tornou uma ferramenta central da operação, utilizada por diversos níveis da empresa: RH, instrutores, encarregados, coordenadores, gerência e diretoria.

Seu valor foi reconhecido a ponto de motivar a empresa a investir na formação da autora em Engenharia de Software — um retorno concreto e mensurável a partir de uma iniciativa própria.

## Tecnologias utilizadas

**Frontend (o painel)**
- **HTML** — estrutura da aplicação
- **CSS** — design, layout e identidade visual do painel
- **JavaScript** — lógica de processamento de dados (filtros, agrupamentos e cálculos) e interatividade
- **Chart.js** — biblioteca de visualização de dados para os gráficos do painel

**Backend (os dados)**
- **Firebase / Cloud Firestore** — banco de dados na nuvem que armazena os registros do efetivo, organizados por coleções (etilometria diária, previsão de escala, prontidão diária), com histórico diário e registro de quem atualizou cada dado

**Publicação**
- **Netlify** — hospedagem da aplicação, que está publicada e acessível online

---

## Sobre este projeto

Este é o primeiro projeto do meu portfólio de Engenharia de Software. Nasceu de uma necessidade real de uma operação de mineração e vem evoluindo junto com a minha formação na área.

**Autora:** Suélen Peruzzo
