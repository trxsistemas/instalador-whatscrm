DESCARGANDO EL INSTALADOR E INICIANDO LA PRIMERA INSTALACIÓN (USAR SOLO PARA LA PRIMERA INSTALACIÓN):

```bash
sudo apt install -y git && git clone https://github.com/plwdesign/instalador-whatscrm && sudo chmod -R 777 instalador-whatscrm && cd instalador-whatscrm && sudo ./install_primaria
```

ACCEDIENDO AL DIRECTORIO DEL INSTALADOR E INICIANDO INSTALACIONES ADICIONALES (USAR ESTE COMANDO PARA SEGUNDA O MÁS INSTALACIÓN):
```bash
cd ./instalador-whatscrm && sudo ./install_instancia
```

