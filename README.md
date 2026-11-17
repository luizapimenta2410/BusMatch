# BusMatch
O sistema deverá gerar duas coordenadas geográficas (latitude e longitude), representando:

- Origem: localização inicial do usuário.

- Destino: local para o qual o usuário deseja se deslocar.

A partir dessas coordenadas, o algoritmo deverá consultar a API Olho Vivo e identificar linhas de ônibus que possuam pontos de parada próximos tanto da origem quanto do destino.

A proximidade deverá ser definida por um raio de distância entre 1 e 1.000 metros, escolhido pelo grupo.

Após identificar as linhas candidatas, o sistema deverá selecionar uma opção, identificar os pontos de embarque e desembarque e consultar a previsão de chegada do próximo ônibus ao ponto de embarque.

A aplicação deverá considerar apenas viagens diretas, sem troca de ônibus.
