## Сustom application launcher

__Напримере TLauncher'а__

![tlauncher launcher](tlauncher-launcher.png)

**Проверка корректности**
```bash
desktop-file-validate app-name.desktop
```

**Обновление кэша [ ↗ ](https://man.archlinux.org/man/update-desktop-database.1.en)**
```bash
update-desktop-database
```


> /home/retrilz/.local/share/applications/[tlauncher.desktop](tlauncher.desktop)
```
[Desktop Entry]
Version=1.0
Type=Application
Terminal=false
Exec=java -jar /home/retrilz/.tlauncher/tl.jar
Name=TLauncher
Icon=/home/retrilz/.tlauncher/tlico.png
```
