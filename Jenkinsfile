pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                bat 'git remote add origin2 https://github.com/shekhar1100/JaniTest1.git'
              //  bat 'git remote set-url origin https//github.com/shekhar1100/DataTestEmpty.git'
             //   bat 'git remote set-url origin https://github.com/shekhar1100/DataTestEmpty.git'
             //   bat 'git remote rm origin'
              //  bat 'git remote add origin https://github.com/shekhar1100/DataTestEmpty.git'
              //  bat 'git push origin master'
             //   bat 'git branch -M master'
               // bat 'git push -u origin master'
               // bat 'git push DataTestEmpty master'
                bat 'git config --global user.email "you@example.com"'
                bat 'git config --global user.name "Your Name'
               // bat 'git checkout master '     
               // bat 'git commit -m "Initial commit" '
               // bat 'git push JaniTest master:master' 
                bat 'git push origin2 HEAD:refs/heads/master'
            }
        }
    }
}
