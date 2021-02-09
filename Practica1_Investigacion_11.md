# Investigación

### Investigación desarrollando los temas y/o resolviendo las siguientes preguntas:

* **¿Qué es un Simulador / Emulador de red?**
  * Es una herramienta de software que proporciona un entorno para realiar pruebas para nuevos sistemas de redes, es una manera segura de realizar pruebas para nuevos metodos antes de su implemantacion.
* **¿Cuáles son los principales emuladores de red? (Mínimo 3 emuladores)**
  1.  Packet Tracer
  2.  NetSim
  3.  Cisco Virtual Internet Routing Lab
  4.  gns3
  5.  Eve-ng
* **¿Cuáles son las ventajas y desventajas de usar un simulador de red para diseñar topologías? (Mínimo 6 ventajas y 6 desventajas)**
  * Ventajas
    1. Permite realizar simulaciones para revisar posibles fallos
    2. Probar la funcionalidad antes de invertir
    3. Permite visualizar de mejor manera las conexiones
    4. Permite un trabajo más limpio y efectivo en un entorno controlado
    5. Posibilidad de tener etiquetas editables para los componentes
    6. Permite optimizar la utilización de los componentes, en comparación si se compran de primero
  * Desventajas
    1. Al ser un entorno controlado no se pueden tomar en cuenta factores externos
    2. No puede tenerse en cuenta la distancia entre un componente y otro para corroborar si son efectivas las conexiones
    3. En un simulador no se toma en cuenta el costo de los componentes o la disponibilidad de los mismos en la vida real
    4. Requiere un conocimiento previo de los emuladores para poder utilizarlos
    5. No se tiene exactamente los mismos componentes terminales (las computadoras físicas) que los que se van a usar en la vida real
    6. Algunos emuladores limitan el uso de cables a un solo tipo

* **¿Qué es Eve-NG? Sus ventajas y desventajas (Mínimo 6 ventajas y 6 desventajas)**
  * Eve-ng es un emulador de redes en linea, que sirve para emular redes, seguridad y devOps
  * Ventajas
    1.  Simple
    2.  Rápido
    3.  Accesible por estar en la red
    4.  Trabajo más fácil en equipo
    5.  Componentes cisco disponibles
  * Desventajas
    1. Solo es accesible en linea
    2. Complica su instalación
    3. No es una aplicación como tal, es un cliente en línea
    4. Requerimiento de un gestor de maquinas virtuales
    5. No disponible para Ubuntu 20

* **¿Que es GNS3? Sus ventajas y desventajas (Mínimo 6 ventajas y 6 desventajas).**

  * Es un software open source, que simula redes ya sea desde diseño de redes simples a complejas, se acerca bastante al funcionamiento real de redes.  Este software proporciona interfaz gráfica, para el diseño de y configuración de redes, las simulaciones que se pueden llegar hacer con este software pueden ser bastante completas y precisas, ya que permite ejecutar emuladores como, VirtualBox, VMware o Qemu para ejecutar diferentes sistemas operativos.   

  * Ventajas

    1. Es open source
    2. Permite ejecutar con o sin hipervisores
    3. Tiene una comunidad bastante grande y activa
    4. No tiene limitaciones de la cantidad de dispositivos permitidos en la redes que se crean
    5. Admite imagines VIRL
    6. Tiene soporte nativo en linux
    7. Es multiplataforma 

  * Desventajas
    1. Depende de el hardware, en el que se ejecuta el GNS3, ya que se podría ver limitado por la ram.
    2. Las imágenes de Cisco, se deben descargar, no vienen incluidas.
    3. Necesita instalación local del software
    4. Se puede ver afectado por la configuración del hardware local. 
    5. No se puede ejecutar en un contenedor, se debe instalar directamente en el sistema
    6. No se puede probar ni medir la performance de la infraestructura real de red 
    

* **Principales diferencias entre GNS3 y Eve-NG, además, ¿En qué situación es
  mejor utilizar cada uno?**
  * GNS3 es mas amigable
  * Eve-NG es para entornos empresariales con recursos mucho más grandes
  * Eve-NG es más potente
  * GNS3 tiene una gran comunidad de colaboradores activos
  * Eve-NG su interfaz es web
  * GNS3 es más básico