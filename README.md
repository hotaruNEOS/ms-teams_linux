# ms-teams_linux
Repo with rpm and deb packages of lastest versión for Fedora-Debian and derivatives

### Links to rpm and deb packages

### RPM
  https://img.cs.montana.edu/linux/fedora/local/38/x86_64/

### DEB
  https://web.archive.org/web/20221203104824/https://packages.microsoft.com/repos/ms-teams/pool/main/t/teams/

### Update and Upgrade OS
First update repos and system from our OS writting the next command according your OS:

### Fedora and others (CentOS, Nobara, etc)

  [user@distro ~]$ sudo dnf update

  [user@distro ~]$ sudo dnf upgrade

### Debian and others (Mint, Ubuntu, etc)

  [user@distro ~]$ sudo apt update

  [user@distro ~]$ sudo apt upgrade

### Note: If you use nala (only for Debian and others), write the next command:

  [user@distro ~]$ sudo nala update

  [user@distro ~]$ sudo nala upgrade
  
### Note: If you use KDE Neon, write the next command:

  [user@distro ~]$ sudo apt update

  (*if you use nala on KDE Neon write: sudo nala update*)

  [user@distro ~]$ sudo pkcon update

### Instalation

After to download the package and update OS, open terminal and chage directory where is located the package, ex:
    
  [user@distro ~]$ cd Downloads/

After execute the next command according your OS and write our password, ex:

### Fedora and others (CentOS, Nobara, etc)

  [user@distro ~Downloads]$ sudo dnf install ./teams-version.x86_64.rpm
  
  [sudo] password for user: 

### Debian and others (Mint, Ubuntu, etc (include KDE Neon))

  [user@distro ~Downloads]$ sudo apt install ./teams-version.x86_64.rpm
  
  [sudo] password for user: 

### Note: If you use nala (only for Debian and others, include KDE Neon), write the next command:

  [user@distro ~Downloads]$ sudo nala install ./teams_version_arch.deb

  [sudo] password for user: 

Accept the command and instalation process will start:

  Is this ok [y/N]:y

### Running Microsoft Teams

Once the package installation process is finished, we look for *Microsoft Teams - Preview* in the applications menu of our OS. If you can't find it, log out and log back in and search again.
