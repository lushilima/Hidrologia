# Hidrologia
scripts para hidrologia



Delimitação da bacia hidrográfica + Características fisiométricas
Ciclo-da-aguabaixa.jpg

Caracterização Morfométrica de Bacia Hidrográfica no Google Colab
Authors: Luciana Shigihara Lima & Anna Nachtigall & Emanuele Koschier & Uiele San Martins

Date: 11-07-2025

Este script Python realiza a caracterização morfométrica e fisiográfica de uma bacia hidrográfica a partir de um shapefile de delimitação da bacia e um Modelo Digital de Terreno (MDT).

O que vai ser necessário:
MDT (em formato raster)

saber o exutório da bacia que você quer delimitar

Colocar o MDT em uma pasta no seu GDRIVE
EM UTM - importante para fins de cálculo.

Etapas:

Configuração do ambiente e instalação de bibliotecas (geopandas, rasterio, numpy, matplotlib, whiteboxtools, etc).
Montagem do Google Drive para acesso aos arquivos.
Definição do ponto (interativo) da foz da bacia hidrográfica
Carregamento e recorte do shapefile da bacia e do MDT.
Cálculo de características morfométricas:
Área e Perímetro
Coeficiente de Compacidade (Kc)
Fator de Forma (Ff)
Índice de Conformidade (Cc)
Elevação Média, Mínima, Máxima e Amplitude Altitudinal
Declividade Média
Curva Hipsométrica
ordenamento dos cursos de água por Strahler
densidade de drenagem
sinuosidade do curso principal
Tempo de Concentração
Mapa de isócronas para o curso principal
