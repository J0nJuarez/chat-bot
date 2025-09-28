# LorcaAI

Este proyecto es una **IA local basada en Llama-3** que funciona directamente en tu navegador gracias a **[WebLLM](https://github.com/mlc-ai/web-llm)**. 

No depende de servidores externos: todo el procesamiento se ejecuta en tu dispositivo, garantizando **privacidad, accesibilidad y baja latencia**.


## Características principales

- Ejecución en local: tus datos nunca salen de tu equipo.  
- Privacidad total: sin intermediarios ni servidores externos.  
- Sin conexión constante: funciona incluso con Internet limitado.  
- Baja latencia: las respuestas se generan más rápido al procesarse en tu navegador.  
- Accesible y sencilla: abre tu navegador y empieza a usar la IA sin complicaciones.  
- Hecho en **JavaScript vainilla**: sin frameworks innecesarios, ligero y fácil de adaptar.  
- Diseñado para ser integrable: se puede usar en proyectos web, extensiones y aplicaciones siempre que corran en un navegador de escritorio con **VRAM suficiente**.  



## ¿Por qué no funciona en móviles?

Este proyecto **no está pensado para ejecutarse en móviles** debido a varias limitaciones técnicas:

1. **Falta de VRAM suficiente**: los modelos Llama-3 necesitan varios GB de memoria de video, algo que la mayoría de móviles no puede ofrecer.  
2. **WebGPU limitado**: aunque algunos navegadores móviles empiezan a incorporar soporte experimental de WebGPU, no es estable ni está optimizado para cargas de este tipo.  
3. **Rendimiento insuficiente**: incluso si arranca, la experiencia sería extremadamente lenta y con riesgo de bloqueos o cierres forzados.  

Por estas razones, la ejecución se ha diseñado y optimizado para **navegadores de escritorio** en equipos con suficiente VRAM.  



## Tecnologías utilizadas

- [Llama-3](https://ai.meta.com/llama/) como modelo base.  
- [WebLLM](https://github.com/mlc-ai/web-llm) para la ejecución local en navegador.  
- [2048 Game](https://github.com/gd4Ark/2048) (MIT License).  
- JavaScript vainilla (inspirado en el curso **“100 proyectos de JavaScript”** de [Midudev](https://midu.dev/)).  



## Instalación y uso

1. Clona este repositorio:  
   ```bash
   git clone https://github.com/tuusuario/tu-repo.git
   cd tu-repo
   ```
2. Instala las dependencias (si aplica).  
3. Inicia el proyecto en tu navegador de escritorio.  

*(Se puede adaptar según la configuración concreta del repo.)*



## Inspiración y agradecimientos

- Inspirado en el curso **“100 proyectos de JavaScript”** de [Midudev](https://midu.dev/).  
- Agradecimiento especial a este vídeo: [Midudev en YouTube](https://www.youtube.com/@midudev).  
- Gracias a [gd4Ark/2048](https://github.com/gd4Ark/2048) por su fantástico repositorio del juego **2048**, publicado bajo **licencia MIT**, lo que permite que cualquiera lo pueda usar y adaptar libremente.  



## Licencia

Este proyecto está publicado bajo **Licencia MIT**.  

Me da hasta un poco de cosa ponerle licencia (aunque sea MIT), porque al final lo hice con un enfoque **educativo**, integrando poco a poco distintas partes que me parecían interesantes.  

Aun así, creo que puede ser perfectamente viable para usarlo en **proyectos internos** o en contextos donde se manejen **datos sensibles** y no quieras que salgan de tu equipo.  

Si alguien quiere reutilizar el repositorio e integrarlo en su propio proyecto, **puede ponerse en contacto conmigo** y estaré encantado de explicarle cómo funciona, además de resolver cualquier duda que surja en el proceso.  



## Autor

Proyecto desarrollado por **Jon Juárez**.  

- [GitHub](https://github.com/j0njuarez)  
- [LinkedIn](https://www.linkedin.com/in/jon-juarez)  

