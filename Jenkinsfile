import java.util.Date
import groovy.json.*


def isMaster = env.BRANCH_NAME == 'master'
def isStaging = env.BRANCH_NAME == 'staging'

if(isMaster){
    node{
        stage('initializing') {
            sh '''echo  stage1'''
        }
        stage('stage2') {
            sh '''echo stage2'''
        }
        stage('stage3') {
            sh '''echo stage3'''
        }
    }
}