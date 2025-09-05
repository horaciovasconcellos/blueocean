pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Compilando o projeto... Horacio'
      }
    }

    stage('Test') {
      steps {
        echo 'Executando os testes...Horacio'
      }
    }

    stage('Deploy') {
      agent any
      steps {
        echo 'Publicando...Horacio'
      }
    }

  }
}
