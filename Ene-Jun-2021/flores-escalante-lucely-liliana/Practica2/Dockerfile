# Imagen base
FROM python:3.8

# se declara la dirección
WORKDIR /usr/src/prac2

#se copian los archivos
COPY . /usr/src/prac2

# se instalan los requerimentos
RUN pip install --no-cache-dir -r requirements.txt

# ejecuta este comando
CMD ["python","./NumerosAleatorios.py"]
