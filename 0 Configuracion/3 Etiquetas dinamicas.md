# Etiquetas inteligentes para el LLM

- Si la respuesta del LLM incluye los términos: reclamos, garantías, y además incluye el enlace o información de contacto del departamento de postventa (ej., [link_cargar_garantia] o <serviciotecnico@tromen.com>), asigna la etiqueta:
    `RECLAMOS POSTVENTA`

- Si la respuesta del LLM incluye los términos: pida instrucciones, ayuda, soporte, asistencia, asesoramiento, instalación, instalador, y además menciona la instalación de un producto Tromen, asigna la etiqueta:
    `INSTALACION (CONSULTAS)`

- Si la respuesta del LLM indica que el usuario quiere ofrecer algún producto o servicio a la empresa, quiere ser proveedor, o quiere vender productos o servicios a la empresa, asigna la etiqueta:
    `COMPRAS`

- Si la respuesta del LLM proporciona información sobre: dónde comprar, dónde adquirir, dónde conseguir, dónde obtener, dónde ordenar, dónde solicitar, dónde reservar, cómo puedo comprar, cómo adquirir, cómo obtener, cómo ordenar, cómo solicitar, cómo reservar, cómo apartar, cómo hacer el pedido, comparaciones, precios, características, asigna la etiqueta:
    `INFORMACION`

- Si la respuesta del LLM detecta que el usuario quiere ser distribuidor, o usa los términos: precios, costos, valores para reventa, comercializar, distribución, asigna la etiqueta:
    `VENTAS`

- Si la respuesta del LLM incluye los términos: reclamos, garantías, y además incluye el enlace o información de contacto del departamento de postventa (ej., [link_cargar_garantia] o <serviciotecnico@tromen.com>) y se refiere específicamente a equipos a gas (ej., salamandras a gas, estufas a gas, calefactores a gas, hornos a gas, parrillas a gas), asigna la etiqueta:
    `POSTVENTA GAS`

- Si la respuesta del LLM incluye los términos relacionados con marketing: promociones, publicidad, redes sociales, eventos, ferias, exposiciones, campañas publicitarias, estrategias de marketing o se proporciona el correo <info@tromen.com>, asigna la etiqueta:
    `MARKETING`

- Si la respuesta del LLM detecta interés en trabajar en la empresa, recibe un CV, recibe un CV de un ex trabajador, recibe un CV de un ex trabajador y pide una referencia, o recibe un CV de un ex trabajador y pide una carta de referencia, asigna la etiqueta:
    `RRHH (CV Y RECOMENDACION)`

---

| ID | Nombre etiqueta             | Uso                                                                                                                                                                                                                                                        |
|----|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | RECLAMOS POSTVENTA          | La respuesta del LLM incluye los términos: reclamos, garantías, y además incluye el enlace o información de contacto del departamento de postventa.                                                                                                        |
| 2  | INSTALACION (CONSULTAS)       | La respuesta del LLM incluye los términos: pida instrucciones, ayuda, soporte, asistencia, asesoramiento, instalación, instalador, y además menciona la instalación de un producto Tromen.                                                                |
| 3  | COMPRAS                      | La respuesta del LLM indica que el usuario quiere ofrecer algún producto o servicio a la empresa, quiere ser proveedor, o quiere vender productos o servicios a la empresa.                                                                                   |
| 4  | INFORMACION                   | La respuesta del LLM proporciona información sobre: dónde comprar, dónde adquirir, dónde conseguir, dónde obtener, dónde ordenar, dónde solicitar, dónde reservar, cómo puedo comprar, cómo adquirir, cómo obtener, cómo ordenar, cómo solicitar, cómo reservar, cómo apartar, cómo hacer el pedido, comparaciones, precios, características. |
| 5  | VENTAS                       | La respuesta del LLM detecta que el usuario quiere ser distribuidor, o usa los términos: precios, costos, valores para reventa, comercializar, distribución.                                                                                                  |
| 6  | POST VENTA GAS              | La respuesta del LLM incluye los términos: reclamos, garantías, y además incluye el enlace o información de contacto del departamento de postventa y se refiere específicamente a equipos a gas.                                                              |
| 7  | MARKETING                    | La respuesta del LLM incluye los términos relacionados con marketing: promociones, publicidad, redes sociales, eventos, ferias, exposiciones, campañas publicitarias, estrategias de marketing o se proporciona el correo <info@tromen.com>.                            |
| 8  | RRHH (CV Y RECOMENDACION) | La respuesta del LLM detecta interés en trabajar en la empresa, recibe un CV, recibe un CV de un ex trabajador, recibe un CV de un ex trabajador y pide una referencia, o recibe un CV de un ex trabajador y pide una carta de referencia.                          |