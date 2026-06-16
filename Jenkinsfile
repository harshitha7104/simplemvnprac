pipeline{
agent any
tools{
mavn 'Maven'
}
stages{
stage('Checkout'){
steps{
checkout scm}}
stage('Build & Test'){
steps{
sh 'mvn clean install'}}
stage('Run Appplication'){
steps{
sh 'java -jar target/simplemvnprac-1.0-SNAPSHOT.jar'}}
}}
