# underline with bouncy apps kde plasma




https://github.com/user-attachments/assets/168f5642-9a8e-432d-b917-f5d1abf3028b



https://github.com/user-attachments/assets/8ed280c5-4dd7-4f4a-a578-eba26ef1dd3a


works for dark mode and light mode




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


Copy paste org.kde.plasma.taskmanager and org.kde.plasma.kickoff folder

```bash
sudo cp -r org.kde.plasma.taskmanager /usr/local/share/plasma/plasmoids/
sudo cp -r org.kde.plasma.kickoff /usr/local/share/plasma/plasmoids/
```

Log out and log in or restart

alternatively you can install it manually using kio-admin

-------------------------------------------------------------------

## to uninstall
```bash
sudo rm -rf /usr/local/share/plasma/desktoptheme/default
sudo rm -rf /usr/local/share/plasma/plasmoids/org.kde.plasma.taskmanager
sudo rm -rf /usr/local/share/plasma/plasmoids/org.kde.plasma.kickoff

```
