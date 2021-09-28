# Modelo para Apresentação do Lab06 - Artigo de Dataset Público

Estrutura de pastas:

~~~
├── README.md  <- arquivo apresentando a tarefa
│
└── images     <- arquivos de imagem usados na tarefa (se houver)
~~~

# Aluno
* `233840`: `Elton Cardoso do Nascimento`

# Análise do Artigo `Dataset: Multi-city Street-Sidewalk Imagery from Pedestrian Mobile Cameras`

| campo | valor |
|------------|----------------------------------------|
| referência |JAIN, S. Multi-city street-sidewalk imagery from pedestrian mobile cameras: dataset. Proceedings of the Third Workshop on Data: Acquisition To Analysis. Anais... In: SENSYS ’20: THE 18TH ACM CONFERENCE ON EMBEDDED NETWORKED SENSOR SYSTEMS. Virtual Event Japan: ACM, 16 nov. 2020. Disponível em: <https://dl.acm.org/doi/10.1145/3419016.3431486>. Acesso em: 28 set. 2021|
| link       | https://dl.acm.org/doi/pdf/10.1145/3419016.3431486?casa_token=Dyo6022vhX4AAAAA:Vq-8-ADpCwtq3xnIwsRlXSqE0xPrq-FKILLETCiw3ag1M6RzxuR5n4Qb8Oe4KVQ0nY6hBvZcTp-1FA |
| dataset | https://datadryad.org/stash/dataset/doi:10.5061/dryad.2280gb5qj|
| formato | Imagens PNG, organizadas em pastas segundo cidade, tipo (calçada/rua) e material|

## Resumo


O artigo descreve a coleta de dados para o dataset TerraFirma, que contém imagens coletadas por voluntários usando celulares enquanto caminhavam em diferentes cidades do mundo, para possuir uma diversidade de posições da câmera e tipos de materiais. O artigo propõe o uso desses dados para diferentes aplicações, se focando na segurança dos pedestres; problema relevante na atualidade, visto que o hábito de andar enquanto digita no celular cresce. Ele também realiza uma análise estatística das imagens.

## Perguntas de pesquisa/análises

Entre as análises propostas pelo artigo, se encontram aquelas voltadas para a segurança dos pedestres como verificar se uma via é segura para a pessoa, se ela está na calçada ou na rua, se existe algum risco em seu caminho. 

Uma outra categoria se volta para estatísticas desses mesmos pedestres, como o tempo de espera em passagens de pedestre, o tempo de travessia e a variação na velocidade para atravessar.

Por fim, a terceira categoria se volta para estatísticas sobre a própria cidade, para auxiliar no seu projeto e policiamento. Se encontram nela perguntas como monitorar a condição de uma rua e o seu material.

## Trabalhos relacionados

É mencionado, sem citação, a existência de outros datasets semelhantes, porém capturados usando câmeras especiais e ambientes controlados. Ele também cita outros trabalhos que utilizam sensores vestíveis e móveis para detectar o contexto do pedestre, assim como um projeto governamental da cidade de New York voltado para a segurança de pedestres na cidade. 