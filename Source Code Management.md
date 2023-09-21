

## 5.1.2. Source Code Management.

El manejo y la organización de las diferentes modificaciones se llevaron a cabo mediante una organización del startup en Github. 

Organization: https://github.com/WebMindsGroup 

Landing Page Repository: https://github.com/WebMindsGroup/WebMinds-LandingPage 

Asimismo, para llevar a cabo un mejor control de cómo crear ramas y realizar cambios en el código fuente, se procedió a utilizar GitFlow.
Ramificaciones principales: Se establecieron dos ramas principales en el control de versiones:

- master: Esta rama contiene las versiones oficiales del proyecto que están listas para ir a producción.
-	develop: Esta rama es donde se integran todas las características nuevas y cambios antes de ser liberados. Es una especie de área de pruebas.
### Ramas auxiliares:
-	Ramas de características (feature): Cada nueva característica o funcionalidad que se está desarrollando se crea en su propia rama llamada "feature". Por ejemplo, si se está trabajando en la función de inicio de sesión, se crearía una rama llamada "feature/login". Una vez que la característica está completa y probada, se une a la rama develop.
-	Rama de lanzamiento (release): Antes de lanzar una nueva versión, se crea una rama de lanzamiento. En esta rama se pueden hacer correcciones finales y preparativos para la versión. Cuando todo esté listo, esta rama se fusiona con master para liberar una nueva versión.
-	Ramas de corrección urgente (hotfix): Si surge un error crítico en la versión actual en producción, se crea una rama de corrección urgente. Esto permite solucionar el error de inmediato sin tener que esperar a la próxima versión planificada.
-	Convenciones de commits: Los mensajes de commit siguen un formato específico llamado "Conventional Commits" en su versión 1.0.0 https://www.conventionalcommits.org/en/v1.0.0/  . Esto facilita la lectura y el seguimiento de los cambios realizados en el código.  Por ello seguimos el siguiente formato:
<type>[optional scope]:<description>
Donde: 

-	type: Describe el tipo de cambio que se realizó. Puede ser algo como una nueva característica (feat), una corrección (fix), una documentación (docs), etc.
-	scope: Indica el alcance o área del proyecto que se vio afectada por este cambio.
-	description: Es un resumen breve de los cambios realizados en el código.
### Convenciones de versionamiento:
Para nombrar las versiones del software, se utiliza el formato de "Semantic Versioning 2.0.0". Esto significa que las versiones se componen de tres números, por ejemplo, X.Y.Z:
-	X (Mayor): Este número representa una versión mayor. Se incrementa cuando se realizan cambios que no son compatibles con las versiones anteriores. Comienza desde 0 para el desarrollo inicial y se cambia a 1 cuando la versión está lista para ser utilizada por el público. Por convención, los números Y y Z se reinician a 0 cada vez que X aumenta.
-	Y (Menor): Este número representa una versión menor. Aquí se incluyen cambios que son compatibles con las versiones anteriores. Los commits realizados desde las ramas de lanzamiento se agregan aquí cada vez que se agregan nuevas características. Por convención, el número Z se reinicia a 0 cada vez que Y aumenta.
-	Z (Parche): Este número representa parches y correcciones de errores menores. Aquí se incluyen los commits realizados desde las ramas de corrección urgente que se fusionan en la rama "master" para corregir errores críticos.

