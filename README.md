# underline with bouncy apps kde plasma

you have to be using the default breeze theme 


install

 Clone the repo
 
```bash
git clone https://github.com/orqvvcn/kde-panel-tasks.git
cd kde-panel-tasks
```

Create needed folders (with sudo)
```bash
sudo mkdir -p /usr/local/share/plasma/desktoptheme
sudo mkdir -p /usr/local/share/plasma/plasmoids
```

Copy the default folder for Breeze theme

```bash
sudo cp -r default /usr/local/share/plasma/desktoptheme/
```


Copy org.kde.plasma.taskmanager folder

```bash
sudo cp -r org.kde.plasma.taskmanager /usr/local/share/plasma/plasmoids/
```


-------------------------------------------------------------------

to uninstall
```bash
sudo rm -rf /usr/local/share/plasma/desktoptheme/default
sudo rm -rf /usr/local/share/plasma/plasmoids/org.kde.plasma.taskmanager
```
