# News-query_RPP-lab
# News-query_RPP-lab
Este proyecto implementa un sistema de búsqueda semántica sobre noticias extraídas del RSS de RPP Noticias. Utiliza técnicas de vectorización (TF-IDF) y almacenamiento en ChromaDB para permitir consultas por significado, no solo por coincidencia de palabras.

🎯 Objetivo del Task 1
- Extraer noticias desde el RSS de RPP
- Tokenizar y vectorizar el contenido
- Generar embeddings con TF-IDF
- Crear una colección en ChromaDB
- Permitir consultas semánticas sobre el contenido

🧩 Estructura del proyecto
News-query_RPP-lab/
├── notebooks/
│   └── task1_rpp_news.ipynb
├── src/
│   ├── data_loader.py
│   ├── embedding_generator.py
│   ├── chroma_manager.py
│   └── query_tool.py
├── README.md
├── requirements.txt

Cómo ejecutar
1. Clona el repositorio
2. Abre el notebook `task1_rpp_news.ipynb`
3. Ejecuta las celdas paso a paso (0 a 5)
4. Usa la función `buscar_noticias("tu consulta")` para probar el sistema

📦 Requisitos
- Python 3.10+
- feedparser
- pandas
- scikit-learn
- chromadb


