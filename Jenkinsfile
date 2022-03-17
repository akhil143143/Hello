pipeline (){
    agent any
    stages{
        stage('serverdetails'){
            steps{
                sh'''
                  hostname
                  hostname -I
                  mpstat
                  free -h
                  df -h
                '''
            }
        }
    }
}
