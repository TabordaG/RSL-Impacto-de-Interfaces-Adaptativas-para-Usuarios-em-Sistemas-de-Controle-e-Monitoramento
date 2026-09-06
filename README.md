# RSL — Impacto de Interfaces Adaptativas para Usuários em Sistemas de Controle e Monitoramento

Este repositório reúne os dados e documentos produzidos durante a condução de uma Revisão Sistemática da Literatura (RSL). Abaixo, a descrição de cada arquivo/pasta: o que ele é, quais informações contém e quando consultá-lo.

## Arquivos

### `Estudos Selecionados.xlsx`
Export completo do Parsifal com **979 registros**: todos os artigos retornados pela string de busca e pela busca manual, antes e depois da triagem.

Colunas: `bibtex_key`, `title`, `author`, `journal`, `year`, `source`, `pages`, `volume`, `abstract`, `document_type`, `doi`, `url`, `affiliation`, `author_keywords`, `keywords`, `publisher`, `issn`, `language`, `note`, `selection_criteria`, `created_at`, `updated_at`, `created_by`, `updated_by`, `status`, `comments`.

Colunas mais relevantes:
- `status`: `Accepted` / `Rejected` / `Duplicated`.
- `selection_criteria`: motivo predominante de inclusão ou exclusão atribuído a cada registro (ex.: "Estudos anteriores a 2016", "Fora do contexto de sistemas interativos relevantes").
- `source`: base de dados de origem (ACM Digital Library, IEEE Xplore, ScienceDirect, Scopus, SpringerLink, Manual).

**Consultar quando:** precisar de metadados (ano, base, autores, abstract) de qualquer um dos 979 registros, ou entender por que um artigo específico foi aceito/rejeitado.

### `Artigos Após Avaliação de Qualidade.xlsx`
Lista apenas com os **nomes dos artigos aprovados** na avaliação de qualidade (sem notas ou outras colunas).

**Consultar quando:** precisar saber rapidamente quais artigos compõem o corpus final.

### `Conducting · Impacto de interfaces adaptativas para usuários em sistemas de controle e monitoramento_ Uma Revisão Sistemática de Literatura.pdf`
Print de tela do Parsifal mostrando o *summary* da avaliação de qualidade: todos os artigos avaliados junto com a nota que cada um recebeu.

**Consultar quando:** precisar da nota de qualidade de um artigo específico, ou conferir o critério de corte aplicado.

### `Artigos/` (pasta)
PDFs dos estudos que compõem o corpus final (nota de qualidade acima do corte). É o conjunto de texto completo disponível para leitura integral.

**Consultar quando:** precisar do conteúdo completo de um artigo (não apenas metadados), para leitura, extração de dados ou codificação. Para identificar a qual artigo cada PDF corresponde, cruzar título/DOI com `Artigos Após Avaliação de Qualidade.xlsx` ou com a tabela de estudos do `Protocolo_RSL`.

### `Protocolo_RSL_Impacto_de_Interfaces_Adaptativas.pdf`
Relatório completo da RSL (protocolo + resultados): PICOC, questões de pesquisa, string de busca, critérios de inclusão/exclusão, checklist de qualidade (com o prompt usado no NotebookLM), fluxograma PRISMA, tabelas de distribuição por critério e por base de dados, e a tabela completa dos estudos do corpus final (base, autores, título, ano, nota, link).

**Consultar quando:** precisar de qualquer detalhe metodológico completo, ou conferir os números/critérios usados nas planilhas acima.

### `Poster_Impacto_de_Interfaces_Adaptativas...pdf`
Artigo em formato pôster, submetido e já avaliado no IHC 2026, com um resumo da pesquisa: introdução, metodologia resumida, resultados da seleção e conclusão.

**Consultar quando:** precisar de uma versão curta e já redigida da pesquisa, sem entrar nos detalhes completos do Protocolo.