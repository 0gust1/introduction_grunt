##  Gestion de la configuration (1)
### Principe :
````
├── Gruntfile.js
├── grunt-tasks
│   ├── options
│   │   ├── imagemin.js
│   │   ├── notify.js
│   │   └── watch.js
│   ├── set_config.js
│   └── set_global.js
````
### Gruntfile :
````
module.exports = function(grunt) {

  require('load-grunt-config')(grunt, {
        configPath: 'grunt-tasks/options'
    });

  grunt.loadTasks('grunt-tasks');
  grunt.registerTask('default', ['watch']);
};
````
