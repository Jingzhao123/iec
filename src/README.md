# Bookinfo example on Istio
This example deploys a sample application composed of four separate microservices
used to demonstrate various Istio features. The application displays information
about a book, similar to a single catalog entry of an online book store. Displayed
on the page is a description of the book, book details (ISBN, number of pages, and
so on), and a few book reviews.
For more detail informations, please refer to corresponding website:
[Bookinfo](https://istio.io/docs/examples/bookinfo/).
In this document, it will show you how to deploy it.

## Deploy Bookinfo example
Firstly, get to know the k8s master IP address.
Secondly, run the install.sh scripts with master IP address.

  ./install/install.sh $master_ip
