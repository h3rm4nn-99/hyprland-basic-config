# hyprland-basic-config
Ecco la mia (estremamente minimale) configurazione del window manager **Hyprland** usato insieme a **Waybar** sulla piattaforma **Arch Linux** (*btw*). Nonostante sia stata creata principalmente a fini di backup personale, questa repository può rappresentare un buon punto di partenza per la creazione di configurazioni più complesse, essendo le funzionalità più utili (a mio avviso!) già configurate.

# Prerequisiti
Per far sì che la configurazione presente in questa repository funzioni su una qualsiasi installazione Arch Linux è necessario installare i seguenti pacchetti:
- [``hyprland``](https://archlinux.org/packages/extra/x86_64/hyprland/) (il window manager)
- [``waybar``](https://archlinux.org/packages/extra/x86_64/waybar/) (la barra superiore)
- [``wlogout``](https://aur.archlinux.org/packages/wlogout) (da AUR, per il menu di spegnimento)
- [``hyprlock``](https://archlinux.org/packages/extra/x86_64/hyprlock/) (per la schermata di blocco)
- [``wofi``](https://archlinux.org/packages/extra/x86_64/wofi/) (un app launcher)

# Struttura della repository
- La cartella **Hyprland** contiene la config del window manager e della schermata di blocco. Per installare la config è necessario creare la cartella ``~/.config/hypr`` e copiarvi i file di configurazione (oltre al file png che viene usato come immagine della **lockscreen**)

- La cartella **Waybar** contiene la config della barra superiore. Per installare la config è necessario creare la cartella ``~/.config/waybar`` e copiarvi i file di configurazione.

- La cartella **Wlogout** contiene la config del mneu di spegnimento. Per installare la config è necessario creare la cartella ``~/.config/wlogout`` e copiarvi il file di configurazione.
