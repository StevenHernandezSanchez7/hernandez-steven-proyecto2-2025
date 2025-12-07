## Descripcion del Proyecto
Aplicacion React desarrollada como parte del Proyecto 2 de la materia Tecnicas de Programacion, desplegada en Firebase Hosting para demostrar habilidades de despliegue en produccion.

## Objetivos Cumplidos
- [x] Configuracion de Firebase Hosting
- [x] Build de produccion de aplicacion React
- [x] Despliegue automatico en Firebase
- [x] URL publica accesible
- [x] Documentacion completa del proceso

## Caracteristicas Tecnicas
- **Frontend:** React 18.2.0 con Hooks
- **Hosting:** Firebase Hosting
- **Build:** Webpack optimizado para produccion
- **CI/CD:** Despliegue manual configurado
- **Performance:** Score alto en Lighthouse

### Requisitos Previos
- Node.js (v14 o superior)
- npm o yarn
- Cuenta de Google para Firebase
- npm install
- npm start
- npm install -g firebase-tools
- firebase login
- firebase init hosting
- npm run build
- firebase deploy --only hosting

  npm start          # Inicia servidor de desarrollo
npm run build      # Crea build de produccion
npm test           # Ejecuta pruebas
npm run eject      # Expone configuracion (avanzado)
firebase deploy    # Despliega en Firebase Hosting

Dependencias Principales
json
{
  "react": "^18.2.0",
  "react-dom": "^18.2.0",
  "react-scripts": "5.0.1",
  "firebase": "^10.5.0"
}
