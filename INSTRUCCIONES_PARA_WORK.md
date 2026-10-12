# BUSTER ALGORITMO — PAQUETE DE CONTINUIDAD PARA CHATGPT WORK

## Objetivo
Publicar la aplicación web existente Buster Algoritmo en GitHub Pages, habilitar instalación PWA y facilitar que el usuario la agregue a la pantalla de inicio de Android. NO reemplazar la aplicación por una demo.

## Repositorio existente
https://github.com/obustamanteterrazas-cmd/Buster-algoritmo
Propietario: obustamanteterrazas-cmd
Rama principal indicada: main
Visibilidad: pública

## Estado verificado en el chat anterior (12 de octubre de 2026)
- Repositorio existente, visible desde la conexión GitHub.
- La integración GitHub del chat anterior devolvió 403 «Resource not accessible by integration» al intentar crear archivos.
- NO se subieron archivos mediante esa integración; NO se activó GitHub Pages; NO hay URL de instalación verificada.
- El usuario tiene otro chat en Work que podría tener acceso de escritura.
- Este paquete incluye el ZIP original de la PWA y una copia extraída de sus cinco archivos.

## Archivos incluidos
- app/index.html
- app/manifest.webmanifest
- app/sw.js
- app/icon-192.png
- app/icon-512.png
- Buster_Algoritmo_PWA_original.zip

## Instrucciones para Work
1. Inspecciona todos los archivos, especialmente index.html, manifest.webmanifest y sw.js. Conserva el simulador existente y corrige solo lo necesario.
2. Verifica acceso de escritura al repositorio antes de modificarlo. Evita sobreescribir cambios de terceros; revisa el contenido actual.
3. Sube los cinco archivos de app/ a la raíz de la rama main del repositorio.
4. Configura GitHub Pages para servir la rama main, carpeta /(root), o usa el flujo permitido por la plataforma.
5. Espera el despliegue y comprueba HTTP 200, carga del simulador, enlaces relativos, iconos, manifest y service worker.
6. Verifica la posibilidad de instalar la PWA en Android; si falta algún requisito, arréglalo.
7. Entrega URL HTTPS pública verificada y pasos concretos en Chrome: menú ⋮ > Instalar aplicación (o Añadir a pantalla principal).
8. Si no puedes activar Pages mediante herramientas, proporciona instrucciones precisas para Settings > Pages > Deploy from a branch > main > /(root) > Save, y verifica después.

## Consideraciones técnicas
- GitHub Pages en un repositorio de proyecto suele publicar bajo /Buster-algoritmo/; comprueba que rutas de iconos, manifest, service worker y start_url sean relativas.
- No afirmes que el icono ya está instalado: la instalación final se confirma desde el dispositivo del usuario.
- Esta es una simulación de microestructura y formación de precios, NO un sistema de predicción de mercado.
- Distingue agresión compradora/vendedora, liquidez, ejecuciones, cancelaciones y reposición.
- Antes de presentar como versión terminada, prueba controles, cálculos, exportación CSV y comportamiento móvil.

## Mensaje del usuario
«Quiero instalar Buster Algoritmo en mi celular Android con icono, igual que Aula Técnica. Ya autoricé trabajar en mi repositorio de GitHub. Continúa desde este paquete y publica la app».
