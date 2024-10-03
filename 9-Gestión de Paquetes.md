# Gestión de Paquetes 📦

## ¿Qué es un gestor de paquetes?

Un gestor de paquetes es una herramienta que automatiza el proceso de instalación, actualización, configuración y eliminación de programas en un sistema operativo.

## APT (Advanced Package Tool)

APT es el gestor de paquetes utilizado en distribuciones basadas en Debian, como Ubuntu.

Comandos básicos:
```bash
sudo apt update              # Actualiza la lista de paquetes
sudo apt upgrade             # Actualiza todos los paquetes instalados
sudo apt install paquete     # Instala un paquete
sudo apt remove paquete      # Elimina un paquete
```

## YUM (Yellowdog Updater Modified)

YUM es utilizado en sistemas basados en Red Hat, como CentOS.

Comandos básicos:
```bash
sudo yum update              # Actualiza todos los paquetes
sudo yum install paquete     # Instala un paquete
sudo yum remove paquete      # Elimina un paquete
```

## DNF (Dandified YUM)

DNF es el sucesor de YUM, utilizado en Fedora y versiones recientes de Red Hat.

Comandos básicos:
```bash
sudo dnf update              # Actualiza todos los paquetes
sudo dnf install paquete     # Instala un paquete
sudo dnf remove paquete      # Elimina un paquete
```

## Pacman

Pacman es el gestor de paquetes utilizado en Arch Linux y sus derivados.

Comandos básicos:
```bash
sudo pacman -Syu             # Actualiza el sistema
sudo pacman -S paquete       # Instala un paquete
sudo pacman -R paquete       # Elimina un paquete
```

## Snap y Flatpak

Snap (de Canonical) y Flatpak son sistemas de empaquetado y distribución de software universales para Linux.

Snap:
```bash
sudo snap install paquete    # Instala un paquete snap
sudo snap remove paquete     # Elimina un paquete snap
```

Flatpak:
```bash
flatpak install paquete      # Instala un paquete flatpak
flatpak uninstall paquete    # Elimina un paquete flatpak
```
