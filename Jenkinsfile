pipeline {
    agent any
    environment {
        PYTHON_HOME = '/usr/bin/python3'
    }
    stages {
        stage('Build') {
            steps {
                script {
                    // Choisissez la commande en fonction de votre script
                    sh 'python3 -m pip install pandas' // Installer les dépendances
                    sh 'python3 data_analysis.py' // Exécuter le script Python
                }
            }
        }
    }
}
