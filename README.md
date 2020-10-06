# my-libs

```
@Library('javahome-libs') _

pipeline{
    agent any
    stages{
        stage('Demo'){
            steps{
                welcome("Hari Kammana")
                script{
                    calc.add(10,20)
                    calc.mul(10,20)
                }
            }
        }
    }
}
```
