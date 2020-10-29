# Comandos de la Práctica 01
## Pablo Hernandez

# Parte I. 

**Respuesta 1:**

/usr/bin/bash 

**Respuesta 2:**

mkdir data filtered raw_data meta scripts figures archive

**Respuesta 3:**

mv filtered data; mv raw_data data

**Respuesta 4:**

- La organización de "data" se debe a que esta carpeta requiere especificar el tipo de informacion que sera procesada en el proyecto.
- La carpeta "meta" contendra informacion que describe a la informacion del proyecto.
- La carpeta "scripts" se utilizara para guardar codigo fuente que realice procesos dentro del proyecto.
- La carpeta "figures" se utiliza como pivote para archivos que componen graficos.
- La carpeta "archives" contiene informacion privada.

# Parte II.


**Respuesta 1:**

chmod +x delay.sh

**Respuesta 2:**

ls -l

**Respuesta 3:**

sleep 30

**Respuesta 4:**

./delay.sh &
kill PID

# Parte III.


**Respuesta 1:**

cd meta
touch SarsCov-2.txt
nano SarsCov-2.txt

**Respuesta 3:**

mv sequence.fasta x_sequence.fasta
mv sequence.gff3 x_sequence.gff3
mv x phernandez_p01/data/raw_data

# Parte IV.

**Respuesta 1:**

ln -s ../raw_data/splike_x.faa

**Respuesta 2:**

touch glycoproteins.faa

**Respuesta 3:**

head -1 splike_x.faa

**Respuesta 4:**

cat splike_a.faa > cat splike_b.faa > cat splike_c.faa > glycoproteins.faa

**Respuesta 5:**

Los enlaces simbolicos han desaparecido.

**Respuesta 6:**

head -3 sarscov2_genome.fasta
zless sarscov2_assembly.fasta.gz | head -3 -

La diferencia es que el genoma es mas largo porque representa el total, mientras que el assembly solo es un gen especifico.


