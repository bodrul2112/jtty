
Jtty
====

A lovely chap (https://github.com/stephenh/jtty) made this: 

	A really simple jar bootstrap around Jetty.

However since I like gradle. I wanted a gradle build with the wrapper in source, so I made this. Plus, no IDE cruft :) And of course, most importantly There's a prebuilt jar in here as well.

So now we just run:

    java -jar jtty.jar 8080 /context1
	
or:

	java -jar jtty.jar 8080 .

All the other lovely stuff still exists in stephens src, if you want to open the project in eclipse simply run:

	gradlew eclipse
	
if you want to build that jar again run:

	gradlew jar
	
enjoy.