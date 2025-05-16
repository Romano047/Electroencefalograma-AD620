# Prótesis Electroencefalograma AD620
Electroencefalograma-AD620 Realizado en la Escuela de Educación Secundaria Técnica N°5 "2 de Abril" Temperley, Buenos Aires, Argentina. 

Desarrollado por Iván Romano, 7mo 6ta, 2025

*Proyecto actualmente en desarrollo.*

Actualizaciones constantes hasta su finalización.

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
  - Fuente_EEG: Fuente optativa del proyecto diseñada para componentes SMD y menores exigencias de Corriete por parte del MicroControlador.
  - Fuente_EEG_2: Fuente empleada en el proyecto adaptada al uso de ServoMotores como Output.
  - Amplificador_EEG: Etapa de amplificación de la señal.
  - MicroControlador_EEG: MicroControlador embebido, procesamiento de la señal y respuesta de Output.
  - Huellas y Footprints Externos
    - E.E.S.T. n°5: Huellas diseñadas por alumnos de la escuela correspondiente.
    - MacroLib: Carpeta diseñada por el profesor Máximiliano Andrés Barzola.
    - Romano: Carpeta diseñada por el creador de este repositorio.
- 3D: Archivos correspondientes a los diseños 3D del proyecto (Diseño de prótesis y soportes de PCBs)

v1.0 - 15 de Mayo 2025
