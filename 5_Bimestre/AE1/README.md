<img src="https://github.com/hernancontigiani/ceia_memorias_especializacion/raw/master/Figures/logoFIUBA.jpg" width="500" align="center">

# Algoritmos Evolutivos — Panadería 24 h

Repositorio asociado al trabajo práctico de la materia **Algoritmos Evolutivos I (CEIA - UBA)**.  
Autor: **Juan Cruz Ojeda**  
Cohorte: 19Co2024  

---

## Descripción

Este proyecto modela la planificación de turnos en una **panadería que opera las 24 h**, con el objetivo de cubrir una demanda horaria variable al **menor costo laboral posible**.  

El problema se aborda mediante un **algoritmo genético** implementado con la biblioteca **DEAP** en Python. El código optimiza la asignación de empleados a cada franja horaria considerando:

- Disponibilidad individual de cada empleado.  
- Límite máximo de horas por día y de horas consecutivas.  
- Penalización por bloques aislados de 1 h y por el patrón 1‑0‑1.  
- Adicional por trabajo nocturno.  
- Bonificación por continuidad de turnos.  

---

## Requisitos

- Python ≥ 3.10  
- [DEAP](https://deap.readthedocs.io/en/master/) ≥ 1.4  
- matplotlib, numpy  

Instalación rápida:
```bash
pip install deap matplotlib numpy
```

---

## Ejecución

Desde consola o Google Colab:
```python
!python panaderia_24h.py
```
