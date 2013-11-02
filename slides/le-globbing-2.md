##  Fichiers et "globbing" - Dynamique

Quand on doit travailler avec un ensemble conséquent de fichiers.

Quand on veut pouvoir conserver la hierarchie de système de fichiers (lors d'une copie par ex.)

````
files: [{
	expand: true, // Enable dynamic expansion
	cwd: 'img/src', // Src matches are relative to this path
	src: ['**/*.{png,jpg,gif}'], // Actual patterns to match
	dest: 'img/' // Destination path prefix
	// ext :''
}]
````
