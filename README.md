# Omarchy Pill Bar

Una barra de Omarchy Quattro con cada sección/widget en su propia píldora. Usa los colores del tema activo, ajusta el contraste de la letra cuando hay transparencia y mantiene el reloj centrado al pasar el cursor.

## Instalar

```bash
omarchy plugin add https://github.com/jeancarlosg93/omarchy-pill-bar.git --enable
omarchy restart shell
```

No requiere los plugins de reloj ni de espacios de trabajo: puede usarse con los widgets originales de Omarchy o con los personalizados.

Las píldoras se muestran por defecto. Haz doble clic derecho en una zona vacía del centro de la barra para alternarlas. La elección se guarda como `bar.pills` en `~/.config/omarchy/shell.json`. El doble clic izquierdo en esa zona sigue alternando la transparencia.

Para volver a la barra original sin desinstalar este plugin:

```bash
omarchy bar use omarchy.bar
omarchy restart shell
```

Para actualizar: `omarchy plugin update jeanc.bar`.

`Bar.qml` y `BarModel.js` derivan del shell de [Omarchy](https://github.com/omacom/omarchy), bajo licencia MIT. Véase [LICENSE](LICENSE).
