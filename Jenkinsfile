node {
    stage('git') {
       git 'https://github.com/developerAdreet/practiceFinalJenkins.git'
    }
    
     stage('mavenbuild') {
       sh 'mvn clean package'
    }
}
