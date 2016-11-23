stage('Dev') {
    node {
		echo "stage DEV"
		bat 'C:\Users\fengguangke\AppData\Roaming\npm\newman.cmd -u https://www.getpostman.com/collections/013349691e623f42448c -e E:\\postman_api\\TestEnvironment.postman_environment.json -d  E:\\postman_api\\postman_data.json -n 2'
    }
}

stage('QA') {
	node{
		echo "stage QA"
	}
}