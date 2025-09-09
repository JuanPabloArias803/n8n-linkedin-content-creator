# n8n-linkedin-content-creator

## 📌 Descripción
Este flujo de **n8n** aprovecha la integración de **SerpAPI** y el **API de OpenAI** para crear y publicar diariamente un post en LinkedIn basado en la noticia más reciente del tema seleccionado.  

El objetivo es mantener una presencia activa y profesional en LinkedIn, generando contenido relevante de alto valor y actualizado sin intervención manual.

---

## ⚙️ Funcionamiento del Flujo
1. **Obtención de noticias** 📰  
   Se consulta la noticia más reciente sobre el tema configurado mediante **SerpAPI**.  

2. **Generación de copy** ✍️  
   Con el contenido de la noticia, el API de **OpenAI** redacta un post optimizado para LinkedIn con tono profesional, atractivo y conciso, añadiendo hashtags relacionados.

3. **Generación de imagen** ✍️  
   También se utiliza el API de **OpenAI** para crear una imagen relacionada a la noticia, para lograr más visibilidad.

4. **Publicación automática** 🔗  
   El copy final y la imagen se envía a la API de **LinkedIn** para ser publicado.

---

## 🎯 Beneficios
- **Ahorro de tiempo**: elimina la búsqueda manual de noticias y la redacción de posts.  
- **Consistencia**: asegura publicaciones diarias y oportunas.  
- **Relevancia**: el contenido siempre está alineado con las tendencias más recientes.

---

## 🛠️ Requisitos
- Una cuenta de **n8n**.  
- Clave de **SerpAPI** para consultar noticias.  
- Clave de **OpenAI** API para generar contenido.  
- Credenciales de **LinkedIn** para publicar posts automáticamente.

---

## 📌 Notas
- Este flujo es un ejemplo base y puede integrarse con otros nodos para enriquecer el contenido.
- Asegúrate de respetar las políticas de uso de LinkedIn para evitar bloqueos por publicaciones automatizadas.  

---
