##  Un moteur de tâches (2)

Ecrire ses propres tâches.

### tâches d'alias vers une ou plusieurs tâches. 
```` 
grunt.registerTask('myTask', 'ma super tâche', ['jshint:prod','tests:prod']) 
````

### tâches "custom"
- tâches aynchrones.
- tâches à plusieurs targets (multi-tasks)
- tâches lançant d'autres tâches (avec conditions d'échecs etc...)

### Référence : 
http://gruntjs.com/creating-tasks