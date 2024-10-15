Desafio de Modelagem dimensional

#### Objetivo:
Este desafio tem como propósito a construção de um **modelo estrela** para análise de dados. O foco é criar um modelo dimensional robusto que permita a análise eficiente de dados, estruturado por meio de uma tabela de fatos e tabelas de dimensões. Não será necessário incluir dados de alunos.

#### Tarefas a serem realizadas:
1. **Criação da Tabela Fato**:  
   A tabela fato deve conter os dados centrais para a análise, como métricas e medições pertinentes ao contexto. Ela será a base do modelo, agregando informações relevantes.

2. **Criação das Tabelas de Dimensão**:  
   Essas tabelas são responsáveis por fornecer informações contextuais para a tabela fato. Devem conter detalhes específicos que permitem a análise detalhada dos dados. Exemplo de possíveis dimensões:
   - Cursos ministrados
   - Departamento
   - Outros dados relevantes

3. **Adição de Tabela de Dimensão de Datas**:  
   Inclua uma tabela de dimensão para as datas. Caso os dados relacionais não tenham informações detalhadas de datas, crie manualmente uma tabela que contenha os campos de data necessários para o modelo.

#### Exemplo de uso das datas:
Datas de oferta de cursos, datas de início e fim de disciplinas, etc. O formato da tabela de datas pode variar conforme a granularidade desejada.

#### Observações:
- A granularidade dos dados não está fixa, portanto, diferentes níveis de detalhe podem ser usados conforme o objetivo da análise.
