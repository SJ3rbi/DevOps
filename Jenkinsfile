node{
    stage('SCM Checkout'){
        git 'https://github.com/Mohamed-Rouahi/DevopsProject.git'  
    }
    stage('Email Notification'){
        mail bcc: '', body: 'test sending email', cc: '', from: '', replyTo: '', subject: 'Jenkins', to: 'mohamed.rouahi@esprit.tn'        
    }

}
