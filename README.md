# MMDVM Reflector Monitor: This is the dashboard for the MMDVM Reflector app created by Caleb KO4UYJ.

[![License](https://img.shields.io/badge/License-GPLv3-blue?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)

## Debian Basic Scripted Install:

The script downloads dotnet for compiling, compiles the app, and creates a service file so it can run in the background.

 - `sudo -s`
 - `apt update && sudo apt upgrade`
 - `apt install git`
 - `cd /opt`
 - `git clone https://github.com/firealarmss/MMDVM_Reflector`
 - `cd MMDVM_Reflector`
 - `chmod +x install.sh`
 - `./install.sh`
