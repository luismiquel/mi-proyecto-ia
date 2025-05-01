# mi-proyecto-ia
Proyecto del curso Building AI

# IA para detectar noticias falsas en redes sociales
Proyecto de curso de desarrollo de IA – Building AI

## Resumen
Este proyecto propone una solución basada en inteligencia artificial para detectar noticias falsas compartidas en redes sociales, ayudando a los usuarios a identificar contenido potencialmente engañoso antes de compartirlo.

## Antecedentes
Las noticias falsas son un problema creciente en la era digital, especialmente en plataformas como Facebook, Twitter o WhatsApp. Este tipo de contenido puede tener consecuencias sociales, políticas y de salud muy negativas. Mi motivación personal surge del deseo de contribuir a una red más segura y consciente, donde los usuarios puedan tomar decisiones informadas antes de difundir información.

### Problemas abordados:
- Desinformación en redes sociales
- Difusión viral de contenido falso
- Dificultad de verificar la veracidad rápidamente

## ¿Cómo se utiliza?
El sistema se integra como una extensión del navegador o aplicación complementaria. Cuando el usuario selecciona un texto o enlace, el modelo analiza automáticamente el contenido y devuelve una probabilidad de veracidad. Si el contenido parece falso o poco confiable, se muestra una advertencia.

### Usuarios:
- Personas que consumen y comparten noticias
- Educadores y periodistas
- Plataformas que quieren reducir la desinformación

## Fuentes de datos y métodos de IA
### Datos:
- FakeNewsNet Dataset
- Noticias verificadas por fact-checkers (Snopes, PolitiFact)

### Técnicas:
- Clasificación de texto con modelos de lenguaje (TF-IDF, BERT)
- Redes neuronales recurrentes (RNN, LSTM) para análisis secuencial
- Procesamiento de lenguaje natural (NLP)

## Desafíos
- No puede garantizar la veracidad al 100%
- Posibles sesgos en los datos de entrenamiento
- Privacidad de los usuarios al analizar contenido en tiempo real

## ¿Qué sigue?
- Añadir capacidad multilingüe (español, inglés, portugués)
- Integrar el modelo en aplicaciones móviles
- Colaborar con organizaciones de verificación profesional

## Agradecimientos
- Inspirado en proyectos de código abierto como FakeNewsNet
- Dataset original por Kai Shu, Suhang Wang y Huan Liu
- Licencia de datos y código respetada conforme a uso académico y educativo
