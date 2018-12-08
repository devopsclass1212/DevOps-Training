node {

stage 'checkout'
git ''

stage 'compile'
sh 'mvn compile'

stage 'test'
sh 'mvn test'

stage 'package'
sh 'mvn package'

stage 'artifacts'
archiveArtifacts 'target/*.war'

}
