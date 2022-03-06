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

Inicialmente se conectan los bloques `swerv_wrapper_verilog` y `intcon_wrapper_bd`, en estos bloques hay tres tipos de sets de pines, los cuales son,  IFU (_Instruction Fetch Unit_), LSU (_Load Store Unit_) y SB (_Store Byte_). La conexión se realiza en el orden mencionado anteriormente, se continúa con el paso a paso de los otros bloques, al terminar las conexiones internas se inician las conexiones externas, estas son el reloj `clk`, el reset, `rst`, las memorias y finalmente los pines `bidir` de lso bloques bidirec, terminando con estos todas als conexiones del diagrama.



![Alt text]()

### 🔖 Conclusiones

*


### 📚 Referencias

* [Imagination University Programme](https://university.imgtec.com/) 
* [RVfpga – Introduction to RVfpgaSoC  V1.0](https://university.imgtec.com/resources/download/rvfpgasoc-v1-0/)
* [EH1 RISC-V SweRV CoreTM 1.9 from Western Digital](https://github.com/chipsalliance/Cores-SweRV.git) 
* [SweRVolf](https://github.com/chipsalliance/Cores-SweRVolf.git) 




#### Universidad Industrial de Santander
* 👩 Francy Jessenia Calderón Osorio - 2162491
* 👩 Andrea Paola Reyes Carreño - 

