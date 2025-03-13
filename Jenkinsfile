pipeline{
    agent any
    parameters{
        booleanParam(name: "enable service", description: "Enable Service", defaultValue: false)
    }
    stages{
        stage("Parameter Demo"){
            steps{
                echo "booleanParam is set to ${params.myBool}"
            }
        }
    }
}