from nbformat import read

# Ruta del archivo cargado
file_path = "/mnt/data/Aprendiendo_Python_con_Fútbol (2).ipynb"

# Cargar el archivo .ipynb para inspeccionarlo
with open(file_path, "r", encoding="utf-8") as file:
    notebook_content = read(file, as_version=4)

notebook_content
