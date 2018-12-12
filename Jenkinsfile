pipeline {
    agent any
    stages {
        stage('build') {

            steps {
                echo "Master of puppets I'm pulling your strings.."
                sh 'javac -d . src/*.java'
                sh 'echo Main-Class: Rectangulator > MANIFEST.MF'
                sh 'jar -cvmf MANIFEST.MF rectangle.jar *.class'

            }
        }
    }

}
