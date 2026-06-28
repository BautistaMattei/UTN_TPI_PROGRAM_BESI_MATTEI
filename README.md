

**Trabajo Práctico Integrador (TPI) — Programación 1**  
Tecnicatura Universitaria en Programación — UTN  

**Integrantes:** Bautista Mattei y Santiago Andres Besi

---

## Descripción

Aplicación de consola en Python 3 que permite gestionar un dataset de países almacenado en un archivo CSV. Implementa búsquedas, filtros, ordenamientos y estadísticas utilizando listas, diccionarios y funciones modularizadas.

---

## Estructura del proyecto

```
UTN_TPI_PROGRAM_BESI_MATTEI/
├── Main.py        # Código fuente principal
├── paises.csv     # Dataset base con 42 países
└── README.md      # Este archivo


## Funcionalidades

| Opción | Descripción |
|--------|-------------|
| 1 | Mostrar todos los países |
| 2 | Agregar un nuevo país |
| 3 | Actualizar población, superficie y/o continente |
| 4 | Buscar por nombre (parcial o exacto) |
| 5 | Filtrar por continente, rango de población o superficie |
| 6 | Ordenar por nombre, población o superficie (asc/desc) |
| 7 | Estadísticas: mayor/menor población, promedios, países por continente |
| 0 | Salir |



## Ejemplos de entrada/salida

### Mostrar países (opción 1)

==========================================================================================
NOMBRE              POBLACION      SUPERFICIE     CONTINENTE
==========================================================================================
Argentina           45376768       2780400        America
Brasil              213993437      8515767        America


### Buscar país (opción 4)

=== BUSCAR PAIS ===
Ingrese el nombre del país que desea buscar (total o parcial): arg

NOMBRE              POBLACION      SUPERFICIE     CONTINENTE
==========================================================================================
Argentina           45376768       2780400        America


### Filtrar por continente (opción 5 → 1)

=== FILTRAR POR CONTINENTE ===
Continente: Europa

NOMBRE              POBLACION      SUPERFICIE     CONTINENTE
==========================================================================================
Alemania            83149300       357022         Europa
Francia             67390000       551695         Europa
España              47450795       505990         Europa


### Ordenar por población descendente (opción 6 → 2)

=== ORDENAR POR POBLACIÓN ===
A Ascendente / D Descendente: D

NOMBRE              POBLACION      SUPERFICIE     CONTINENTE
==========================================================================================
India               1428600000     3287263        Asia
China               1412600000     9596961        Asia


### Estadísticas (opción 7)

=== ESTADÍSTICAS ===
Mayor población : India (1,428,600,000)
Menor población : Uruguay (3,574,964)
Promedio población : 146,988,926.29
Promedio superficie: 1,927,860.50 km²

Cantidad de países por continente:
  Africa: 9
  America: 12
  Asia: 10
  Europa: 8
  Oceania: 3



## Formato del CSV


nombre,poblacion,superficie,continente
Argentina,45376768,2780400,America
Japon,125800000,377975,Asia
```

**Reglas:**
- Sin campos vacíos
- `poblacion` y `superficie` deben ser enteros positivos
- No se permiten nombres duplicados


## Video demostrativo

> 🔗 **[Insertar enlace al video aquí]**

## Documentación PDF

> 🔗 **[Insertar enlace al PDF aquí]**





