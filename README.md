![image](https://github.com/user-attachments/assets/3cfac06a-0dbf-4170-950e-684e465f7385)

# Sweet-Dark-v40 for ungoogled-chrome/chromium

Sweet-Dark-v40-chromium is a fork from [Sweet](https://github.com/EliverLara/Sweet). This fork contains a fix for Chromium and Chromium based browsers that use GTK-theme:

![image](https://github.com/user-attachments/assets/9a118a91-63fc-4b86-b4b3-28d28e9c9042)

With theme enabled you'll see working close and minimize buttons:

![image](https://github.com/user-attachments/assets/995da74c-5f77-4323-8fd2-113bd726ec9e)

#### Installation

1. Extract the zip file to the themes directory i.e. `/usr/share/themes/` or `~/.themes/` (create it if necessary).
2. To set the theme in Gnome, run the following commands in Terminal

```
gsettings set org.gnome.desktop.interface gtk-theme "Sweet"
gsettings set org.gnome.desktop.wm.preferences theme "Sweet"
```
or Change via distribution specific tool.

3. Install [stylepak](https://github.com/refi64/stylepak).
4. Restart Chromium.
