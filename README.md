# oto-cc3201-g14
Proyecto grupo 14 Bases de Datos

Por ahora está disponible a la vista en padón de La Florida. Pronto añadiremos más.

Usaremos el padrón electoral y los resultados de las votaciones por mesas:
- Resultados de votación: 13_Resultados_Mesa_Alcaldes_TER.xlsx
- Padrón electoral La Florida (~300.000 registros):
	https://drive.google.com/file/d/0B94CdcwUqdv4bXd1bGlnd0g1dnM/view
	(Tuve que subirlo a drive por el tamaño del archivo)
- Parser pdf -> texto:
	https://github.com/jpalma-espinosa/servel/blob/master/servelParser.py

Nuestro base estará compuesta de las tablas:
- Para todos los votantes (nombre, rut, direccion, mesa, etc.)
- Para las direcciones (dirección, circuncripcion, comuna, etc.)
- Resultados por mesa (pacto, candidato, votos)
