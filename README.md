Gabriel Barros Mazzariol RM:55541O
Rodrigo Akira Hirota Mori RM:555384




Este projeto é um simulador que prevê o desempenho de pilotos de Fórmula E com base em dados históricos. O sistema utiliza um arquivo CSV contendo informações sobre os pilotos, como experiência, tipo de pista preferido e condições climáticas favoráveis, para calcular a média de pontos que um piloto pode obter em uma corrida, dadas certas condições.

Funcionalidades
Carregamento de dados de pilotos a partir de um arquivo CSV.
Previsão da média de pontos com base na experiência, tipo de pista e condições climáticas.
Interface interativa para seleção de pilotos e parâmetros através de widgets.
Exibição de um relatório com os resultados da previsão.

A função carregar_dados(arquivo) carrega os dados de um arquivo CSV e retorna um DataFrame do pandas,  a função prever_media_pontos(dados, experiencia, tipo_pista_preferido, condicoes_climaticas) filtra os dados dos pilotos com base na experiência, no tipo de pista preferido e nas condições climáticas, e calcula a média de pontos que esses pilotos costumam fazer, retornando esse valor como um número. A função gerar_relatorio(nome_piloto, experiencia, tipo_pista_preferido, condicoes_climaticas, media_pontos) exibe um relatório no console com as informações do piloto, incluindo seu nome, anos de experiência, tipo de pista, condições climáticas e a média de pontos prevista. Por fim, a função interagir() cria uma interface interativa para o usuário, permitindo que ele selecione um piloto, defina os parâmetros e calcule a média de pontos, mas não retorna nada.
