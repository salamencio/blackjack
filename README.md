# Blackjack Americano — Mesa Royale

Aplicación web de **Blackjack Americano** lista para alojar gratis en **GitHub Pages**, con modo individual y **salas multijugador en tiempo real mediante PeerJS** (sin servidor).

## Características principales

- **Reglas de Casino Americano**: Zapato de 6 barajas (312 cartas) mezclado aleatoriamente, el crupier comprueba Blackjack natural con As o figura y **se planta en todos los 17** (duros y blandos).
- **Pagos verificados**:
  - **Blackjack Natural (21 con 2 cartas)**: paga **3:2** (`apuesta × 2,5` devuelto al saldo). Si el crupier también tiene Blackjack natural, es **empate** y recuperas tu apuesta.
  - **Victoria normal**: paga **1:1** (`apuesta × 2` devuelto al saldo).
  - **Doblar (`Doblar`)**: duplica tu apuesta en las dos primeras cartas, reparte 1 carta adicional y paga **1:1** sobre el total doblado si ganas.
  - **Empate (`Push`)**: devuelve exactamente tu apuesta.
- **Apuestas flexibles y personalizadas**:
  - Fichas rápidas (`1 €`, `5 €`, `25 €`, `50 €`, `100 €`, `500 €`) apilables directamente en los huecos.
  - Campo de **cantidad personalizada** para escribir cualquier importe exacto (`Añadir` o `Fijar`), además de botones `×2` y `MAX`.
  - Hasta **3 huecos simultáneos** en la mesa, opción **Mantener apuesta** y botón **Repetir última**.
- **Banca persistente**: El saldo inicial de **1.000 €** y tus estadísticas se guardan automáticamente en el navegador (`localStorage`). Para reiniciar el dinero debes entrar en la pestaña **Banca / Reiniciar** y escribir `reiniciar`.
- **Multijugador P2P (PeerJS)**: Crea una sala y comparte el código o enlace directo con tus amigos para ocupar los 3 asientos de la mesa.

## Cómo subirlo a GitHub Pages en 3 pasos

1. Crea un repositorio nuevo en [GitHub](https://github.com/new) (por ejemplo, `blackjack`).
2. Sube **todos los archivos** de esta carpeta (`index.html`, `favicon.svg`, `favicon.ico`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `manifest.json`, `.nojekyll`, `README.md`) a la raíz del repositorio.
3. Ve a **Settings → Pages**, en *Build and deployment* selecciona **Deploy from a branch**, elige la rama `main` y la carpeta `/ (root)`, y pulsa **Save**. En unos segundos tendrás tu enlace público listo para jugar.
