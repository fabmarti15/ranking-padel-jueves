# Jugadores — nombres y apodos (Americanos de los jueves)

Referencia para traducir los apodos del WhatsApp al **nombre oficial** que usa la página
(`index.html`, array `P`). Úsala cada vez que lleguen resultados nuevos.

| Nombre oficial (en la página) | Apodos / cómo aparece en el grupo |
|---|---|
| Felipe Skewes | **Pipe**, **Presidente**, Pipe Skewes, **Felipe S**, **feli**, "el presidente" |
| Ignacio Tejeda | Tejeda, Nacho |
| Tomás San Juan | Tom, **Tom SJ**, Tom sj, San Juan |
| Daniel La Roche | **Dani**, Dani La Roche |
| Fabián Martínez | **Fa**, Fabián, Fabian Martínez |
| Diego Martínez | **Yeyo**, Diego, Diego Martínez |
| Joaquín Villanueva | **Joaco**, Juaco, Joako, Joako Villanueva |
| Felipe Bindis | Bindis |
| Cristian Pérez | **Cris**, **Crist**, Cristian, C Pérez, Pérez |
| Nicolás Terré | **Terre**, Terré, Nicolás Terre |
| Fabrizio Arnalot | **Fa Arnalot**, **Fabri**, Fa A., Fabrizio |
| José Manuel Lecaros | Lecaros, José Manuel |
| Karl Nebe | **Nebe**, Karl, Karl Nebe Miranda |
| Angello Tapia | Tapia, Angello |
| Andrés Velarde | **Velarde**, Velardes (jugador nuevo desde el 18-jun; pareja fija de Angello Tapia) |
| Kyle Shepard | **Kyle** (jugador nuevo desde el 30-jul) |

## ⚠️ Ojo con las confusiones (apodos peligrosos)

- **"Fa" = Fabián Martínez** ≠ **"Fa Arnalot" / "Fabri" = Fabrizio Arnalot**. Son dos personas.
- **"feli" = Felipe Skewes** (el presidente), NO Felipe Bindis. A Bindis dícenle "Bindis".
- **"Yeyo" = Diego Martínez**. No es un jugador nuevo.
- **"Pipe"** también es Felipe Skewes.
- **"Cris" / "Crist" = Cristian Pérez**.

## Cómo se guardan los resultados

En `index.html`, dentro del array `G`:

```js
["AAAA-MM-DD",["Jugador 1","Jugador 2"],["Jugador 3","Jugador 4"],gamesA,gamesB]
```

Los nombres deben ir **idénticos** a la columna "Nombre oficial" (con tildes).
