# Actividad 11 - Gestión ágil de proyectos con GitHub Projects, configuración de Kanban Board y creación de historias de usuario

- Nombre: Andrew Owim Inga Rojas 
- Fecha: 21/10/2025
- Tiempo total: 5h
- Entorno usado: IDE Visual Studio Code y Github
## Instrucciones

### Parte 1: Configuración inicial
- **Tablero inicial:** Captura de "Devops-agile" con columnas predeterminadas.
![Kanban Board](./capturas/tablero-incial.png)
- **Columnas renombradas:** Ready -> **Icebox**, In Review -> **Review/QA**.
![1](./capturas/icebox.png)
![2](./capturas/review-qa.png)

#### Parte 2: issue template
- **Configuración:** *Settings > Features > Custom template*.
![template config](./capturas/template-config.png)
- **Template User Story:** Markdown de ejemplo.
![issue template](./capturas/issue-template.png)
####  Parte 3: creacion de historias de usario
- **7 Issues:**
  -  *Counter*, *Multiple Counters*, *Persist*, *Reset*, *Deploy*, *Remove*, *Update*
![Historias de usuario](./capturas/creacion-issue.png)

- **Límite:** *New Issues* con límite **7**.
![New issue (0/7)](./capturas/creacion-issue.png)
- **Priorización:** *Counter* al inicio de **Product Backlog**, *Multiple Counters* en **Icebox**, resto en **New Issues**.
![prioridad](./capturas/tablero-parte3.png)

####  Parte 4: refinamiento del backlog

- **Triage:** *Deploy* bajo *Persist*, *Remove* a **Icebox**, *Update* tras *Reset*.
![triage-deploy](./capturas/triage-depley.png)

![triage-remove](./capturas/triage-remove.png)

![triage-update](./capturas/tablero-parte3.png)

- **Edición:** Detalles y criterios para todas las historias en **Product Backlog**.
![edit-counter](./capturas/edit-counter.png)

- **Label Technical Debt:** Amarillo `#FBCA04`.
![label debet](./capturas/label-technical-debt.png)

- **Labels Asignados:** **enhancement** para la mayoría, **technical debt** para *Deploy*.
![label visible](./capturas/label-visible.png)


[enlace](# Intrucciones)


#### Ejercicio 1: Epic

![epic](./capturas/epic.png)

#### Ejercicio 2: Etiquetas

- **Labels:** *High/Medium/Low Priority*, *In Review*, *Blocked*, *Ready for Testing*.
![](./capturas/new-labels.png)

![](./capturas/tablero-ej2.png)

#### Ejercicio 3: GitHub Actions
[enlace del workflow](https://github.com/Andrew-Inga/CC3S2/blob/main/.github/workflows/kanban-automation.yml)
Este es un cambio para probar la automatización del PR.
-  **Captura:** YAML y prueba de automatización.
![](./capturas/workflow.png)
![](./capturas/automatization-prrof.png)
![](./capturas/automatization-proof2.png)


#### Ejercicio 4: Tiempo

- **Campo:** Esfuerzo estimado (horas).
![](./capturas/campo-esfuerzo.png)
#### Ejercicio 5: Stakeholder Feedback

![](./capturas/exportar-csv.png)
#### Ejercicio 6: Análisis

- **Métricas:** *Cycle time*, cuellos de botella 
![](./capturas/metrica.png)
![](./capturas/metrica-repositorio.png)




