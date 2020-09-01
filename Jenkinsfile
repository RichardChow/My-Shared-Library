@Library('My-Shared-Library@master') _

pipeline {
	agent any
	stages{
	    stage('test vars'){
	    	script{
	    		test.test()
	    	}
	    }
	    stage('test src'){
	    	script{
	    		def nofity = new com.ecic.automation.base.Nofity()
	    		nofity.printClassName('test class')
	    	}
	    }
	 }
}
