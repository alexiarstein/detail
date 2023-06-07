# Detail

Detail is a small application that prints information about a file, directory or link in a rather comprehensive and human format.

    [alexia@goldenDogLinux]$ detail example.txt  
    Detail 1.1.2
    Nombre example.txt | Tipo: Archivo | CHMOD: 664  
    Dueño/a: alexia | Grupo: alexia | Sistema (Todos) | 
    Lectura:     si | Lectura:   si | Lectura:     si | 
    Escritura:   si | Escritura: si | Escritura:   no |
    Ejecución:   no | Ejecución: no | Ejecución:   no |
    
    [alexia@goldenDogLinux]$ detail /usr/bin/
    Detail 1.1.2 
    Nombre /usr/bin/ | Tipo: Directorio | CHMOD: 555
    Dueño/a: root |   Grupo: root | Sistema (Todos) |
    Lectura:   si | Lectura:   si | Lectura:     si |
    Escritura: no | Escritura: no | Escritura:   no |  
    Ejecución: si | Ejecución: si | Ejecución:   si | 
    [alexia@goldenDogLinux]$


# Install:

 1. git clone https://github.com/alexiarstein/detail.git
 2. copy/paste the following code in your terminal:

    cd detail; sudo mv /usr/local/bin/detail; sudo chmod a+x /usr/local/bin/detail

## Remove:

    sudo rm ~/.detail.conf; sudo rm /usr/local/bin/detail

## Reset Language:

    sudo rm ~/.detail.conf


# Author:
**Alexia R. Stein  <mistysteinberg@gmail.com>**

## Changelog:

**v1.1.2**
06/06/2023: Added language support
fixed minor bugs.

## Contributions:
Contributions are needed. I need help translating this script to the following languages:

 - Portuguese
 - French
 - Chinese
 - Japanese
 - German
 - Russian
 - Italian 
  

# TO DO:
Create .deb and .rpm installer packages
Create snap and flatpak containers
