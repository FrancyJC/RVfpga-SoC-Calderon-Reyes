# 📚 Proyecto Arquitectura de Computadores I.

# 💻 RVfpgaSoC

Algunos de los grandes contribuyentes actuales en el área de tecnología, se unieron para crear e impartir un curso para el aprendizaje y estudio de SoCs, _System-on-Chips_, entre ellas resaltan Diligent, RISC-V, Xilinx, Imagination entre otros. 

En este curso se muestra como construir un subconjunto de SweRVolfX SoC desde cero utilizando bloques de construcción como el núcleo SweRV, las memorias y los periféricos, mediante el software de Vivado.

Inicialmente se busca crear un diagrama de bloques en el cuál se incluyen los siguientes bloques de vivado:

| No. 	| Módulo               	| Vivado bloque         	|
|-----	|----------------------	|-----------------------	|
| 1   	| SweRV Core           	| swerv_wrapper_verilog 	|
| 1   	| Interconnect Wrapper 	| intcon_wrapper_bd     	|
| 1   	| Boot-ROM             	| bootrom_wrapper       	|
| 1   	| GPIO Top Module      	| gpio_wrapper          	|
| 1   	| System Controller    	| syscon_wrapper        	|
| 32  	| Bidirec Gpio Module  	| bidirec               	|

Estos módulos se interconectan mediante un instructivo proporcionado por _Imaginaton_, donde se especifican las conecciones.

Inicialmente se conectan los bloques `swerv_wrapper_verilog` y `intcon_wrapper_bd`, en estos bloques hay tres tipos de sets de pines, los cuales son,  IFU (_Instruction Fetch Unit_), LSU (_Load Store Unit_) y SB (_Store Byte_). La conexión se realizará en el orden mencionado anteriormente.


###Characters
                

Superscript: X<sub>2</sub>，Subscript: O<sup>2</sup>

**Abbreviation(link HTML abbr tag)**

The <abbr title="Hyper Text Markup Language">HTML</abbr> specification is maintained by the <abbr title="World Wide Web Consortium">W3C</abbr>.


###Links

[Links](http://localhost/)

[Links with title](http://localhost/ "link title")

`<link>` : <https://github.com>

[Reference link][id/name] 

[id/name]: http://link-url/


ejem imagen

![Alt text](https://i.imgur.com/ZgpiGM3.png)

### 🔖 Conclusiones

*


### 📚 Referencias
ejemplo referencias

* [HDLbits](https://hdlbits.01xz.net/wiki/Module_fadd) 
* [YosysHQ](https://www.yosyshq.com/)
* [Karnaugh Map](https://www.geeksforgeeks.org/introduction-of-k-map-karnaugh-map/)
* [SimuladorTablas](https://logicaunad.com/simulador-tablas/)





#### Universidad Industrial de Santander
* 👩 Francy Jessenia Calderón Osorio - 2162491
* 👩 Andrea Paola Reyes Carreño - 

