# MariaEugenia
Es una página para venta de ropas, vestidos y trajes

# Usar entorno virtual de python
source venv/bin/activate
# Si no existe el entorno crearlo con
python3 -m venv venv

# Con el entorno activado instalar las dependencias
pip install -r requirements.txt
# Si se instala una nueva librería, actualiza el requirements con
pip freeze > requirements.txt

# Para ver cambios de git
git status
# Para agregar archivos para subir
git add archivoModificado
# Para confirmar los cambios y escribir un mensaje
git commit -m "mensaje"
# Antes de subir hay que traer los datos del repo
git pull --rebase
# Si ya está actualizado se suben los cambios
git push