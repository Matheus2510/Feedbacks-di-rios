![Logo of the project](https://github.com/Matheus2510/Feedbacks_diarios/blob/main/folder/Feedback-Capa.jpg)
 
## Feedbacks Diários
 
Trata-se de uma automação de processo muito útil para empresas que têm em sua organização equipes e necessidade de feedbacks constantes aos seus funcionários, como atendimento ao cliente, por exemplo.

A ideia central é ter uma planilha que informe aos usuários - no caso os supervisores, team leaders, coordenadores, etc. - um resumo com os principais acontecimentos diários de uma operação, especificando o funcionário, o fato relacionado a este funcionário, e o gestor direto desse mesmo funcionário (o responsável por aplicar feedbacks a ele).

 
## Tecnologias

* Python versão 3.7.12
* Arquivos CSV
* Arquivos Excel (xlsx)


## Serviços utilizados
 
* Google Colab
* Google Sheets


## Como usar
 
São utilizados arquivos em formato csv e excel (formatos fornecidos pela empresa). O primeiro deles é o "actions_done.csv", que traz informações detalhadas de cada atendimento, como hora de início, hora em que foi finalizado, identificação do atendimento (source_id), agente que realizou o atendimento, etc.

![actions_done_1](https://github.com/Matheus2510/Feedbacks_diarios/blob/main/folder/actions_done_gif_1.gif) 

O segundo é o "csat.csv", bem semelhante ao primeiro arquivo, porém com uma coluna que indica qual nota o cliente deu para seu atendimento.

![csat_1](https://github.com/Matheus2510/Feedbacks_diarios/blob/main/folder/csat_gif_1.gif)

Além desses dois tem também o "Resultados.csv", que traz os indicadores diários de cada agente.

![Resultados](https://github.com/Matheus2510/Feedbacks_diarios/blob/main/folder/Feedbacks_diarios_img_resultados.png)

Por último, há o "Dimensionamento.xlsx", que traz a divisão das equipes dentro da empresa, para este projeto em específico, os campos utilizados são o nome do funcionário e o seu gestor direto.

![Dimensionamento_1](https://github.com/Matheus2510/Feedbacks_diarios/blob/main/folder/dimensionamento_gif_1.gif)


Após carregar os arquivos no Colab, basta executar, incluindo o código de autorização para manipulação de planilhas no Drive do Google. Após isso, é requisitado o dia desejado do relatório (aaaa-mm-dd)

![Em execucao_1](https://github.com/Matheus2510/Feedbacks_diarios/blob/main/folder/deploy_1.gif)
 
A planlha de feedbacks diários será atualizada com os dados do dia inserido, bem como outras XXXX sheets distribuídas em 5 worksheets, que servem de apoio aos feedbacks e contém detalhes de cada informação da worksheet de feedbacks diários.

![deploy_2](https://github.com/Matheus2510/Feedbacks_diarios/blob/main/folder/deploy_2.gif)

Na worksheet de feedbacks diários há ainda colunas referentes a justificativa e ação realizada em cima do fato destacado, com justificativas predefinidas (caso haja alguma, a coluna de ação será realçada de cinza escuro, pois não será necessária nenhuma ação). Há também uma coluna contendo os links para cada uma cad planilhas auxiliares.

![deploy_3](https://github.com/Matheus2510/Feedbacks_diarios/blob/main/folder/deploy_3.jpeg)


## Features

  - Detalhamento hora a hora
  - Detalhamento dos status dos atendimentos (finalizados, transferidos para outro setor ou transferidos para o mesmo setor)
  - Detalhamento de atendimentos transferidos
  - Detalhamento das avaliações mensais dos clientes (client satisfaction)
  - Detalhamento de possíveis encerramentos abruptos (finalização de atendimento sem resolução de caso)
  - Detalhamento de atendimentos com vagarosidade excessiva na resolução (Time Spent e Waiting Time)
  - Evidência de ocorrências negativas na operação
  - Escalabilidade de feedbacks
  - Acompanhamento de evolução de atendentes
  - Automatização na identificação de pontos de melhoria
 
 
## Links
 
  - Link of deployed application: https://docs.google.com/spreadsheets/d/1zFoV5t670G5uap20jzlrRhf91Mdgb48yCKhtIHxX0sw/edit?usp=sharing (Feedbacks_diários)
  - Repositório: https://github.com/Matheus2510/Feedbacks_diarios
    - In case of sensitive bugs like security vulnerabilities, please contact
      YOUR EMAIL directly instead of using issue tracker. We value your effort
      to improve the security and privacy of this project!
 
 
## Versioning
 
1.0.0.0
 
 
## Authors
 
* **Matheus Henrique de Souza**: @Matheus2510 (https://github.com/Matheus2510)
 
 
Please follow github and join us!
Thanks to visiting me and good coding!
