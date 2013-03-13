hadoop wordcount example
========


#package
	mvn package

#local test
	java -jar target/wordcount-1.0.jar input/ output/

#remote test
	hadoop jar wordcount-1.0.jar remote/input/ remote/output/ 

