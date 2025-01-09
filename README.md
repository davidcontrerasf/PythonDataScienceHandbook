# PythonDataScienceHandbook
Essentials tools for working with data

# Clonar el repositorio desde GitHub (si aún no lo tienes localmente)
git clone https://github.com/tu-usuario/PythonDataScienceHandbook.git
cd PythonDataScienceHandbook

# Crear la carpeta "notebooks"
mkdir notebooks

# Crear un archivo README.md para describir el repositorio
echo "# Python Data Science Handbook" > README.md
echo "This repository contains the entire Python Data Science Handbook, in the form of (free!) Jupyter notebooks." >> README.md
echo "\n## Structure" >> README.md
echo "- **notebooks/**: Contains all Jupyter notebooks from the handbook." >> README.md

# Agregar notebooks (aquí como ejemplo, puedes añadir los tuyos reales)
cd notebooks
echo "# Placeholder notebook" > example_notebook.ipynb

# Volver al directorio raíz
cd ..

# Añadir los cambios al repositorio
git add .
git commit -m "Initial structure for Python Data Science Handbook repository"
git push origin main
