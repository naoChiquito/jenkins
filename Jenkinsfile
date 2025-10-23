pipeline {
   agent any
   stages {
     stage('Clonar codigo') {
       steps {
          git 'https://github.com/usuario/mi-repo.git'
       }
     }
     stage('Compilar') {
       steps {
         sh 'echo "Compilando el proyecto..."'
       }
     }
     stage('Pruebas') {
       steps {
         sh 'echo "Ejecutando pruebas..."'
       }
     }
  }
}

