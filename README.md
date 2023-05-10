# projectpipeline
pipeline {
 agent any
  stages {
   stage(checkout) {
    steps {
    pipeline syntax 
      
      
      
      pipeline {
 agent any
  stages {
   stage(checkout) {
    steps { 
    shell script select and  mvn package
    generate pipeline script click copy and paste apply and save
    
    
    
    pipeline {
 agent any
  stages {
   stage(sonarqube) {
    steps { 
    manually click and project display name: maven and project key : maven
    and main branch name: main and setup click
    globaly click and generate and continue and maven click and copy 
    mvn clean verify paste here
    apply and save
    
    
     pipeline {
 agent any
  stages {
   stage(nexus) {
    steps { 
    nexus artifact uploader select
    nexus version: nexus 3
    protol :http
    nexus url : paste here
    credentials and group id : go to pom.xml(com.example.maven-project)
    version:1.0 SNAPSHORT
    repository: maven-snapshots
    componets click and maven snapshots click
    Artifactid :maven-project
    type : war
    oncce run job path copy path :paste here
    generate pipeline copy and paste
    apply and save 
    build fail credentials delete
    
    
     pipeline {
 agent any
  stages {
   stage('docker $ push') {
    steps { 
    script 
    install plugins 
    cloud docker pipeline
    docker pipeline
    docker set up pipeline
    with docker registory sets up docker regiostry endpoint select
    manage jenkins and manage credentials click system click and global credentials clickadd domain
    dockerhubcredentials evali  user name :devopsvmr
    password:madhu@1234
    id: docker_cred
    description:docker_cred
    create click
    generate pipeline script click
    copy (withdocker registory (credentials docker_cred)
        sh 'docker build -t  devopsvmr/vcubetaxi:tag10am .'
        sh 'docker push devopsvmr/vcubetaxi:10am .'
        }
}
}
go to github and taxibooking click and docker file click

    
    
    
    
    
    
    
    
