#Crea una carpeta llamada 'mi_pre_prueba' y entra en ella.
mkdir mi_pre_prueba
cd mi_pre_prueba
#Crea un archivo llamado 'info.txt' que contenga tu nombre completo
echo "zeus chavez galvez" > info.txt
#Copia 'info.txt' a 'copia_info.txt'.
cp info.txt copia_info.txt
#Muestra el contenido de ambos archivos en pantalla usando un solo comando.
cat archivo1.txt archivo.txt
#Elimina 'copia_info.txt'
rm copia_info.txt
#Muestra los permisos del archivo 'info.txt'
ls -l info.txt
#Cambia los permisos para que solo tú puedas leer y escribir 'info.txt'.
chmod 600 info.txt
chmod u=rw,g=---,o=--- info.txt
#Crea un archivo oculto con tu nombre y verifica que existe.
echo "zeus_chavez_galvez" .(nombre).txt
para buscar tu archivo oculto ls -a 
nano .hola.txt (escribe adentro tu nombre o x)
#Usa 'find' para buscar archivos '.txt' en tu carpeta.
find *.txt
#Usa 'grep' para buscar tu nombre dentro de 'info.txt'
grep Zeus info.txt
-----------------------------------------------------------------
#Crea archivos 'a.txt' con "Hola" y 'b.txt' con "Mundo", únelos en 'saludo.txt'.
cat a.txt b.txt > saludo.txt
#Comprime todos los archivos '.txt' en 'archivos.tar.gz'.
tar -czvf archivos.tar.gz *.txt
#Extrae 'archivos.tar.gz' en una carpeta llamada 'extraidos'.
mkdir extraidos
tar -xzvf archivo.tar.gz -C extraidos
#Usa 'awk' para imprimir nombres de un archivo 'nombres.csv' con datos tipo:
echo -e "Juan,23\nAna,19\nLuis,31" > data.csv
awk -F [.,] {print$1} nombres.csv (sale en la pantalla los nombres y edad)

