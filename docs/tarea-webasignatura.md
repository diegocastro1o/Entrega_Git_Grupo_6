# Tarea: Git+Markdown - Onboarding · Equipo Campus U1

## Onboarding

Bienvenido/a.

Te integras al equipo de desarrollo de Campus U1, una aplicación que será el sistema documental académico a nivel universitario.

El proyecto ya está en marcha y el equipo trabaja con prácticas profesionales de control de versiones. 
Como nuevo integrante, tu primera tarea es incorporarte al flujo de trabajo y comenzar a contribuir.

En las últimas reuniones de coordinación surgieron varios action items que necesitamos resolver. 
Estos están organizados como una serie de retos progresivos.

Tu objetivo no es solo “hacer que funcione”, sino trabajar como lo haría un equipo profesional:

- aislar cambios en ramas
- registrar avances con commits claros
- integrar cambios de forma controlada
- documentar decisiones

Es momento de empezar.

## Inicio del trabajo

En una carpeta de tu disco, ejecuta:

```
git clone https://github.com/ucudal/Fundamentos_Ciencias_Computacion_Ejercicio_U3.git
```

Luego ingresa al repositorio:

```
cd Fundamentos_Ciencias_Computacion_Ejercicio_U3
```

Dentro de la carpeta:

```
retos/
```

encontrarás los archivos:

- `reto1.md`
- `reto2.md`
- `reto3.md`
- `reto4.md`
- `reto5.md`

Cada archivo representa una tarea concreta del equipo.

## Desarrollo

A medida que avances:

- trabaja utilizando ramas, commits y merges según se indique
- mantén un historial claro y ordenado
- evita mezclar tareas en un mismo commit

Además, deberás documentar tu trabajo en:

```
docs/reporte-retos.md
```

Este archivo forma parte del repositorio y actúa como registro de tu trabajo dentro del equipo.

Para cada reto debes completar:

- **Comandos usados**
- **Decisiones tomadas**
- **Dificultades (opcional)**

## Documentación de apoyo

El equipo ya dejó documentación interna que puedes consultar:

- `docs/flujo_trabajo.md`
- `docs/comandos.md`
- `docs/troubleshooting.md`

Utiliza estos recursos como lo harías en un entorno profesional: para avanzar con autonomía y reducir errores.

## Entregable

La entrega consta de un único archivo:

```
nombre.apellido.bundle
```

Este archivo representa una copia completa de tu repositorio de trabajo e incluye:

- historial de commits
- ramas
- merges
- archivo `docs/reporte-retos.md` completo

## Cómo generar la entrega

Antes de generar el entregable, asegúrate de que tu trabajo esté correctamente registrado:

```
git add docs/reporte-retos.md 
git commit -m "docs: agrega reporte final de retos"
```

Luego genera el bundle:

```
git bundle create nombre.apellido.bundle --all
```

Sube el archivo `.bundle` en esta tarea de Webasignatura.

## Criterios de evaluación

### Misiones

- Reto 1: 10 puntos
- Reto 2: 15 puntos
- Reto 3: 20 puntos
- Reto 4: 30 puntos
- Reto 5: 15 puntos

**Total base: 90 puntos**

### Bonificaciones

- +5 por commits con mensajes claros y consistentes
- +5 por resolución autónoma de conflictos
- +5 por explicación clara en el reporte

### Penalizaciones

- -3 por commits con mensajes poco descriptivos
- -3 por mezclar varias misiones en un mismo commit
- -5 por realizar merges sin revisión previa (git status, git diff)

### Consideraciones

- El repositorio debe ser consistente con el reporte entregado.
- El archivo `docs/reporte-retos.md` debe reflejar el proceso realizado.
- El bundle debe incluir el commit final con el reporte.
- Se valorará tanto el resultado técnico como la claridad del proceso.

### Nota final

Este trabajo simula la incorporación a un equipo real de desarrollo.

No solo evaluamos si lograste el resultado, sino cómo trabajaste:

- cómo organizaste tus cambios
- cómo integraste el trabajo
- cómo explicaste tus decisiones

Las bonificaciones permiten compensar errores menores, priorizando buenas prácticas profesionales en el uso de Git.

