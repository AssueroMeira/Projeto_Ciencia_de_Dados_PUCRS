# Projeto da disciplina: Ciência de Dados e Inteligência Artificial - PUCRS

## Fase 1

O objetivo deste trabalho é selecionar um conjunto de dados interessante, desenvolver um projeto inicial sobre ele com a ferramenta Orange Data Mining e identificar oportunidades em ciência de dados com ele. Para tanto, procurem algum conjunto de dados que vocês se sintam motivados a explorar. O conjunto selecionado deve ter pelo menos 1.000 linhas e pelo menos 10 colunas totalmente preenchidas (sem valores faltantes) e, principalmente, deve ter um atributo alvo, categórico ou numérico.

#### Enunciado:
1. Procurem um conjunto de dados com, pelo menos, 1.000 linhas e 10 colunas, e que tenha um atributo alvo categórico ou numérico.
2. Façam a carga no Orange Data Mining para ajudar na exploração.
3. Transcrevam a síntese do conjunto de dados como apresentado em sua origem.
4. Em até 3 parágrafos, expliquem o interesse em explorá-lo.
5. Sobre o conjunto de dados escolhido:
- Qual a finalidade do conjunto de dados?
- Quantas linhas e quantas colunas o conjunto de dados tem?
- Qual o formato que ele é disponibilizado? (CSV, JSON, XLSX, etc)

6. Escolham pelo menos 10 colunas totalmente preenchidas (as mais importantes) e, para cada coluna (inclusive para a coluna alvo):
- Qual o nome e o que representa?
- Qual o tipo de dados? Nominal/Ordinal/Numérico/Data e/ou hora?
- Quais são os valores considerados válidos?
- Quantos valores distintos aparecem na coluna?
- Qual o menor e o maior valor, e qual a moda?
- Os valores da coluna são numéricos? Qual a média e qual o desvio-padrão? Qual a mediana?

7. Qual a oportunidade para um projeto de ciência de dados foi identificada? Justificar a resposta!



8. O que você deve entregar nesta fase:  Documento em PDF/DOCX (desenvolvido a partir do modelo de template disponibilizado)  com a documentação de todas as atividades feitas e o link para o conjunto de dados escolhido. No caso de ter sido feito um recorte/amostragem do conjunto original, documentar quais foram os passos feitos para produzir o recorte.

## Fase 2

- Desenvolvam um processo de ciência de dados, cobrindo:

 - Exploração dos dados
 - Escolha dos algoritmos de aprendizado para a modelagem (pelo menos 3 algoritmos)
 - Preparação dos dados de acordo com as características dos algoritmos de aprendizado Escolhidos
 - Execução dos experimentos de aprendizado e coleta das métricas

- Relato dos experimentos e lições aprendidas.



O que você deve entregar nesta fase: – Documento em PDF/DOCX (desenvolvido a partir do modelo de template disponibilizado) , mais notebook do projeto (ipynb), com a documentação de todas as atividades feitas, e mais o conjunto de dados usado como entrada para o projeto. Salve esses arquivos em uma pasta zipada (.ZIP) para postar na Plataforma.

### Dataset: Students Performance Dataset:

**Link:** https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset

**Autor:** Rabie El Kharoua

**DOI:** 10.34740/kaggle/ds/5195702

### Índice
Os dados sobre os estudantes foram coletados considerando as categorias abaixo:

- Informações dos Estudantes
 - ID do Estudante
 - Detalhes Demográficos (idade, gênero, etnia, educação dos pais)
 - Hábitos de Estudo (tempo de estudo semanal, faltas e aulas de reforço)
- Envolvimento dos Pais (apoio dos pais)
- Atividades Extracurriculares (atividades extracurriculares, esportes, música e voluntariado)
- Desempenho Acadêmico (GPA)
- Variável Alvo: Classificação de Notas

### Dicionário do Conjunto de Dados (Por Coluna)

- **ID do Estudante:** Um identificador único atribuído a cada estudante.
- **Idade:** A idade dos estudantes varia de 15 a 18 anos.
- **Gênero:** Gênero dos estudantes, onde 0 representa Masculino e 1 representa Feminino.
- **Etnia:** A etnia dos estudantes, codificada da seguinte forma:
 - 0: Caucasiano;
 - 1: Afro-Americano;
 - 2: Asiático;
 - 3: Outro.
- **Educação dos Pais:** O nível de educação dos pais, codificado da seguinte forma:
 - 0: Nenhuma;
 - 1: Ensino Médio;
 - 2: Algum Ensino Superior;
 - 3: Bacharelado;
 - 4: Superior.
- **Tempo de Estudo Semanal:** Tempo de estudo semanal em horas, variando de 0 a 20.
- **Faltas:** Número de faltas durante o ano letivo, variando de 0 a 30.
- **Aulas de Reforço:** Status de aulas de reforço, onde 0 indica Não e 1 indica Sim.
- **Apoio dos Pais:** O nível de apoio dos pais, codificado da seguinte forma:
 - 0: Nenhum;
 - 1: Baixo;
 - 2: Moderado;
 - 3: Alto;
 - 4: Muito Alto.
- **Atividades Extracurriculares:** Participação em atividades extracurriculares, onde 0 indica Não e 1 indica Sim.
- **Esportes:** Participação em esportes, onde 0 indica Não e 1 indica Sim.
- **Música:** Participação em atividades musicais, onde 0 indica Não e 1 indica Sim.
- **Voluntariado:** Participação em voluntariado, onde 0 indica Não e 1 indica Sim.
- **GPA:** Média de Notas (Grade Point Average) em uma escala de 2,0 a 4,0, influenciada por hábitos de estudo, envolvimento dos pais e atividades extracurriculares.
- **Variável Alvo: Classificação de Notas**
- **Classificação de Notas:** Classificação das notas dos estudantes com base no GPA:
 - 0: 'A' (GPA >= 3,5);
 - 1: 'B' (3,0 <= GPA < 3,5);
 - 2: 'C' (2,5 <= GPA < 3,0);
 - 3: 'D' (2,0 <= GPA < 2,5);
 - 4: 'F' (GPA < 2,0).
