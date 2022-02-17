# Feedbacks diários

Trata-se de uma automação de processo muito útil para empresas que têm em sua organização equipes e necessidade de feedbacks constantes aos seus funcionários, como atendimento ao cliente, por exemplo.

As ferramentas que utilizei para a criação desse projeto são o Google Colab (notebook que reproduz a linguagem python) e o Google Sheets, as famosas planilhas.

A ideia central é ter uma planilha que informe aos usuários - no caso os supervisores, team leaders, coordenadores, etc. - um resumo com os principais acontecimentos diários de uma operação, especificando o funcionário, o fato relacionado a este funcionário, e o gestor direto desse mesmo funcionário (o responsável por aplicar feedbacks a ele).

São utilizados arquivos em formato csv e excel (formatos fornecidos pela empresa). O primeiro deles é o "actions_done.csv", que traz informações detalhadas de cada atendimento, como hora de início, hora em que foi finalizado, identificação do atendimento (source_id), agente que realizou o atendimento, etc.

O segundo é o "csat.csv", bem semelhante ao primeiro arquivo, porém com uma coluna que indica qual nota o cliente deu para seu atendimento.

Além desses dois tem também o "Resultados.csv", que traz os indicadores diários de cada agente.

Por último, há o "Dimensionamento.xlsx", que traz a divisão das equipes dentro da empresa, para este projeto em específico, os campos utilizados são o nome do funcionário e o seu gestor direto.

Após carregar os arquivos no Colab, basta executar, incluindo o código de autorização para manipulação de planilhas no Drive do Google. Após isso, é requisitado o dia desejado do relatório (aaaa-mm-dd).

No nosso caso, a planilha de feedbacks é então atualizada, bem como outras 5 planilhas auxiliares, num total de 15 abas, com mais detalhes de cada fato. São elas: 

- CSAT (Avaliação do cliente)

- Skip/Transfer

- Produtividade

- Hora a hora

- Métricas diárias

Caso deseje saber a lógica por trás de cada uma delas, vou deixar os links com mais detalhes aqui na descrição.

Os fatos relevantes podem ser determinados pela empresa e, com alguns ajustes, serem adaptados para suas necessidades.
