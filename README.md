# Map [GfxTablet](https://github.com/rfc2822/GfxTablet) input to [Xournal](https://xournalpp.github.io/)

Usa [xodotool](https://github.com/jordansissel/xdotool) per ottenere le coordinate della finestra di Xournal.
Calcola la matrice di trasformazione in modo da mappare l'input di GfxTablet alla finestra Xournal mantenendo le proporzioni e massimizzando la superficie attiva del tablet. 
Infine usa [xinit](https://github.com/freedesktop/xorg-xinit) per applicare la trasformazione.
