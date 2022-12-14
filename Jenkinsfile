pipeline{
  agent any
  stages{
    stage("SCM"){
      steps{
       echo "Git"
      }
     }
     stage("MVN"){
      steps{
       echo "mvn clean package"
      }
     }
     stage("NXS"){
      steps{
       echo "nexus repo"
      }
    }

}
}
