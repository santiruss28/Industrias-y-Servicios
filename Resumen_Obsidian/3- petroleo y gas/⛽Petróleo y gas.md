Material:
[[🖥️ Petróleo y Gas.pdf]]
[[🖥️ El Petróleo I.pdf]]
[[🖥️ El Petróleo II.pdf]]
[[🖥️ Industrialización del Petróleo_YPF.pdf]]
[[🖥️ Petróleo y Gas_Reservorios no convencionales (N. García).pdf]]

Esquema:
[[⚙️Flowchart - Refinería]]

Cuotas de mercados operadores de petróleo Nafta:
```chartsview
#-----------------#
#- chart type    -#
#-----------------#
type: Pie

#-----------------#
#- chart data    -#
#-----------------#
data:
  - type: "YPF (%)"
    value: 60
  - type: "SHELL (%)"
    value: 20
  - type: "AXION (%)"
    value: 13
  - type: "PUMA (%)"
    value: 5
  - type: "OTRAS (%)"
    value: 2  

#-----------------#
#- chart options -#
#-----------------#
options:
  angleField: "value"
  colorField: "type"
  radius: 0.8
  legend:
    layout: "horizontal"
    position: "BOTTOM"
```

Cuotas de mercados operadores de petróleo Gasoil:
```chartsview
#-----------------#
#- chart type    -#
#-----------------#
type: Pie

#-----------------#
#- chart data    -#
#-----------------#
data:
  - type: "YPF (%)"
    value: 60
  - type: "SHELL (%)"
    value: 14
  - type: "AXION (%)"
    value: 13
  - type: "PUMA (%)"
    value: 5
  - type: "OTRAS (%)"
    value: 8  

#-----------------#
#- chart options -#
#-----------------#
options:
  angleField: "value"
  colorField: "type"
  radius: 0.8
  legend:
    layout: "horizontal"
    position: "BOTTOM"
```
[Fuente]([Qué porcentaje del mercado de combustibles tiene cada petrolera - Forbes Argentina](https://www.forbesargentina.com/money/que-porcentaje-mercado-combustibles-tiene-cada-petrolera-n49490)) Revista Forbes. Marzo 2024

# Industrialización del Petróleo

## Recepción y Preparación del Crudo

## Transporte y almacenamiento del crudo

En Argentina, el transporte de crudo se realiza principalmente a través de oleoductos. Los oleoductos más importantes están en las principales cuencas petroleras, como la Cuenca Neuquina, la Cuenca del Golfo San Jorge y la Cuenca Noroeste.

El principal oleoducto, conocido como el Oleoducto Troncal, conecta Vaca Muerta con refinerías y puertos. Además, hay otros oleoductos como el de Oldelval, que transporta crudo desde Neuquén hasta Bahía Blanca.

En cuanto a volúmenes, se transportan varios cientos de miles de barriles diarios. Por ejemplo, el Oleoducto Oldelval puede transportar alrededor de 36.000 metros cúbicos diarios. Es un sistema clave para la industria petrolera del país.

Yacimientos y Oleoductos de Argentina:
 [[Cuencas Argentina.pdf]]
- [[Cuenca Cuyana.pdf]]
- [[Cuenca Austral.pdf]]
- [[Cuenta Noroeste.pdf]]
- [[Cuenca Neuquina.pdf]]
- [[Cuenca Golfo de San Jorge.pdf]]
### Desalado
El desalador es un equipo utilizado en la refinación de petróleo para eliminar las impurezas presentes en el crudo antes de su procesamiento en la columna de destilación. Su principal función es eliminar sales, agua y sólidos en suspensión, que pueden causar problemas de corrosión y formación de depósitos en los equipos de la refinería.

### **Funcionamiento del Desalador**

1. **Precalentamiento del Crudo**: Antes de ingresar al desalador, el crudo se calienta a aproximadamente 120-140 °C para reducir su viscosidad y mejorar la separación de las impurezas.
    
2. **Inyección de Agua de Lavado**: Se inyecta agua exenta de sales (agua de lavado), lo que permite disolver las sales presentes en el crudo y formar pequeñas gotas de agua salina.
    
3. **Mezclado y Emulsificación**: Se utilizan válvulas emulsificadoras o mezcladores estáticos para favorecer la dispersión del agua en el crudo.
    
4. **Aplicación de Campo Eléctrico**: La mezcla se introduce en el desalador, donde un campo eléctrico de alto voltaje (aproximadamente 20.000 V) hace que las pequeñas gotas de agua se unan y formen gotas más grandes.
    
5. **Decantación y Separación**: Las gotas de agua más grandes decantan y se separan del crudo, eliminando las sales y otras impurezas disueltas en ellas.
    
6. **Inyección de Solución Cáustica**: Se inyecta una solución de hidróxido de sodio (soda cáustica) para transformar los cloruros de calcio y magnesio en cloruro de sodio, minimizando la generación de ácido clorhídrico y reduciendo el riesgo de corrosión en los equipos posteriores.
    
7. **Salida del Crudo Desalado**: Finalmente, el crudo libre de sales y agua sale por la parte superior del equipo y se dirige al horno de precalentamiento antes de ingresar a la destilación atmosférica.
    

El proceso de desalado es crucial para garantizar la eficiencia y la seguridad de la refinación del petróleo, ya que evita la corrosión en los equipos, mejora la eficiencia de la destilación y reduce la formación de residuos sólidos en las unidades de procesamiento​.

1. **Destilación Atmosférica** (Topping)
    
    - Separación del crudo en fracciones:
        
        - Gases ligeros (GLP)
            
        - Nafta liviana y pesada
            
        - Kerosene
            
        - Gasoil
            
        - Residuo atmosférico
            
2. **Destilación al Vacío**
    
    - Procesamiento del residuo atmosférico para obtener:
        
        - Gasoil de vacío (GOV)
            
        - Residuo de vacío (base para procesos posteriores)
            
3. **Procesos de Conversión**
    
    - **Craqueo Catalítico:** Convierte fracciones pesadas en gasolinas de alto octanaje, GLP y gasoil ligero. Se realiza a 500-550°C y baja presión (~3-4 kg/cm²) con un catalizador de zeolitas. Optimiza el rendimiento de gasolina y requiere hidrotratamiento posterior para eliminar impurezas.
        
    - **Hidrocraqueo**: Proceso de conversión de fracciones pesadas en productos más livianos con menor contenido de azufre mediante el uso de hidrógeno a altas presiones (80-160 kg/cm²) y temperaturas (350-450°C). Se utiliza un catalizador a base de molibdeno y níquel o cobalto sobre alúmina, permitiendo la ruptura de moléculas grandes en hidrocarburos más ligeros, como diésel de alto índice de cetano, querosenos y naftas. Este proceso también reduce la presencia de compuestos aromáticos y mejora la estabilidad de los productos finales.
        
    - **Craqueo Térmico (Coquización)**: Proceso en el que los residuos pesados del crudo, como el residuo de vacío, se someten a altas temperaturas (450-550°C) y presiones moderadas para romper las moléculas grandes en productos más ligeros. Este proceso genera gasoil, naftas y coque de petróleo, un sólido rico en carbono utilizado como combustible o materia prima en la industria metalúrgica. Se emplean diversas técnicas, como el coque retardado, el coque fluido y la visbreaking, dependiendo del tipo de producto deseado y la configuración de la refinería.
        
4. **Tratamientos de Mejora de Calidad**
    
    - **Hidrotratamiento**: Eliminación de azufre y contaminantes.
        
    - **Reformado Catalítico**: Proceso que incrementa el octanaje de la nafta mediante la conversión de hidrocarburos nafténicos y parafínicos en aromáticos y isómeros de mayor octanaje. Se realiza a temperaturas de 490-530°C y presiones de 3-16 kg/cm² en presencia de un catalizador de platino sobre alúmina. Además, genera hidrógeno como subproducto, el cual es utilizado en otros procesos de refinación como el hidrotratamiento.
        
    - **Isomerización**: Mejora la calidad de las gasolinas al aumentar su octanaje.


- **Procesos Petroquímicos**
    
    - **Complejo de Aromáticos**:
        
        - **Inputs:** Nafta reformada, hidrógeno.
            
        - **Outputs:** Benceno, tolueno y xilenos, utilizados en la producción de plásticos, resinas y solventes.
            
    - **Complejo de Olefinas**:
        
        - **Inputs:** Etano, propano, nafta ligera.
            
        - **Outputs:** Etileno, propileno y butadieno, esenciales para la fabricación de polímeros.
            
    - **Anhídrido Maleico (MAN)**:
        
        - **Inputs:** Butano.
            
        - **Outputs:** Resinas de poliéster, adhesivos y plastificantes.
            
    - **Poliisobutileno (PIB)**:
        
        - **Inputs:** Isobuteno.
            
        - **Outputs:** Lubricantes sintéticos, adhesivos y selladores industriales.
            
    - **Alquilbenceno Lineal (LAB)**:
        
        - **Inputs:** Benceno, parafinas lineales.
            
        - **Outputs:** Detergentes biodegradables, ampliamente utilizados en la industria de limpieza y cosmética.
   

**Producción de Lubricantes y Asfaltos**
   - **Desasfaltado (PDA)**: Eliminación de residuos pesados.
   - **Extracción con Furfural**: Mejora la estabilidad de los lubricantes.  
   - **Hidrotratamiento de Aceites**: Producción de aceites de alta calidad.

**Mezclas y Almacenamiento**
    - **Blending de gasolinas** (super y premium)
    - **Blending de gasoils** (grados 1, 2 y 3)
    - **Almacenamiento y despacho** para distribución.

