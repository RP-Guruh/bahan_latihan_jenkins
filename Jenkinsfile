pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
               git 'https://github.com/RP-Guruh/bahan_latihan_jenkins.git' // ambil dari main
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