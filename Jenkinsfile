pipeline {
    agent {
        label "qa"
    }

    stages {
        stage("stage-1") {
            steps {
                echo "this is stage-1"
            }
        }

        stage("stage-2") {
            steps {
                echo "this is stage-2"
                echo "this is dev branch"
            }
        }        
    }
}
