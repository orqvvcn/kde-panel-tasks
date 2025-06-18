# underline with bouncy apps kde plasma



https://github.com/user-attachments/assets/ade71f78-303f-408e-8a07-176a94ed6f28


you have to be using the default breeze theme 

this also makes the separator lines and blue bars invisible on the panel and panel applets

suggestion to look better  
- change the application launcher icon to view-grid
- select 'session' on 'show buttons for:' and uncheck the 'Show action button captions' (application launcher settings)
- make the panel floating
  

## install

 Clone the repo
 
```bash
git clone https://github.com/orqvvcn/kde-panel-tasks.git
cd kde-panel-tasks
```

Create needed folders 
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

Log out and log in or restart

alternatively you can install it manually using kio-admin

-------------------------------------------------------------------

## to uninstall
```bash
sudo rm -rf /usr/local/share/plasma/desktoptheme/default
sudo rm -rf /usr/local/share/plasma/plasmoids/org.kde.plasma.taskmanager
```
