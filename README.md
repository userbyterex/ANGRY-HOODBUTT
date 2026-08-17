# 🐦 Angrybird Hoodbutt

Juego estilo Angry Birds con los personajes Hoodbutt.

## Cómo jugar

1. Abre `angrybird-hoodbutt.html` en cualquier navegador moderno (Chrome, Firefox, Edge, Safari).
2. Arrastra el personaje hacia atrás con el ratón o el dedo y suelta para lanzarlo.
3. Destruye todos los cerditos verdes para completar el nivel.
4. Usa el botón **Siguiente** para avanzar.

## Funciones incluidas

- **10+ niveles** diseñados + niveles procedimentales infinitos
- **7 personajes** desbloqueables (tus imágenes)
- **Sistema de login local** (usuario + contraseña opcional)
- **Ranking** de puntuaciones guardado en el dispositivo (localStorage)
- Física de resortera, bloques y partículas
- Compatible con escritorio y móvil (táctil)

## Login y Ranking

- Haz clic en **Iniciar sesión** e introduce un nombre de usuario.
- Tus mejores puntuaciones y nivel máximo se guardan automáticamente.
- El ranking muestra el top 15 de este dispositivo.
- Puedes jugar como invitado (las puntuaciones de invitado también se guardan).

### Sobre Privy

Para un login real con email / wallet (Privy):

1. Crea una cuenta en [privy.io](https://www.privy.io)
2. Crea una App y obtén tu `appId` y `clientId`
3. Integra el SDK `@privy-io/js-sdk-core` o el React SDK
4. Sustituye el sistema de login local por las llamadas de Privy

Esta versión ya está preparada con el flujo de autenticación y ranking listo para conectar a un backend o a Privy.

## Archivos

- `angrybird-hoodbutt.html` → el juego completo
- `*.png` / `*.jpg` → imágenes de los personajes

¡Diviértete!
