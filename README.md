# Blackjack Americano — Mesa Royale

Aplicación web de **Blackjack Americano** lista para alojar gratis en **GitHub Pages**, con dividir pareja (**Split**), **Doblar tras dividir (DAS)**, modo individual (hasta 3 manos), **salas multijugador P2P de 9 huecos** (máximo 3 manos por jugador) y **perfil personalizable** con foto, nombre y contraseña.

## Reglas de Dividir (Split) implementadas

- **Parejas del mismo valor**: Puedes dividir cualquier pareja de dos cartas iniciales del mismo valor (incluidas parejas de figuras/dieces como `K-Q` o `10-J`), colocando una segunda apuesta idéntica.
- **Ases divididos (`A-A`)**: Al dividir Ases, cada As recibe exactamente **1 carta adicional** y se planta automáticamente (sin re-dividir Ases ni doblar).
- **21 tras dividir**: Alcanzar 21 en una mano dividida paga **1:1** (victoria normal, no Blackjack natural 3:2).
- **Doblar tras dividir (DAS)**: Permitido en cualquier mano dividida que no sea de Ases (hasta 4 manos divididas por hueco).

## Cómo subirlo a GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo, `blackjack`).
2. Sube todos los archivos de esta carpeta a la raíz del repositorio.
3. Ve a **Settings → Pages**, selecciona **Deploy from a branch**, elige `main` y `/ (root)` y pulsa **Save**.
