This repo contains a configuration file for creating a connection with nmcli for the eduroam network of the HTW Berlin.

### Steps
1) Follow [this guide](https://doku.tid.dfn.de/de:eduroam:easyroam#installation_der_easyroam_profile_auf_linux_geraeten_ohne_desktop_umgebung_wpa-supplicant_only) but only until the step, where you moved the files in the directory /etc/easyroam-certs/
2) either copy & paste or use git clone to copy the config.sh file in this repo
3) you need to specify two values
* your CN
* your private key password
just remove the placeholders in the command and input the right values

4) run the command and connect to the wifi with `nmcli device wifi connect eduroam`
