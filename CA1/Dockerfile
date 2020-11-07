#FROM allows the user to select the type of image they would like to download, the colon allows the user to specify the version if necessary

FROM python:3.9

#Sets the work directory within the image
WORKDIR /EPA-CA1

#Copies the html file into the work directory
COPY dockertutorial.html /EPA-CA1/

#Adds a command for the python3 server to point to port 8080
CMD python3 -m http.server 8080
