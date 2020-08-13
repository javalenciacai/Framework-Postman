pipeline {
  agent any
  stages {
    stage('test1') {
      steps {
        bat 'cd Postman  C:\\Users\\VALE262268\\AppData\\Roaming\\npm\\newman run PayrollLiquidator_V2.postman_collection.json -d NominacsvErrores1.csv --insecure -r htmlextra --reporter-htmlextra-export ./results/index.html'
      }
    }

  }
}