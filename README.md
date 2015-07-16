#This command generates a Gradle web-based Groovy project using the actuator:
curl https://start.spring.io/starter.tgz -d dependencies=web,actuator -d language=groovy -d type=gradle-project | tar -xzvf -t
#btw, specify a baseDir with -d baseDir=xxxxx 
