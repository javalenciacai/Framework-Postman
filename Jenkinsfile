pipeline {
  agent any
  stages {
    stage('test1') {
      steps {
        bat 'C:\\Users\\VALE262268\\AppData\\Roaming\\npm\\newman run Postman/PayrollLiquidator_V2.postman_collection.json -d Postman/NominacsvErrores1.csv --insecure -r htmlextra --reporter-htmlextra-export ./results/index.html'
      }
    }

  }
}