# Extensions:
Bluetooth Quick Connect - Simplify the process of connecting Bluetooth devices to your Ubuntu system.

Blur my Shell - Add a stylish blur effect to your Ubuntu Shell interface.

Custom Hot Corners - Extended - Configure and personalize hot corner actions on your Ubuntu desktop.

Dash to Panel - Transform your Ubuntu Dash into a convenient and customizable panel.

Desktop Icons - Easily manage and organize your desktop icons on Ubuntu.

Extension List - Get a comprehensive list of installed GNOME extensions on your Ubuntu system.

Impatience - Speed up GNOME Shell animations for a snappier desktop experience.

OpenWeather - Access real-time weather information directly from your Ubuntu desktop.

Screenshot Tool - Capture screenshots effortlessly with this handy Ubuntu tool.

Ubuntu Appindicators - Enable support for legacy application indicators in Ubuntu.

Vitals - Monitor system resources and hardware information in Ubuntu.

Window is Ready - Notification Remover - Disable annoying "Window is Ready" notifications on Ubuntu.

Lolcat - Add rainbow colors to your terminal output with this fun script.

Tree - Install and utilize the 'tree' command for a visual representation of directory structures.

# Script
```
#!/bin/bash

# Bluetooth Quick Connect
sudo apt-get install gnome-bluetooth -y

# Blur my Shell
sudo apt-get install gnome-shell-extension-blur-my-shell -y

# Custom Hot Corners - Extended
sudo apt-get install gnome-shell-extension-custom-hot-corners -y

# Dash to Panel
sudo apt-get install gnome-shell-extension-dash-to-panel -y

# Desktop Icons
sudo apt-get install gnome-shell-extension-desktop-icons -y

# Extension List
sudo apt-get install gnome-shell-extension-prefs -y

# Impatience
sudo apt-get install gnome-shell-extension-impatience -y

# OpenWeather
sudo apt-get install gnome-shell-extension-weather -y

# Screenshot Tool
sudo apt-get install gnome-screenshot -y

# Ubuntu Appindicators
sudo apt-get install gnome-shell-extension-appindicator -y

# Vitals
sudo apt-get install gnome-shell-extension-system-monitor -y

# ArcMenu
sudo apt-get install gnome-shell-extension-arc-menu -y

# Window is Ready - Notification Remover
sudo apt-get install gnome-shell-extension-window-is-ready-notification-remover -y

# Lolcat
apt-get install ruby
wget https://github.com/busyloop/lolcat/archive/master.zip
unzip master.zip
cd lolcat-master/bin
gem install lolcat

# Tree
sudo apt-get install tree


echo "All items downloaded successfully."
```
