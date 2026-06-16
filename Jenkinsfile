pipeline{
agent any
tools{
mavn 'Maven'
}
stages{
stage{
steps('Checkout'){
checkout scm}}
stage{
steps('Build & Test'){
sh 'mvn clean install'}}
stage{
steps('Run Appplication'){
sh 'java -jar target/simplemvnprac-1.0-SNAPSHOT.jar'}}
}}
