pipeline{
    agent any
    stages{
        stage('Git pull & Verify'){
            steps{
                git branch: 'main', credentialsId: 'git', url: 'https://github.com/Sayan6726/demojenking.git'
                sh 'ls -alF'
            }
        }

        stage('Copy Project'){
            steps{
                sh 'cp -rf . /home/ubuntu/samjenks'
            }
        }

    }
}
