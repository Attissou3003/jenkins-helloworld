node {
    stage('Clone') {
        git credentialsId: 'ac675c76-5940-4a3c-96d9-50f5e98dac72', url: 'https://github.com/Attissou3003/jenkins-helloworld.git'
    }
    stage('Build') {
        sh '''javac Main.java'''
    }
    stage('Run') {
        sh '''java Main'''
    }
}
