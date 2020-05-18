node {
    stage('Example') {
        if (env.BRANCH_NAME == 'master') {
            echo 'I only execute on the master branch'
        }
        if (env.BRANCH_NAME == 'atleti') {
          echo 'Forza atleti'
        }
        else  {
            echo 'I execute elsewhere'
        }
    }
}
