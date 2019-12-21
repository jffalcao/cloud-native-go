# cloud-native-go
Packt Video: Getting Started with Cloud Native Go
By: Mario-Leander Reimer

- Safari Tech Videos:   
https://proquestcombo-safaribooksonline-com.res.banq.qc.ca/video/operating-systems-and-server-administration/virtualization/9781787125476

- Lynda.com:   
https://wwwlyndacom.res.banq.qc.ca/Go-tutorials/Motivation-cloud-native-apps/672415/682810-4.html

Clone the repository:

```
$ git clone https://github.com/jffalcao/cloud-native-go.git
```


## Install Go on Linux (Debian)
- Download go from https://golang.org/dl/

```
  $ cd ~/Downloads
  $ sudo tar -C /usr/local -xzf go1.13.5.linux-amd64.tar.gz
  $ nano $HOME/.profile

  # Add the following line and save the file
  export PATH=$PATH:/usr/local/go/bin
```

## Install Postman on Linux (Debian)
- Download from https://www.getpostman.com/downloads/

```
  $ sudo tar -xvzf Postman-linux-x64-7.14.0.tar.gz -C /opt
  $ sudo ln -s /opt/Postman/Postman /usr/bin/postman

  # Add an Icon to the menu

$  cat << EOF > ~/.local/share/applications/postman2.desktop
[Desktop Entry]
Name=Postman
GenericName=API Client
X-GNOME-FullName=Postman API Client
Comment=Make and view REST API calls and responses
Keywords=api;
Exec=/opt/Postman/Postman
Terminal=false
Type=Application
Icon=/opt/Postman/app/resources/app/assets/icon.png
Categories=Development;Utilities;
EOF
```