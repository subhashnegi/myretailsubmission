# myretailsubmission

How to Run myRetail RestfulService

	Prerequisite
•	Intellij(or any IDE)
•	Java 8
•	Mongodb

1.	Unzip myRetailSubmission.zip
2.	You will see 4 Separate maven project
a.	myretail-price-catalogue
b.	myretail-product-catalogue
c.	myretail-product-nomenclature
d.	discovery-server
3.	Since this Project requires mongodb , please start the mongo DB on default port 27017
4.	Start all four Spring Boot Application, Start the discovery server first and then there is no order for the rest , please refresh
http://localhost:8761/

Running the above URL will show you the similar snapshot , with all the listed client.

 

5.	Last step is to execute on Browser
http://localhost:8082/myretail/v1.0/product/13860428

O/p 
{ 
"id":13860428,
"name":"The Big Lebowski (Blu-ray)",
"currentPrice":{ 
"value":13.49,
"currencyCode":"USD"
}
}


					
