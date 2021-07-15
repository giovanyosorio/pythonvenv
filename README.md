# pythonvenv

Creando un ambiente virtual con VENV
Creación de ambiente Virtual:

python3 -m venv nombre_venv

Usualmente el nombre del ambiente virtual es venv.
Activación del ambiente virtual:

Windows:
.\venv\Scripts\activate

Unix o MacOS:
source venv/bin/activate

Desactivar el ambiente virtual:

deactivate

Crear un alias en linux/mac:

Ejecutar sudo nano ~/.zshrc
Ir al final del archivo
Agregar el comando: alias avenv='source venv/bin/activate'
Guardar presionando ctrl + o y luego salir con ctrl + x
Reejecutar la configuración de la terminal: source ~/.zshrc
Activar el entorno vitual avenv
.
De esa forma persistirá siempre, ya que el alias se guarda dentro del archivo de configuración de la termial 😄
