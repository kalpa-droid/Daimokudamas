# 🌸 Daimokudamas - SGI División Femenina

¡Bienvenido a **Daimokudamas**! Una aplicación web interactiva de alto nivel diseñada especialmente para las integrantes de la División Femenina (DF) y Juvenil Femenina (DJF) de la Soka Gakkai. Combina un cronómetro de Daimoku integrado con el logotipo dorado de Hachiyourenge, un aliento dinámico del maestro Daisaku Ikeda con 60 frases inspiradoras vinculadas a fuentes oficiales, y una grilla interactiva gigante en glassmorphism para iluminar perlas doradas formando la palabra **"DAMAS"**.

---

## 🎨 Características Destacadas

*   **Estética de Ensueño (Glassmorphism & Gold)**: Fondos suaves y translúcidos difuminados, tipografías elegantes (Playfair Display, Cormorant Garamond e Inter), gradientes dorados y perlas tridimensionales brillantes para los Daimokus realizados.
*   **Logotipo Dorado de Hachiyourenge**: Gráfico vectorial en alta definición que corona el cronómetro de Daimoku, simbolizando la flor del loto de ocho pétalos.
*   **Aliento del Segundo de Sensei**: El botón de flor late dinámicamente y cambia de flor cada 5 segundos de manera orgánica. Al presionarlo, reproduce un efecto de campanada elegante y muestra una frase de aliento aleatoria entre 60 opciones únicas con enlaces directos a los portales oficiales de la Soka Global y Daisaku Ikeda.
*   **Cálculo Inteligente de Fin de Oración**: Al iniciar el cronómetro, calcula automáticamente la hora exacta en la que finalizarás tu Daimoku y la muestra en una tarjeta destacada.
*   **Red SGI Activa**: Integra un simulador de red local que interactúa cuando estás conectado a internet, mostrando una luz verde y una lista interactiva de damas conectadas en tu zona entonando Daimoku en ese momento.
*   **Soporte de PWA Completo**: Compatible al 100% con los estándares de Google Chrome e iOS (Safari). Almacena todo en caché mediante Service Worker para permitir su uso e instalación como app nativa sin requerir conexión a internet.
*   **Palanca Analógica de Reinicio**: Botón con diseño analógico táctil de palanca deslizante con confirmación de seguridad para restablecer el tablero.

---

## 🚀 Cómo Subir a GitHub

Sigue estos pasos desde la terminal para subir el proyecto a tu repositorio de GitHub:

1.  **Abre una terminal** en la carpeta `/home/mappo/Kalpagrafica/Daimokudamas/`.
2.  **Inicializa el repositorio**:
    ```bash
    git init
    ```
3.  **Añade todos los archivos**:
    ```bash
    git add .
    ```
4.  **Crea el primer commit**:
    ```bash
    git commit -m "feat: versión inicial de Daimokudamas con PWA"
    ```
5.  **Crea un repositorio vacío en tu cuenta de GitHub** (puedes llamarlo `Daimokudamas`).
6.  **Vincula tu repositorio local con GitHub** y sube los archivos:
    ```bash
    git remote add origin https://github.com/TU_USUARIO/Daimokudamas.git
    git branch -M main
    git push -u origin main
    ```

---

## ⚡ Cómo Desplegar en Vercel

Vercel detecta automáticamente proyectos estáticos de HTML de forma instantánea y de manera gratuita.

1.  Inicia sesión en [Vercel](https://vercel.com/) (conectando tu cuenta de GitHub).
2.  Haz clic en **"Add New..."** -> **"Project"**.
3.  Importa tu repositorio **Daimokudamas** de GitHub.
4.  Haz clic en **"Deploy"** sin realizar configuraciones adicionales.
5.  ¡Listo! Ya tienes tu enlace público de Vercel listo para compartir con tus compañeras de la Soka Gakkai.
