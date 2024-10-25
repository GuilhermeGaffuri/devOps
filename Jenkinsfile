pipeline {
    agent any

    stages {
        stage('Clonar Repositório') {
            steps {
                // Clonar o repositório Git
                git url: 'https://github.com/g4l4ctusInt/devOpsaula03'
            }
        }

        stage('Executar o Código') {
            steps {
                sh 'python3 main.py'
            }
        }
    }
}
