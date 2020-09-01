@Library('My-Shared-Library@master') _

pipeline {
	agent any
	stages{
	    stage('test vars'){
	    	steps{
	    		script{
	    			test.test()
	    		}
	    	}
	    }
	    stage('test src'){
	    	steps{
	    	   	script{
	    			def nofity = new com.ecic.automation.base.Nofity()
	    			nofity.printClassName('test class')
	    		}
	    	}
	    }
	 }
}
