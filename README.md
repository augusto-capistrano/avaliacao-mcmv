# avaliacao-mcmv
Ferramenta para avaliação da inserção urbana de empreendimentos MCMV Faixa 1 com dados do OpenStreetMap

Projeto aplicado de conclusão do curso de pós-graduação em Geoprocessamento da UFABC. Trata-se de um script em python dividido em dois arquivos ipynb.

A partir do endereço e suas coordenadas (obtidas via geocoding, se não disponíveis inicialmente), obtém POIs predefinidos e a rede viária caminhável do entorno via OSMnx, traça as rotas do endereço até cada um dos POIs, calcula as distâncias das rotas, gera relatórios e mapa interativo para visualização dos resultados.
