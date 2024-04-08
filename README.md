## Golang Website Health Checker

This golang application checks the health of a website by attempting to establish a TCP connection to a specified domain and port.

### How to setup

- Ensure sure you have Go installed on your system. If not, you can download and install it [here](https://golang.org/dl/).

- Clone the repo using `git clone https://github.com/alahirajeffrey/golang-website-healthchecker.git`

- Navigate to the clone repo using `cd golang-website-healthchecker`

- Run the application by using `go run . -- domain google.com`. This would try to create a tcp connection on port 80 with google

- You can also pass the port flag for example `go run . --domain localhost.com --port 8080`. This would try to connect to your localhost on port 8080.
