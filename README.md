# Proyecto API con GitHub Actions – CI Automatizado

**Grupo 5:**
- Juan Villaman  
- Cristóbal de Jesus  
- Victor Figueroa

## Descripción del Proyecto
Automatización de Pruebas en una API de Inmobiliaria, utilizando las herramientas aprendidas en los trabajos anteriores.

---

### Entregables:

## ¿Qué importancia tiene probar en múltiples entornos de Node.js?

  La principal importancia es detectar errores, por ejemplo al validar las versiones 16 y 18, la primera nos mostraba error por lo cual entendimos que no cualquier version se puede utilizar.
  Tambien aquello nos ayudara a detectar errores futuros ya que como bien se sabe cada version incluye mejora por lo que tambien se valido con la version 19.x
  Lo anterior va de la mano con garantizar la integridad y las fallas en nuestros builds y por supuesto mejora la calidad de nuestro desarrollo.
  
## ¿Por qué es importante validar la salida de una API desde un workflow?

  La importancia de validar la salida de una API es ya que podemos velar los datos entregados y que estos sean correctos, ya que con ello podemos detectar problemas o errores posteriores.
  Con lo anterior podemos, tambien, auditar los datos y así sacar conclusiones ejecutivas, nos permite mejorar ya sabremos donde atacar el problema.
  
## ¿Qué pasos podrías agregar si fueras a hacer despliegue a producción?

  Se podrian agregar distintos tipos de pruebas (unitarias, integracion)
  Revisar dependencias y versiones, tal como en el ejemplo.
  Revisar recuros del sistema, en nuestro ejemplo vimos como se comportaba el cache.
  Usar herramientas como Git Actions o Jenkins para el despliegue
  Pruebas post despliegues, revisar logs por ejemplo.

## ¿Qué limitaciones tiene GitHub Actions y cómo las enfrentarías?

  La primera limitancia y mas importante detectada es su uso, ya que se limita en minutos, tambien los jobs corriendo en simultaneo ya que el espacio es limitados, a nivel de seguridad los secretos se pueden filtrar si no se controlan.
  Como enfrentar lo antes mencionado es revisando en internet como solucionar los problemas puntuales por cada caso, ya que para todo hay solucion, en caso contrario buscar una herramienta de pago como gitlab.

---
