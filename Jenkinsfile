#!groovy

node {
    stage('DEV') {
        echo 'This is the JOB1 inside the dev environment in  the first place'
        functionInstall('DEV')
    }
    stage('TEST') {
        echo 'This is the JOB1 inside the Test environment in the first place'
        functionInstall('TEST')
    }
    stage('QA') {
        echo 'This is the JOB1 inside the QA environment in the first place'
        functionInstall('QA')
    }
    stage('XAT') {
        echo 'This is the JOB1 indide the XAT environment in the first place'
        functionInstall('XAT')
    }
    stage('PROD') {
        echo 'This is the JOB1 inside the Prod enironment in the first place'
        functionInstall('PROD')
    }
}

def functionInstall(env) {
    echo 'This is the fuction call in the jenkinsfile in '+env
}