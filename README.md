# Simple Arduino Crypto Display

![alt text](https://i.imgur.com/QcoTabI.png "Display")

pantalla creada con un ESP8266 que obtiene precios de moneda en vivo directamente de la API [CoinMarketCap.com] (CoinMarketCap.com).

Intent� hacer este proyecto tan f�cil de hacer como sea posible. No hay soldadura y tampoco necesitas saber c�mo codificar. En total, deber�a tomar de 10 a 15 minutos


### Partes Necesarias

* [NodeMCU ESP8266 Board](http://bit.ly/2lUer9O)
* [OLED Display 1.3" version](http://bit.ly/2E96O6L)
* [Female-Female Dupont cables](http://bit.ly/2lUm4gE)

### Tiendas en las que encontrarlas
Geartbest:
* [NodeMCU ESP8266 Board](https://es.gearbest.com/transmitters-receivers-module/pp_366523.html?wid=23&lkid=12563384)
* [Female-Female Dupont cables](https://es.gearbest.com/diy-parts-components/pp_234611.html?wid=23&lkid=12563379)

Aliexpress:
* [NodeMCU ESP8266 Board](http://bit.ly/2lUer9O)
* [OLED Display 1.3" version](http://bit.ly/2E96O6L)
* [Female-Female Dupont cables](http://bit.ly/2lUm4gE)

### Cableado

Debe estar conectado de la siguiente manera

| Pin On Display| Pin on NodeMCU |
| ------------- |----------------|
| GND     | G |
| VCC     | 3V (some boards say 3.3V |
| SCL (Sometimes SCK)    | D5 |
| SDA     | D3 |

---

NOTA: Algunas pantallas tienen GND y VCC intercambiados, �siempre cablee como se indica arriba!

---
![alt text](https://i.imgur.com/jaC6E2S.jpg?1 "Warning")


![alt text](https://i.imgur.com/OrTd5SX.jpg "Wiring")
![alt text](https://i.imgur.com/0pLIPvH.png "Wiring to Screen")
![alt text](https://i.imgur.com/xgvBrwZ.png "Wiring to Board")
