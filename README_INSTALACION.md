# EFFIX — instalación como app en Android

## Opción rápida: GitHub Pages
1. Crea un repositorio público llamado `effix`.
2. Sube todos los archivos de esta carpeta a la raíz.
3. En GitHub: Settings → Pages → Deploy from branch → main → /(root).
4. Abre la URL HTTPS que GitHub te entregue desde Chrome en Android.
5. Chrome mostrará la opción "Instalar aplicación" / "Añadir a pantalla de inicio".

## Opción Netlify/Vercel
Sube esta carpeta como sitio estático. Debe quedar disponible por HTTPS.

## Importante
La PWA es instalable como aplicación desde Android, pero no es todavía un APK de Google Play.
Para Google Play se puede empaquetar posteriormente como AAB usando Android Studio/Capacitor.
