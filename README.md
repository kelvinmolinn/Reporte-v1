# REPORTE DE VULNERABILIDADES EN KIOPTRIX
# CONTENIDO:

Contenido y descripción del reporte: 
El objetivo del ataque es lograr vulnerar nuestra maquina en este caso KIOPTRIX lv.1 , para ello arrancamos nuestra maquina kioptrix en un red local, en nuestra primera fase del ataque tenemos la siguiente metodología de hacking :
1.	Reconocimiento: 
Hacer un barrido de la red para identificar los hosts activos.
Proceso: 
-	Arp-scan -l 
-	nmap (hacemos un análisis de los puertos que están abiertos)
-	nmap -T4 -p- -A (ip a atacar)
2.	Enumerar:
Encontrar el servicio a explotar y detalles de la versión
Procesos:
-	encontrar ttps para puertos abiertos
-	identificar el software y la versión instalados
-	encontrar cve / exploits críticos



