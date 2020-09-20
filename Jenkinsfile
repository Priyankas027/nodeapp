pipeline {
    agent any
stages{
 stage('Deploy node app') {
steps{
    echo $pwd
sh 'pm2 start app.js'
}
}}
}
