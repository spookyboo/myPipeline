@Library ('pipeline_library') _
import nl.rabobank.psit4it.Utils

node {
  stage ("test") {
    println "Executing Jenkinsfile"
	testLib()
	def utils = new Utils()
	utils.aUtilsMethod()
  }
}
