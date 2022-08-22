reference:  https://github.com/shekeriev/dob-2021-04-exam-re

It is a set of three Docker containers, each with a dedicated role. Together they form a simple web application. 

The general setup looks like:

![general setup](https://github.com/shekeriev/dob-2021-04-exam-re/blob/main/setup.png?raw=true)

If all set up corectly then the result will be something like this:

![sample result](https://github.com/shekeriev/dob-2021-04-exam-re/blob/main/result.png?raw=true)

For successful completion of the challenge, you will have to implement the following steps:
 - (re)build the images;
 - (re)run the containers;
 - ensure the containers are part of the same network.

Please note that:
 - each container should be named after the following rule - ***dob-role***, where ***role*** is either ***producer***, ***storage***, or ***consumer***;
 - database password is expected to be **Exam-2021**;
 - web content is delivered by the *consumer* on port **5000**. It may be redirected to an arbitrary port on the host, for example on port 80;
 - there is no particular order to follow when starting the containers.

*More details could be found in the downloadable **Practice Exam** document available in the **Retake Exam** section of the course.*
