# NetHunter-In-Termux
A simple bash script to install Kali Linux NetHunter in an unrooted android device using Termux. Just clone this repository in your Termux and then run ``` nethunter-in-termux.sh ``` file.

## Official tutorial blog and video

[**3 Easy Steps To Install Nethunter In Android**](https://amanbytes.com/install-kali-nethunter-in-android/)


[![Install Nethunter In Termux](https://img.youtube.com/vi/hwVwApYxbVw/0.jpg)](http://www.youtube.com/watch?v=hwVwApYxbVw)

## Installation

```

apt update && apt install git

git clone https://github.com/amanbytes/NetHunter-In-Termux nethunter

cd nethunter

chmod +x nethunter-in-termux.sh

./nethunter-in-termux.sh

```
## Some Commands

```nethunter``` - Start  Kali NetHunter command line interface.

```nethunter kex passwd``` - Configure Kex Password (Only need for first time).

```nethunter kex &``` - start Kali NetHunter VNC Server.

```nethunter kex stop``` - stop Kali NetHunter VNC server.

```nethunter <command>``` - run specified command in NetHunter environment.

```nethunter -r``` - start Kali NetHunter CLI as root.


Read step-by-step guide in installing NetHunter In Termux without root by [clicking here.](https://amanbytes.com/install-kali-nethunter-in-android/)
