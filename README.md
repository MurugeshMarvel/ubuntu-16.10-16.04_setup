# ubuntu-16.10_setup

This Repository contains some tutorials and code for configuring your ubuntu system immediately after intialization.

**These are the primary steps to be done after finishing the installation of UBUNTU (16.04,16.10)**

1. Update your system's kernel.
```bash
sudo apt-get update
```
2. Update your system's applications
```bash
sudo apt-get upgrade
```
3. Let's Make your system firewall good
```bash
sudo ufw enable

sudo ufw status
```
4. Then install GUI for your firewall
```bash
sudo apt install gufw
```
5. For minimizing the application while clicking on the icon of the application in the launcher you need to run the following code.
```bash
gsettings set org.compiz.unityshell:/org/compiz/profiles/unity/plugins/unityshell/ launcher-minimize-window true
```
6. If you hate the launcher to be in your side screen, you make in below as the windows bar using.
```bash
gsettings set com.canonical.Unity.Launcher launcher-position Bottom
```
*Replace the "Bottom" with the desired position*
7. For tweaks and customization, install unity-tweak-tool
```bash
sudo apt install unity-tweak-tool
```
8. To Install Media Codecs and more for supporting in Multiple video player.
```bash
sudo apt-get install ubuntu-restricted-extras
```
9. To install VLC
```bash
sudo apt-get install vlc
```
10. For getting new customization themes visit this [link](http://www.linuxandubuntu.com/linux-themes)
