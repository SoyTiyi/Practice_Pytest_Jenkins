
peline {
	agent any
	stages {
		stage("test PythonEnv") {
			steps{
				sh 'pip install pytest'
				sh 'python -m pytest *.py'
			}
		}
	}
}