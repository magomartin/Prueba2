# Prueba_IA_CNN_clasificar
Este repositorio se crea en el marco del examen de claisificación para la materia de física fisi-3650, "Reto Empresarial".
Contiene los siguientes elementos como parte del deliverable: 
"modelo.py": Script del Modelo.
"Librerías utilizadas": Lista de librerías utilizadas.

Contiene los siguientes elementos adicionales:
"my_model.h5": Modelo guardado en formato h5 (HDF5)
Si se quiere conocer el código con el que se entrenó el modelo, puedo proveerlo contactándome al correo.
Utilicé el script de eval.py (con los datos de Test a los que tenía acceso) para verificar que funcionara: para hacer esto importé el repositorio con el enunciado del examen y sustituí en el script de eval.py la siguiente línea 
Test_data=load_test_paths('./Rice_Image_Dataset/Test/')

por esta otra:

Test_data=load_test_paths('/content/classification-exam-fisi-3650/Rice_Image_Dataset/Test')
