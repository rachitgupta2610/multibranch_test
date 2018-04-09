
pipeline {
    agent any
    //triggers {
        //cron('39 15 * * *','40 15 * * *')
    //}
    
    #nvironment {
       #def causes = currentBuild.rawBuild.getCauses()
       #def specificCause = currentBuild.rawBuild.getCause(hudson.triggers.TimerTrigger$TimerTriggerCause)
       #def specificCause_2 = currentBuild.rawBuild.getCause(hudson.model.Cause$UserIdCause)
       #def disc = getShortDescription()

    #}
    
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



