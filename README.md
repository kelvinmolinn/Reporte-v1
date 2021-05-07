# REPORTE DE VULNERABILIDADES EN KIOPTRIX
# CONTENIDO:
Contenido y descripción del reporte: 

El objetivo del ataque es lograr vulnerar nuestra maquina en este caso KIOPTRIX lv.1 , para ello arrancamos nuestra maquina kioptrix en un red local, en nuestra primera fase del ataque tenemos la siguiente metodología de hacking 
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

3.	Explorar: 
obtener acceso interactivo en metaesploit
procesos: 
-	msfconsole 
-	search smb (información sobre el protocolo smb)
-	explorar los diferentes modulos del protocolo samba 
-	explotar y enumerar vulnerabilidades en nuestra prueba de penetración 
-	man smbclient
-	smbclient -L <ip atacada>
-	
finalmente obtener privilegios o escalar privilegios y depurar exploits disponibles
procesos:
-	Shells (buscar abrir sección en kioptix)


Nombre de las vulnerabilidades explotadas:
-	Ataque con OpenLuck

Aplicativo de la vulnerabilidad
-	VmWare
-	Máquina Virtual Kioptrix Nivel 1


Referencias:
-	www.rapid7.com
-	www.exploit-db.com
-	www.cvedetails.com
-	www.giac.org 
-	https://github.com/heltonWernik/OpenLuck
-	https://vold3m0rt.medium.com/kioptrix-level-1-285e1ae90162





