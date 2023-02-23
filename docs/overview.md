# Visão Geral

## Lições

### [Usando Ontologias e Termos de Ontologia](lesson/ontology-term-use.md)

- Destinado a [certos papéis](getting-started.md#oboroles): Curadores de banco de dados
- Habilidades:
  - saber para que servem as ontologias
  - encontrar boas ontologias: repositórios de ontologias, OBO
  - encontrar bons termos: navegadores de ontologia
  - avaliar para uso: licença, qualidade
  - mapear termos locais para termos de ontologia
  - identificar termos faltantes
  - usar IRIs, prefixos, CURIEs, rótulos
  - usar Protege?

### [Contribuindo para as ontologias OBO 1: Protege e Github](lesson/contributing-to-obo-ontologies.md)

- Destinado a [certos papéis](getting-started.md#oboroles): Curadores de banco de dados, Curador de Ontologia, Engenheiro / Desenvolvedor de Ontologia
- Constrói sobre:
  - [Usando Ontologias e Termos de Ontologia](lesson/ontology-term-use.md)
- Habilidades:
  - usar o GitHub: issues, Pull Requests
  - entender a etiqueta básica do Open Source
    - ler READMEs
  - entender noções básicas de fluxos de desenvolvimento de ontologia
  - entender os padrões de design de ontologia
  - usar modelos: ROBOT, DOS-DP
  - noções básicas de OWL

### [Fundamentos de Ontologia](lesson/ontology-fundamentals.md)

- Destinado a [certos papéis](getting-started.md#oboroles): Curadores de Ontologia, Engenheiro / Desenvolvedor de Ontologia
- Constrói sobre:
  - [Usando Ontologias e Termos de Ontologia](lesson/ontology-term-use.md)
- Habilidades:
  - RDF
  - RDFS
  - OWL
  - Reasoners
  - SPARQL básico
  - Turtle, JSON-LD

### Análise de Dados Vinculados

- Destinado a [papéis](getting-started.md#oboroles): Curadores de Ontologia, Engenheiro / Desenvolvedor de Software (Semântico)
- Constrói sobre:
  - [Fundamentos de Ontologia](lesson/ontology-fundamentals.md)
- Habilidades:
  - SPARQL avançado
  - Enriquecimento de termos
  - Similaridade semântica
  - Reconhecimento de Entidades Nomeadas
  - mais...

### Desenvolvimento de Ontologia

- Baseia-se em:
  - [Fundamentos de Ontologia](lesson/ontology-fundamentals.md)
  - [Contribuindo para ontologias OBO](lesson/contributing-to-obo-ontologies.md)
- Habilidades:
  - Gerenciar o GitHub
  - Gerenciar a importação de ontologias
  - Usar a ferramenta ROBOT para extrair informações: MIREOT, SLME
  - Usar o relatório ROBOT
  - Realizar a poda de árvores

### Bancos de Dados Semânticos

- Baseia-se em:
  - Desenvolvimento de Ontologia
- Habilidades:
  - Mapeamento avançado de termos
  - Termos de ontologia em SQL
  - JOINs de tabelas de terminologia, restrições
  - Converter tabelas em triplas
  - Armazenamento de triplas
  - Grafos de conhecimento

### [Automação de Fluxos de Trabalho de Desenvolvimento de Ontologia](lesson/automating-ontology-workflows.md)

- Baseia-se em:
  - Desenvolvimento de Ontologia
  - Pipelines de Ontologia
- Habilidades:
  - Unix shell
  - `make`
  - Git e GitHub avançados
  - ROBOT
  - ODK

### [Desenvolvendo uma Ontologia de Referência OBO](lesson/developing-an-obo-ontology.md)

- Baseia-se em:
  - Automação de Desenvolvimento de Ontologia
- Habilidades:
  - Conhecimento detalhado dos princípios e melhores práticas da OBO
  - Usar o Painel de Controle OBO
  - Usar o Registro OBO
  - Usar o sistema PURL

## Tutoriais

- [Tutorial ROBOT 1: Conversão, Extração e Modelo](tutorial/robot-tutorial-1.md)
- [Tutorial ROBOT 2: Anotação, Fusão, Raciocínio e Diferença](tutorial/robot-tutorial-2.md)
- [Introdução ao GitHub](tutorial/github-fundamentals.md)
- [Introdução à gestão e rastreamento de problemas no GitHub](tutorial/github-issues.md)

## Guias de Como Fazer

- [Instalar Elk 0.5 no Protege](howto/installing-elk-in-protege.md)
- [Configuração do Docker e do Ontology Development Kit](howto/odk-setup.md)
