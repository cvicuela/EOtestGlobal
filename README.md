# EO Chapter Health Check - Con Imagen Misteriosa

Quiz interactivo para diagnosticar la salud de un capitulo de EO (Entrepreneurs' Organization), con un twist divertido.

## Como funciona

1. **Selecciona tu genero** - Al inicio se pregunta si eres hombre o mujer
2. **Responde 15 preguntas** - Sobre los 4 pilares del Chapter Health Model:
   - Liderazgo
   - Excelencia Operativa
   - Valor para Miembros
   - Crecimiento
3. **Imagen misteriosa** - Mientras respondes, una imagen borrosa se va aclarando poco a poco:
   - Si eres **hombre**: aparece una imagen femenina
   - Si eres **mujer**: aparece una imagen masculina
4. **El plot twist** - Al terminar el quiz, en lugar de la imagen revelada... aparece una imagen chistosa de un gato

## Caracteristicas

- Aplicacion de una sola pagina (SPA) - todo en un solo archivo HTML
- Efectos de sonido interactivos con Web Audio API
- Sistema de puntos y rachas (streaks)
- Imagen con blur progresivo que se aclara con cada respuesta
- Mensajes motivacionales que cambian segun el progreso
- Imagen sorpresa chistosa al final con animacion bounce
- Resultados detallados por categoria con graficas animadas
- Diseno responsivo para movil y desktop
- Confetti animado en los resultados
- Integracion opcional con Google Sheets

## Tecnologias

- HTML5 / CSS3 / JavaScript vanilla
- Web Audio API
- CSS Animations & Transitions
- Google Fonts (Outfit, Space Mono)
- Imagenes de Unsplash

## Uso

Simplemente abre `index.html` en un navegador. No requiere servidor, build tools, ni dependencias externas.

## Deployment

Puedes deployarlo en:
- **GitHub Pages**: Settings > Pages > Source: main branch
- **Netlify**: Arrastra la carpeta al dashboard
- **Vercel**: Importa el repositorio
