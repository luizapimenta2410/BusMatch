# BusMatch

Aplicação em Python (Jupyter Notebook) que usa a API Olho Vivo da SPTrans
para recomendar uma linha de ônibus direta entre uma origem e um destino.

## O que o projeto faz
- Valida as coordenadas de origem e destino
- Busca linhas e paradas na API Olho Vivo
- Identifica linhas com paradas próximas à origem e ao destino
- Recomenda uma linha, com embarque, desembarque e previsão de chegada
- Exibe os resultados e um mapa interativo

## Como executar
1. Clone o repositório
2. Instale as dependências: `pip install -r requirements.txt`
3. Copie `.env.example` para `.env` e preencha com o seu token da SPTrans
4. Abra `busmatch_sp.ipynb` e execute as células em ordem

## Estratégia adotada
(resumo: raio escolhido, como as linhas são descobertas, critério de seleção)

## Limitações
(a API pode não ter todas as linhas/previsões; só viagens diretas)

## Integrantes
Larissa, Luiza e Moisés
