pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
               git branch: 'main', url: 'https://github.com/RP-Guruh/bahan_latihan_jenkins.git'
            }
        }

        stage('Build') {
            steps {
                echo "belum ada build apa apa"
            }
        }

        stage('Deploy') {
            steps {
                sh 'cp -r * /var/www/html/bahan_latihan_jenkins'
            }
        }
    }
}