## Marco General

Bienvenido a la tarea de anotación de productos de Mercado Público. En esta tarea te presentamos un texto que describe un producto vendido y te pediremos que lo clasifiques con una categoría general. Utilizaremos estos datos para construir un algoritmo que sea capaz de reconocer la categoría de un producto, en base a los textos que lo describen 

## Conceptos

Nos gustaría que clasificaras cada producto  en alguna de las siguientes categorías: *'CREDENCIALES', 'ESTAMPILLAS MUNICIPALES', 'LICENCIAS DE CONDUCIR', 'LICENCIAS MÉDICAS' o 'SERVICIOS DE CUSTODIA'*. Cada uno de los registros sólo puede tener una clase, es decir, cada registro corresponde a un solo producto.

### Clases o Categorías
Por cada producto, por favor selecciona alguna de las siguientes categorías.
 * **CREDENCIALES**: Existen procesos dentro de las actividades que realizan los Servicios Públicos, que requieren que quién lo esté realizando porte una identificación, generalmente esta corresponde a una credencial. Ejemplo de esta categoría son los siguientes textos:
   *  "credenciales postulantes despachar a plaza prat 570  iquique hojas o folletos de instrucciones 1223790  folleto 1249795 productos impresos y publicaciones medios impresos publicaciones impresas"  
   *  "adquisición de credenciales identificatorias 200 credenciales identificatorias  según diseño adjunto  y accesorios complementarios  requeridas con motivo de programa promoción de la comuna y posicionamiento de la imagen institucional  decreto n°1 276 de fecha 08 de septiembre de 2021 marcadores de identificación credencial pvc impresa en alta calidad  full color por ambos lados  en tamaño carnet  según diseño referencial adjunto  diseño definitivo será enviado junto a orden de compra productos impresos y publicaciones etiquetado y accesorios etiquetado" 
   
* **ESTAMPILLAS MUNICIPALES**: Los municipios requieren de estampillas para franqueo. Ejemplo de esta categoría son los siguientes textos:
   * "estampillas franqueo municipal para la adquisicion de 100 estampillas para el franqueo municipal  dispensador de estampillas 100 estampillas para el franqueo municipal equipos, accesorios y suministros de oficina suministros de oficina suministros de escritorio" 
   * "insumos tesoreria compra de insumos para tesoreria municipal impresión de valores o instrumentos financieros estampilla municipal  500 servicios editoriales, de diseño, publicidad, gráficos y artistas servicios de impresión y reproducción impresión" 
  
* **LICENCIAS DE CONDUCIR**: Otro de los productos de interes corresponde a la impresión de documentos relacionados a las licencias de conducir. Ejemplo de esta categoría son los siguientes textos:
   * "contratacion directa  licencias de conducir	 formularios para licencias de conducir  con termosellables de seguridad  decreto exento nro 1606 de fecha 09 de junio del 2015  formularios o cuestionarios comerciales formularios para licencias de conducir  con termosellables de seguridad  decreto exento nro 1606 de fecha 09 de junio del 2015 productos de papel productos de papel papeles comerciales"
   * "2 000 licencias de conducir con termosellado 2 000 licencias de conducir con termosellado  tesoreria  solicitud n°478231 - impresión de papelería o formularios comerciales 2 000 licencias de conducir con termosellado servicios editoriales, de diseño, publicidad, gráficos y artistas servicios de impresión y reproducción impresión"

* **LICENCIAS MÉDICAS**: Cada Servicio de Salud requiere talonarios de recetas médicas para ser utilizados en los centros de salud, estas compras, en general, se centralizan a través de la CENABAST. Ejemplo de esta categoría son los siguientes textos:
   * "talonario de licencias medicas licencia medica dr  hugo martinez res  nº 2018 c c  210 talones o talonarios compra talonario licencia médica  institucional para dr  hugo martinez gálvez  rut  6 449 001 k productos de papel productos de papel papeles comerciales"
   * "compra talonarios de licencias medicas talonarios de licencias nros: 27627001-27627050/27627051-27627100  compra inferior a tres utm  talones o talonarios talonarios de licencias nros   27627001 27627050 27627051 27627100 productos de papel productos de papel papeles comerciales"

* **SERVICIOS DE CUSTODIA**: En ciertas ocasiones los Servicios Públicos requieren de espacios para guardar documentos físicos que deben archivarse por largos períodos de tiempo. Ejemplo de esta categoría son los siguientes textos:
   * "orden de compra desde 2686-2-lq17 servicio de administración  almacenaje  custodia desde 2686-2-lq17  $ 1 471 775 - mensual por 4 años   duración del contrato:  hasta el 30/11/2020  servicios de almacenaje de documentos retiros servicios de transporte, almacenaje y correo almacenaje depósito y almacenaje especializado"
   * "suministro del servicio de almacenaje y custodia de la documentación emanada de los proce incluir n° de oc en doc  tributario   indicar unidad requirente en doc  tributario  pagos desde el 01 05 2020 son realizados por tgr - dipres  para cualquier información dirigirse a dipresrecepcion@custodium com fomento  memo 12 1-418 servicios de almacenaje de documentos servicio de almacenaje y custodia de la documentación emanada de los procesos de fondos concursables correspondiente al periodo del 28 de julio de 2022 hasta el 27 de agosto de 2022 servicios de transporte, almacenaje y correo almacenaje depósito y almacenaje especializado"
