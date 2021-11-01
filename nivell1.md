# **Java** (```llenguatge de programació```)

El **Java** és un ```[llenguatge de programació]``` dissenyat el 1990 per James Gosling amb altres companys de Sun Microsystems a partir del llenguatge C. Des del seu naixement fou pensat com un llenguatge orientat a objectes. Entre el 13 de novembre de 2006 i el maig del 2007 Sun va alliberar parts de **Java** com a programari lliure de codi obert amb llicència GPL. És un dels llenguatges de programació més utilitzats, i s'utilitza tant per aplicacions web com per aplicacions d'escriptori.

![alt text](https://recursos.bps.com.es/files/1022/21_408x269.jpg "Logo Java")




- Característiques de **Java**
- Tipus de Dades
- _Sintaxi_ 

## Característiques de **Java**

-**Senzill**: Java s'ha creat perquè sigui un llenguatge senzill amb una _Sintaxi_ elegant. Únicament consta de tres tipus de dades primàries, eliminant els punters i l'herència múltiple

-**Orientat a objectes**: **Java** segueix els paradigmes de la programació orientada a objectes, ja que la programació amb **Java** se centralitza en la manipulació, creació i construcció d'objectes.

-**Distribuït**: **Java** permet la construcció d'aplicacions distribuïdes per mitjà d'una col·lecció específica de classes.

-**Interpretat**: Es necessita un intèrpret per executar els programes de **Java**, això alenteix als programes però els hi dona flexibilitat.

-**Robust**: **Java** és un llenguatge robust i fiable, s'ha escrit pensant a poder verificar errors i està molt tipificat.

-**Segur**: **Java** té pocs problemes de seguretat, característica molt important en les aplicacions distribuïdes d'Internet.

-Arquitectura neutral**: **Java** és independent de la plataforma final on s'executarà el programa.

-**Portable**: **Java** és un llenguatge d'alt nivell i de plataforma independent, això li dona portabilitat.

-**Alt rendiment**: Els _compiladors_ **Java** han anat millorant les seves prestacions. Els nous _compiladors_


## Tipus de Dades

Els tipus de dades fan referència al tipus d'informació que es treballa, on la unitat mínima d'emmagatzematge és la dada, també es pot considerar com el rang de valors que pot prendre una variable durant l'execució del programa.

Els tipus primitius en **Java** tenen la mateixa mida en cada implementació menys els tipus booleans que pot variar.


| Tipus                          | Paraula reservada | Mida (bits)| Mida (bytes) | Valor mínim | Valor màxim     |
| :---                           |      :----:       |   :----:   |    :----:    |    :----:   |     ---:        |
| Booleà                         | boolean           |  --        | --           | --          | --              |
| Byte enter                     | byte              | 8-bit      | Header     | -128          | +127            |
| Caràcter                       | char              | 16-bit     | Header     | Unicode 0     | unicode2^16 - 1 |
| Enter curt                     | short             | 16-bit     | Header     | -2^15         | +2^15 -1        |
| Enter                          | int               | 32-bit     | Header     | -2^31         | +2^31 -1        |
| Enter llarg                    | long              | 64-bit     | Header     | -2^63         | +2^63 -1        |
| Punt flotant                   | float             | 32-bit     | Header     |  [IEEE 754](https://ca.wikipedia.org/wiki/IEEE_754)      |  [IEEE 754](https://ca.wikipedia.org/wiki/IEEE_754)       |
| Punt flotant de doble presició | 64-bit            | 64-bit   | Header     |  [IEEE 754](https://ca.wikipedia.org/wiki/IEEE_754)      |  [IEEE 754](https://ca.wikipedia.org/wiki/IEEE_754/)        |


## _Sintaxi_ 

La _Sintaxi_ del **Java** deriva en gran part del ```C```. Però a diferència d'aquest, que combina la _Sintaxi_ per a programació genèrica, estructurada i orientada a objectes, el **Java** va ser dissenyat gairebé exclusivament com a llenguatge orientat a objectes. Tot el codi es troba dins d'una classe, i tot és un objecte (excepte nombres ordinals i reals, booleans i caràcters per motius de rendiment).

Utilitza mètodes per comentar similars al C. Hi ha diferents tipus de comentari: una sola línia amb dues barres obliqües, múltiples línies començades per ```/* i acabades amb */```, i el tipus de comentari de _Javadoc_ que comença amb una barra obliqua i dos asteriscs i acaba amb ```*/```. L'estil _Javadoc_ permet fer córrer l'executable de _Javadoc_ per compilar la documentació del programa. 

 
 #### Hola Món
 
 ```java
 // Hola.java
import java.io.IOException;
public class Hola {
    public static void main(String[] args)throws IOException {
        System.out.println("Hola, món!"); 
    }
}
 ```


[Referencia per fer el markdown](https://ca.wikipedia.org/wiki/Java_(llenguatge_de_programació))






