Netword Address Traslation 

[Tipos de NAT]

[Estático:]
Existe una relación de uno a uno, una IP privada se asocia a una IP publica. 

[Dinámico:]
Existe un pool de de IPs publicas asociadas en el router. si un nodo interno necesita salir al exterior el router le asignara una de las IPs publicas que no este en uso. Para que pueda realizar la conectividad: 

[Sobrecargado [Port Address Traslation:]]
esta modularidad permite utilizar una única IP publica, pero asociando puertos distintos por cada IP Privada. Cada vez que una IP privada quiera salir, se le asigna un puerto dinámico y se asocia con un la IP Publica ese puerto dinámico. Al retornar, basada en su puerto se puede recuperar la IP privada para realizar el redireccionamiento de trafico.

