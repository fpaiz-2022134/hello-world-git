# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6


# Underlines

Underline 1
 ----------

 Underline 2
 ===========


# Formatos de enfasis
 - formato *italica* de la primer forma
 - formato _italica_ de la segunda forma
 - formato **bold o strong** de la primer forma
 - formato __bold o strong__ de la primer forma
 -formato ~~tachado~~, formato normal.
 - aqui podemos usar *formato italica*, o **bold** y ~~tachado~~


# Listas

1. Esto es un item.
2. Esto es un item.
3. Esto es un item.

- Esto es un item lista desordenada.
- Esto es un item lista desordenada.
- Esto es un item lista desordenada.

# Links

<a href = "http://google.com"> Link <a>
- [Esto es un link en markdown](http://google.com)
/ [Esto es un link al index](index.html)

# Imagenes

![Logo Github](https://github.githubassets.com/assets/GitHub-Mark-ea2971cee799.png)

# Code Snippets
Código en JSON
```JSON
    {
  "llave1": "valor1",
  "llave2": "valor2",
  "llave3": "valor3",
  "llave4": 7,
  "llave5": null,
  "favAmigos": ["Kolade", "Nithya", "Dammy", "Jack"],
  "favJugadores": {"uno": "Kante", "dos": "Hazard", "tres": "Didier"}
}

```
Código en JavaScript
```JavaScript
 function relojFecha(){
 	var mydate=new Date();var year=mydate.getYear();
 	if (year < 1000)year+=1900;
 	var day=mydate.getDay();
 	var month=mydate.getMonth();
 	var daym=mydate.getDate();
 	if (daym<10)daym="0"+daym;
 	var dayarray=new Array("Domingo","Lunes","Martes","Miercoles","Jueves","Viernes","Sabado");
 	var montharray=new Array("Enero","Febrero","Marzo","Abril","Mayo","Junio","Julio","Agosto",
 	                                             "Septiembre","Octubre","Noviembre","Diciembre");
 	var horas = mydate.getHours();
 	horas = (horas<10)?"0"+horas:horas;
 	var minutos = mydate.getMinutes();
 	minutos = (minutos<10)?"0"+minutos:minutos;
 	var segundos = mydate.getSeconds();
 	segundos = (segundos<10)?"0"+segundos:segundos;
 	document.getElementById("idReloj").innerHTML = "<"+"small><"+"font color='000000' face='Verdana'>"+
 	                                                dayarray[day]+" "+daym+" de "+montharray[month]+" de "+
                                                        year+" "+horas+":"+minutos+":"+segundos+"<"+"/font><"+"/small>";
 	setTimeout('relojFecha()',1000);

```

# Tablas

|   Nombre | Apellido | Documento |
|----------|----------|-----------|
| Franco  |  Paiz   | README    |
| Franco  |  Paiz   | README    |

# Citas
Esto es un texto referente  a una cita que pondremos debajo.

> Esto es una cita.

Otro texto no relacionado a la cita anterior

# Líneas divisoras

Esto es un texto que sera dividido.

---
Esto es otro texto 

***

Esto es otro texto divido por guiones bajos.

____

#Saltos de línea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista

