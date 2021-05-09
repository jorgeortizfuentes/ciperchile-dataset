# CIPER Chile Dataset

Scraped and processed on May 8, 2021 by Jorge Ortiz Fuentes.

## Tables and columns:

1) Publicaciones (3904 rows) 
- url
- titulo
- entradilla
- fecha
- n_comentarios
- categoria
- n_palabras

2) Comentarios (49756 rows) 
- url
- comentario
- fecha_c
- polaridad (processed with  "2LabelsSentimentAnalysisSpanish" model of HuggingFace)

3) Temas (14431 rows)
- url
- tema

4) Autores (5361 rows)
- url
- autor
