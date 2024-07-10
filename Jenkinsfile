pipeline {
  agent {
    node {
      label 'thamizh_agent'
    }

  }
  stages {
    stage('Devlopment') {
      parallel {
        stage('Devlopment') {
          steps {
            sh '''#!/bin/bash

date > /tmp/date_output'''
          }
        }

        stage('Production') {
          steps {
            pwd()
            timestamps()
          }
        }

      }
    }

  }
}