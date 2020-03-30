def JDK_HOME
def PROPS
def GIT_URL
def CI_TOOLS_BRANCH
def IS_BRANCH
def GIT_CREDENTIALS_ID
def JENKINS_WS
def IS_REPO_HOME
def SAG_HOME
def ABE_HOME
def BUILD_VERSION
def DEPLOYER_HOME
def DEPLOYER_HOST
def DEPLOYER_PORT
def DEPLOYER_USER
def DEPLOYER_PWD
def PROJECT_NAME_IS
def DEP_SET_IS
def DEP_MAP_IS
def DEP_CAN_IS
def REPO_NAME="IS_REPO"
def TARGET_ALIAS_IS
def TARGET_HOST_IS
def TARGET_PORT_IS
def TARGET_USER_IS
def TARGET_PWD_IS
def TARGET_VERSION_IS

def ASSETS_PREFIX_IS
def DIRECTORY_TEST_REPORTS

pipeline {
	environment {
		SAG_HOME="C:/SoftwareAG/v10_3"
	}
	
	agent any
	
	stages {
	
		stage ('Checkout SourceCode') {				
			steps {
					print " ----- SourceCode Checkout -----"
			}
		}
		
		
		stage ('Create Build') {				
			steps {
					print " ----- Create Build ----- "}
		}


		stage ('Deploy Build') {				
			steps {
					print " ----- Create Project ----- "

				
					print " ----- Deploy Build ----- "

				
			}
		}		
		
	
		stage ('Run Unit Tests') {
			steps {

			}
		}		

		}
	}



