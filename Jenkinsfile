pipeline{
    agent{
        label "node"
    }
    stages{
        stage("A"){
            steps{
                echo "========executing A========"
            }

        }

        stage("B"){
            steps{
                echo "========executing B========"
            }

        }

        stage("C"){
            steps{
                echo "========executing C========"
            }

        }

        stage("D"){
            steps{
                echo "========executing D========"
            }

        }

        stage("E"){
            steps{
                echo "========executing E========"
            }

        }

    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}
