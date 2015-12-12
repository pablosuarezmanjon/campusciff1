1. CLONAR REPOSITORIO campusciff1 EN LOCAL
Git init
git remote add origin git@github.com:pablosuarezmanjon/campusciff1.git
git fetch origin  - introducir contraseña –
git clone git@github.com:pablosuarezmanjon/campusciff1.git

EJERCICIO 2
Git init
git remote add origin git@github.com:pablosuarezmanjon/campusciff1.git
git fetch origin  - introducir contraseña –
git clone git@github.com:pablosuarezmanjon/campusciff1.git

EJERCICIO 4
git add .
git commit m- “commit inicial”

EJERCICIO 5
git push origin master

EJERCICIO 6
Touch privado.txt
Mkdir privado

EJERCICIO 7
Echo privado > .gitignore
Cat .gitignore
Echo privado.txt > .gitignore
Cat .gitignore

EJERCICIO 8
Touch 1.txt

EJERCICIO 9
Git tag –a V.01 –m “creada tag V.01”

EJERCICIO 10
Git push –tag origin master

EJERCICIO 11
(crear rama)
git branch V.02
(cambiar a rama)
git checkout V.02

EJERCICIO 12
(ver que rama estoy)
git list 
git branch
(crear fichero 2.txt)
touch 2.txt

EJERCICIO 13
Git push origin V.02

EJERCICIO 14
Git checkout master
Git merge V.02


EJERCICIO 15
Vim 1.txt
	Hola [Ctrl + C]
	[:wq]
git add .
git commit –m “actualizado fichero 1.txt”

EJERCICIO 16
Git checkout V.02
Vim 1.txt
	Adios [Ctrl + C]
	[:wq]
git add .
git commit –m “actualizado fichero 1.txt en rama V.02”

EJERCICIO 17
Git checkout master
Git merge V.02
[error en merge]

EJERCICIO 18
Git branch – -merged
Git branch – -no-merged

EJERCICIO 19
Vim 1.txt
	(aparece lo siguiente:
		<<<<<<< HEAD
		hola
=======
		Adios
>>>>>>> V.02
)
(se borra el adiós y se deja el hola)
git add .
git commit –m “resuelto conflicto fichero 1.txt en rama V.02”
git merge V.02

EJERCICIO 20
Git tag –a V.02 –m “tag V.02 creada”
Git branch –d V.02

EJERCICIO 21
Git list

NOMBRE					ENLANCE GITHUB
carlos paz				https://github.com/cpazsantos
sergio torres palomino			https://github.com/sergiotorrespalomino
Adolfo Sanz De Diego			https://github.com/asanzdiego
