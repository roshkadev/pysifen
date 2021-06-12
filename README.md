# PYSIFEN

`pysifen` es una librería de código abierto, con pocas dependencias externas, para interactuar con SIFEN (Sistema
Integrado de Factura Electrónica Nacional) a través de Python.

## Instalación

## Servicios Web de SIFEN

- Consulta de RUC
- Recepción de Documento Electrónico - Síncrono
- Consulta de Documentos Electrónicos
- Recepción de Lote de Documentos Electrónicos - Asíncrono
- Consulta de Estado de Documentos Electrónicos (Lote)
- Recepción de Eventos

## Uso

***Importante: Leer
el [Manual Técnico de Sifen](https://ekuatia.set.gov.py/rest/contents/download/collaboration/sites/ekuatia/documents/documentacion/documentacion-tecnica/Manual+T%C3%A9cnico+Versi%C3%B3n+150.pdf)
y entender el funcionamiento básico antes de continuar con la guía de uso de esta librería.***

### Configuración

### Consulta de RUC

El uso del servicio web de Consulta de RUC se puede realizar de la siguiente forma:

```python
import so
```

El parámetro es el RUC del contribuyente a consultar, sin el DV (Dígito Verificador).

Para ver la estructura de la respuesta a esta consulta, revisar el Manual Técnico de Sifen, cuyo enlace se encuentra al
principio de esta sección.

## Sugerencias

Si tenés alguna duda o consulta, o encontraste un comportamiento incorrecto dentro de la librería, no dudes en crear
un *issue*.

## Contribución

Cualquier contribución es siempre bienvenida. Por favor, crear primero un *issue* para discutir los cambios a ser
realizados.

## Licencia

`pysifen` está licenciada bajo el MIT License. Ver el archivo [LICENCIA.md](LICENCIA.md) para más detalles.

## Empresas usuarias de pysifen

Algunas empresas que utilizan esta librería en producción para sus implementaciones de SIFEN (*) son:

(*) ¿Querés agregar la tuya? Envianos un [email](mailto:pablo@roshka.com.py) para incluirla. 

## Autores y Responsables

- Pablo Santa Cruz ([github/pablo](https://github.com/pablo))