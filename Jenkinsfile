pipeline {
   agent any
   stages {
     stage('Clonar codigo') {
       steps {
          git branch: 'main', url: "https://github.com/naoChiquito/jenkins.git"
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
