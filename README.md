

# Juego RPG de Texto

Un sencillo juego RPG basado en navegador construido con JavaScript. Los jugadores exploran diferentes ubicaciones, luchan contra monstruos y gestionan recursos como salud, oro e inventario.

## Funcionalidades

* Navegar entre múltiples ubicaciones: Plaza del Pueblo, Tienda y Cueva.
* Luchar contra monstruos, incluyendo slime, bestias con colmillos y un dragón.
* Comprar salud y armas en la tienda.
* Seguimiento de estadísticas del jugador: Salud, Experiencia (XP), Oro e Inventario.
* Interfaz dinámica basada en botones para elegir acciones.

## Cómo Jugar

1. Abre el juego en un navegador.
2. Usa los botones para elegir acciones en cada ubicación:

   * **Plaza del Pueblo**: Ir a la tienda, explorar la cueva o luchar contra el dragón.
   * **Tienda**: Comprar salud, comprar armas o volver a la plaza del pueblo.
   * **Cueva**: Luchar contra monstruos o volver a la plaza del pueblo.
3. Observa tus estadísticas en la parte superior de la pantalla.
4. Derrota monstruos para ganar XP y progresar en el juego.

## Estructura del Código

* **Variables:** Controlan las estadísticas del jugador (`xp`, `health`, `gold`), arma actual, inventario y salud del monstruo.
* **Botones:** Tres botones principales (`button1`, `button2`, `button3`) que se actualizan dinámicamente según la ubicación.
* **Ubicaciones:** Array de objetos que contiene el nombre, los textos de los botones, las funciones de los botones y la descripción del lugar.
* **Funciones:**

  * `update(location)`: Actualiza los botones y el texto según la ubicación actual.
  * Funciones de navegación: `goTown()`, `goStore()`, `goCave()`.
  * Funciones de combate: `fightDragon()`, `fightSlime()`, `fightBeast()`.
  * Funciones de tienda: `buyHealth()`, `buyWeapon()`.

## Limitaciones Actuales

* Las funciones de combate (`fightSlime`, `fightBeast`, `fightDragon`) son placeholders y necesitan implementación.
* La compra de armas aún no está implementada.
* No existen condiciones de victoria o derrota todavía.

## Cómo Empezar

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu-usuario/tu-repo.git
   ```
2. Abre `index.html` en un navegador web.
3. Comienza a jugar haciendo clic en los botones.

## Mejoras Futuras

* Implementar un sistema de combate completo con cálculo de daño.
* Añadir múltiples armas con efectos únicos.
* Incluir gestión de inventario y uso de objetos.
* Crear un sistema de guardar/cargar progreso del jugador.
* Mejorar la UI/UX con estilo y animaciones.


