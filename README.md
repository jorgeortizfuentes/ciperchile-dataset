# CIPER Chile Dataset

Scraped on May 8, 2021 by Jorge Ortiz

## Tables and columns:

1) Publicaciones (publicaciones.csv) 
- url
- titulo
- entradilla
- fecha
- n_comentarios
- categoria
- n_palabras

2) Comentarios (comentarios.csv compressed due to github limitations)
- url
- comentario
- fecha_c
- polaridad (processed with the "2LabelsSentimentAnalysisSpanish" model of HuggingFace)

3) Temas (temas.csv)
- url
- tema

4) Autores (autores.csv)
- url
- autor
