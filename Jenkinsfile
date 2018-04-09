
pipeline {
    agent any
    //triggers {
        //cron('39 15 * * *','40 15 * * *')
    //}
    
     triggers {
     upstream(upstreamProjects: "test_multi_branch_cron", threshold: hudson.model.Result.SUCCESS)
	}

    
    // def causes = currentBuild.rawBuild.getCauses()
    // println causes
    stages {
        stage ('cron-1'){
          steps {  
              echo 'stage cron-1'
            #   println causes
             #  println specificCause
             #  println specificCause_2 
             #  println disc
          }
    }
        stage ('cron-2'){
            steps {
                echo 'stage-cron-2'
            }
             
        }
    }
}



