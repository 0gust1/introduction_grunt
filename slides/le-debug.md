## Le debug

### grunt.log.writeln()

Pas évident pour les plugins. Plus simple pour les custom tasks.

### grunt --debug --stack --verbose "yourtask" 

Assez limité, mais ça peut aider.

### node-inspector

``
node --debug-brk $(which grunt) votre_tache_grunt
``

ou sinon :

``npm install grunt-node-inspector --save-dev``

https://npmjs.org/package/grunt-node-inspector

``npm install grunt-debug``

https://github.com/burnnat/grunt-debug
