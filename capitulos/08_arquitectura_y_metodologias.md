# Arquitectura y metodologias

La arquitectura cambia dependiendo de la metodologia (siendo tradicional o la agil)

**Metodologias tradicionales**: Encontrar los problemas y realizar una solucion a gran escala que ataque a esos problemas de alto riesgo

**Metodologias agiles**: Plantean que la arqquitectura emerge de un equipo autogestionado y por ende ven a el diseño como algo evolutivo que se va dando sprint a sprint. Se PLANEAN MOMENTO. no adelantes una decision que puede ser postergada

![metodologia tradicional](../assets/02_metod_tradicional.png)
![metodologia agil](../assets/03_metod_agil.png)





La arquitectura nace en metodologías tradicionales en donde su objetivo era principalmente encontrar los problemas y diseñar una solución a gran escala que ataque a esos problemas esenciales, como también a los de alto riesgo del desarrollo a realizar.

Las metodologías Agiles plantean que la arquitectura emerge de un equipo auto-gestionado y por ende ven al diseño de una solución como algo evolutivo y que se va dando de sprint a sprint.

## Diferencias:

**Tradicional**: En la etapa de diseño es donde se tiene la definición del problema, requerimientos, restricciones y riesgos todos estos son los agentes que van ayudar al arquitecto a tomar decisiones, el arquitecto contara con herramientas de diseño para poder tomar esto como entrada, para luego tener un modelo de la arquitectura y la documentación para implementar ese modelo, la etapa de diseño no implementa software, sino que le da a la etapa de desarrollo las herramientas para implementar lo que se analizó, al modelo tradicional lo que le falta es el feedback ya que el arquitecto no tiene nociones de lo que el sistema ya hace y como el usuario interactúa con ese sistema, hasta que el arquitecto no hace toda esa solución y la solución no se implementa y se despliega no se tiene feedback de como esas decisiones son tomadas o si son buenas decisiones.

**Agile**: En la metodología ágil todo se trata de momentos en donde podemos evaluar o reevaluar nuestras decisiones, esto se realiza en el planeamiento del spring que es donde planeamos los momentos arquitectónicos importantes. Una vez planeado el spring y se define lo que se tiene que definir arquitectónicamente se ejecuta en base a las prioridades que se tienen y luego se le lleva al usuario haciendo el despliegue y gracias a eso se obtiene feedback, cabe destacar que una vez que se obtiene feedback se pueden reevaluar las decisiones de la arquitectura.

## Articulos

- [patrones de desarrollo y evolucion de la arquitectura usados en un proyecto de software con metodologia agil](http://hillside.net/plop/2015/papers/riverhounds/17.pdf)
- [Link de pdf que compara metodologias agiles con las tradicionales](http://www.revistaespirales.com/index.php/es/article/view/269/225)