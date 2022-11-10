
pipeline {
     agent any
     parameters {
     string(name: 'PERSON' , defaultValue: 'Prathamesh', description: 'ENTER YOUR NAME')
     choice(name: 'CHOICE' , choices: ['1','2','3','4'], description: 'PICK')
     password(name: 'PASSWORD' , defaultValue: '0048728c', description: 'ENTER PASSWORD')
    }
stages {
  stage('name') {
  steps {
  echo "Hello ${params.PERSON}"
  }
}
  stage('choice') {
    steps {
    echo "Choice ${params.CHOICE}"
  }
}
   stage('password') {
    steps {
    echo "Password: ${params.PASSWORD}"
   }
  }
 }
}
