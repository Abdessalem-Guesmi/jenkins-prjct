node {
   
 stage('clone') {
 
   git 'https://github.com/Abdessalem-Guesmi/jenkins-prjct'


}

stage('Build') {
    
sh label: '', script: 'javac Main.java'

}

stage('Run') {
 
   
sh label: '', script: 'java Main'


}

}