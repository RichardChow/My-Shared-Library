@Library('My-Shared-Library') _

pipeline {
	agent any
	stages{
	    stage('test vars'){
	        test.test()
	    }
	    stage('test src'){
	    	def nofity = new com.ecic.automation.base.Nofity()
	    	nofity.printClassName('test class')
	    }
	 }
}
