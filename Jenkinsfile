
pipeline {
     agent any
     parameters {
     string(name: 'PERSON' , defaultValue: 'Prathamesh', description: 'enter your name')
     choice(name: 'CHOICE' , choices: ['1','2','3','4'], description: 'pick')
     password(name: 'PASSWORD' , defaultValue: '0048728c', description: 'enter pass')
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
