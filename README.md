# light-bulb
_Este proyecto es un ejemplo de un prototipo que hace uso de MQTT para simular el comportamiento de una ampolleta (light bulb) con internet capaz de ser encendida y apagada con un interruptor remoto a través de MQTT._

_La finalidad principal de este ejemplo es demostrar cómo se puede sacar provecho de la propiedad de mensaje retenido de MQTT que consiste en conservar la última publicación a un tópico para que esta pueda ser enviada cuando un cliente se suscriba a ese tópico en particular y así conocer el último estado._

_Gracias a esta propiedad podemos prototipar de forma rápida una aplicación de estas características sin la necesidad de hacer uso de una base de datos o de un servidor que maneje una  cierta lógica._

## Comenzando 🚀

_Para obtener una copia de este proyecto sólo es necesario descargarlo o clonarlo directamente desde GitHub._

Mira **Instalación** para conocer como desplegar el proyecto.


### Pre-requisitos 📋

_El único requisito para poder probar este ejemplo es tener un navegador instalado._

_De forma opcional pueden utilizar su propio Broker MQTT. En aquel caso el pre-requisito sería contar con este Broker, ya sea de forma local o en internet._

_Ya que este prototipo no tiene código del lado del servidor, no es necesario utilizar un servidor web, se puede abrir directamente con un navegador._

### Instalación 🔧

_Este prototipo no requiere de ninguna instalación, es tan sencillo como clonar el repositorio o descargarlo directamente desde GitHub, entrar al proyecto y abrir ambos archivos html (light-bulb.html y switch.html) con un navegador a elección._

_Si se está utilizando un Broker MQTT propio se deben modificar los datos de conexión en ambos archivos._

_Se encuentra una copia de este prototipo funcionando en [este link](http://educate.swarm.cl/light-bulb/)._
## Construido con 🛠️

* [Paho](https://www.eclipse.org/paho/clients/js/) - Cliente MQTT usado por los ejemplos web de MQTT
* [Bootstrap 4](https://getbootstrap.com/) - Framework CSS

## Autores ✒️

* **Daniel Pérez** - *Desarrollo de los ejemplos y comentarios en código*
* **Samuel Muñoz** - *Test*
---
⌨️ con ❤️ por [Swarm Technologies](https://github.com/swarmtechnologies) 😊