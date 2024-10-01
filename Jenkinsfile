pipeline {

agent any


stages {

stage('GIT') {

           steps {

               git branch: 'master',

               url: 'https://github.com/oumayma1sh/avec-maven.git'

          }

     }

stage ('Compile Stage') {

    steps {

        sh 'mvn clean compile'

    }

}

}

}