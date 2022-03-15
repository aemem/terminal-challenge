
El ejercicio consiste en ir siguiendo las instrucciones para realizar ciertos comandos en la consola:

1 - Entrar en el directorio thecmdchallenge/. Lo hice usando cd thecmdchallenge/
2 - Imprimir el path al directorio actual. Lo hice con pwd.
3 - Listar todos los archivos en el directorio actual, incluyendo los ocultos. Lo hice con ls -a
4 - Listar recursivamente todos los archivos del proyecto. Lo hice con ls -a -r
5 - Borrar todo lo que hay en la terminal. Lo hice con clear
6 - Ir al último nivel dentro del directorio small-name y mostrar en la consola el contenido de archivo trophy.txt. Fui usando cd hasta llegar al último directorio. Usé tab para completar el nombre del directorio sin tener que escribirlo entero. Para mostrar el contenido del archivo txt usé cat.
7 - Ir al directorio funcode y listar todos los archivos con extensión. Usé cd ../.. hasta volver al directorio inicial. Después usé cd para entrar en funcode y ls -l para listar los archivos con la extensión.
8 - Crear un directorio dentro de funcode/the-most-funny/ llamado “not-that-funny“. Usé cd para entrar en the-most-funny y touch para crear el archivo dentro.
9 - Copiar el archivo the-mostboring-text.txt y llamar a la copia lol.txt. Entré en boringfolder y copié el archivo usando cp the-mostboring-text.txt lol.txt
10 - Mover funcode/kids.jpg a funcode/images/hello/. Lo hice usando mv y los paths absolutos
11 - Borrar el directorio small-name. Lo hice usando rm -r para borrar recursivamente.
12 - Imprimir en la terminal el contenido de the-ultimate-joke.txt. Lo hice con cat
13 - Borrar todo el contenido de boringfolder. Utilicé rm y el path absoluto del directorio.
14 - Abrir el archivo kamehameha/dragon-ball-jokes.md con vim. Lo hice con vim kamehameha/dragon-ball-jokes.md
15 - Borrar el primer chiste del archivo dragon-ball-jokes.md, guardar y cerrar el editor. Primero le di a i para ponerme en modo insert, borré la línea y usé :wq para guardar y salir.



![Command Line Preview](https://raw.githubusercontent.com/breatheco-de/exercise-terminal-challenge/master/preview.png)

This command line challenge is designed to help you become familiar with the bash/command line. The challenge goes over the most used commands every developer needs to know in order to succeed in real life.

> :exclamation: We strongly recommend reading [The Command Line lesson](https://content.breatheco.de/en/lesson/the-command-line-the-terminal) on the BreatheCode platform.

💻The challenge is built for computers using the Linux bash. Use [Gitpod](https://gitpod.io) if you need a terminal in the cloud. 

## 🌱  How to start this project

### 👩‍🎓Students and Teachers must follow this step:

This project comes with the necessary files to start working, but you have two options to start:

a) Open this link in your browser to clone it with gitpod (recommended): https://gitpod.io#https://github.com/breatheco-de/exercise-terminal-challenge.git

b) You can clone this repository on your local computer:

```sh
$ git https://github.com/breatheco-de/excercise-terminal-challenge.git
```

💡 Important: Remember to create a new repository, update the remote (`git remote set-url origin <your new url>`), and upload the code to your new repository using `add`, `commit` and `push`.

## Only teachers must follow this step:

#### 1) Install the packages.

```sh
$ npm install
```

#### 2) Run the presentation.

```sh
$ npm run start
```

# Start Playing!

Follow the presentation for better experience.
