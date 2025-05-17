pipeline {
    agent any
    
    stages {
        stage("build and deploy") {
            steps {
                script {
                    // Excute ansbile playbook on the host machine
                    sh "ssh ubuntu@172.31.17.124 'ansible-playbook /home/ubuntu/docker-play.yml'"
                }
            }
        }
    }
}
