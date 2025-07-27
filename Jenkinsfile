pipeline{
  agent {
    node {
      label "linux && java11"
    }
  }
  stages{
    stage("Build"){
      steps{
        echo("Hello Build1")
        echo("Hello Build2")
      }
    }
    stage("Test"){
      steps{
        echo("Hello Test1")
      }
    }
    stage("Deploy"){
      steps{
        echo("Hello Deploy1")
        echo("Hello Deploy2")
        echo("Hello Deploy3")
      }
    }
  }
}