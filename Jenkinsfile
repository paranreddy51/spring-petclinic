#!/usr/bin/env groovy
node {
    stage('HelloWorld') {
        echo 'Hello World'
    }
    stage('Clone') {
        git url: 'https://github.com/paranreddy51/spring-petclinic.git'
    }
    stage('Build') {
        sh './mvnw clean package'
    }
}
