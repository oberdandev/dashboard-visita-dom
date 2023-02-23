# Dashboard Visita Domiciliar - SEMSA

Abordagem da construção do dashboard de Visita Domiciliar dos ACS's realizado pela equipe de Inteligência de Dados da SEMSA. Distrito Sul e Oeste.


# Índice
- [Ideia](#ideia)
- [Proposta](#proposta)
- [Objetivos](#objetivos)
- [Metodologia](#metodologia)
- [Indicadores](#Indicadores)
  - [Indicador de visitas realizadas](#indicador1) 
  - [Indicador de visitas realizadas a diferentes usuários](#indicador2)


``` 
{
  "firstName": "John",
  "lastName": "Smith", 
  "age": 25
} 
```


## Indicadores <a id=#Indicadores></a>

### 1. Indicador de Visitas Realizadas


```math
 IVR = \frac{x-x_{min}}{x_{max}-x_{min}} 
```
**em que:**
- **x** é a **quantidade de visitas** realizadas em determinado **intervalo de tempo**;
- **x_max** é o ==maior valor== registrado de visitas realizadas em determinado intervalo de tempo;
- **x_min** é o ==menor valor== registrado de **visitas realizadas** em **determinado intervalo de tempo**;

### 2. Indicador de visitas realizadas a diferentes usuários {#indicador2}

> ```math
> IVR_{du} = \frac{y-y_{min}}{y_{max} - y_{min}} 
> ```


> \(E=mc^2\)，$$x_{1,2} = \frac{-b \pm \sqrt{b^2-4ac}}{2b}.$$

$$
a^2+b^2=c^2
$$

em que:
y é a quantidade de visitas realizadas em determinado intervalo de tempo;
y_max é o maior valor registrado de visitas realizadas em determinado intervalo de tempo;
y_min é o menor valor registrado de visitas realizadas em determinado intervalo de tempo;
