# Prótesis Electroencefalograma AD620
Electroencefalograma-AD620 Realizado en la Escuela de Educación Secundaria Técnica N°5 "2 de Abril" Temperley, Buenos Aires, Argentina. 

Desarrollado por Iván Romano, 7mo 6ta, 2025

*Proyecto actualmente en desarrollo.*

Actualizaciones constantes hasta su finalización.

Diseño de Hardware Finalizado y presente en el repositorio. 


Proyecto objetivamente orientado a la investigación y el desarrollo con fines educativos de las señales emitidas por el cerebro e implementarlas en una prótesis de brazo.

# Material y softare utilizados
- Desarrollo de PCB: KiCad 8.0 
- Software: VsCode PlatformIO
- Amplificador: AD620an
- MicroControlador: ESP-WROOM-32
- ServoMotores: SG90

# Guía de Repositorio
- Software: En ella se encontrarán los archivos correspondientes a la programación del proyecto.

- Hardwre: Diseño de Módulos PCBs y huellas utilizadas en el proyecto.
  - Fuente_EEG
    - Fuente_EEG: Fuente optativa del proyecto diseñada para componentes SMD y menores exigencias de Corriete por parte del MicroControlador.
    - Fuente_EEG_2: Fuente empleada en el proyecto adaptada al uso de ServoMotores como Output.
  - Amplificador_EEG
    - Amplificador_EEG_Master: Amplificador Master (Contiene al LM358) 
  - MicroControlador_EEG: MicroControlador embebido, procesamiento de la señal y respuesta de Output.
  - Trazado: En esta carpeta se encontrará el trazado empleado para la fabricación manual de las PCBs.

- 3D: Archivos correspondientes a los diseños 3D del proyecto (Diseño de prótesis y soportes de PCBs)




v1.5_Alpha - 16 de Mayo 2025
