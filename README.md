# Online Shopping Site

## Description

Site to allow customers to view various items to purchase. They will be able to add items they want to a cart system and then checkout when they are done. From there they can enter their credit card details to pay for the items and delivery to their address.

Site owners would have the ability to add new products to the site and also update their stock status to let customers know what items are still available and provide times for out of stock items to be replenished.

They will be able to see customer delivery details in order to send off the products to them.

## Main Features

- Product List
- Item Cart
- Payment Service
- Delivery Details

## Typical Users

- Site Owner/Manager
- Customers

## User Persona's

## Jane

Jane is a Mum of 2 kids and would like to use the website to order some gifts for Christmas and upcoming Birthdays. She wants to be able to see how much her total order would be through the cart system and to see how much the overall shipping will cost her and what the delivery times for her order will be like. She would also like to book a certain day for her to be in as she is busy and is only in the house on certain days and times.

## Simon

Simon is the website manager and is charge of making sure that the site stock stays up to date as well as the adding of the new items to the webpage. He also wants to check the delivery addresses of the various orders so that he can ensure that the orders will make it on time as well as be able to contact the customers if there are any delays in the services.

## User Stories

**Jane's User Stories**

**Simon's User Stories**

## Defining SLI's & SLO's

| User Story  | SLO's |  SLI's |
| ------------- | ------------- | ------ |
| Cart Inquiry  | Available 99.5%  | Fraction of 200 vs 500 HTTP Responses from the API endpoint measure per day |
| Cart Inquiry  | 90% of requests complete in under 300 ms  | Time to last byte GET requests measured every 10 seconds aggregated per minute |
| Cart Update  | 90% of requests complete in under 300 ms  | Time to last byte PUSH requests measured every 10 seconds aggregated per minute |
| Cart Update  | Available 99.5%  | Fraction of 200 vs 500 HTTP Responses from the API endpoint measure per day |
| Shipping Inquiry  | Available 99.5%  | Fraction of 200 vs 500 HTTP Responses from the API endpoint measure per day |
| Shipping Inquiry  | 90% of requests complete in under 300 ms  | Time to last byte GET requests measured every 10 seconds aggregated per minute |
| Shipping Update  | Available 99.5%  | Fraction of 200 vs 500 HTTP Responses from the API endpoint measure per day |
| Shipping Update  | 90% of requests complete in under 300 ms  | Time to last byte PUSH requests measured every 10 seconds aggregated per minute |

## Microservices

![Online Store Microservices drawio](https://user-images.githubusercontent.com/55098689/153029030-82cf5299-a957-4ceb-891c-4421db28a98b.png)

## REST API's

| Service Name  | Collections | Methods |
| ------------- | ------------- | ------------ |
| Content Cell  | Content Cell  | Content Cell |
| Content Cell  | Content Cell  | Content Cell |

## Storage Characteristics

| Service  | Structured or Unstructured | SQL or NoSQL | Strong or Eventual Consistency | Amount of Data (MB, GB, TB, PB, ExB) | Read only or Read/Write |
| ------------- | ------------- | ------------ |------------ |------------ |------------ |
| Content Cell  | Content Cell  | Content Cell | Content Cell | Content Cell | Content Cell |
| Content Cell  | Content Cell  | Content Cell | Content Cell | Content Cell | Content Cell |

## Google Storage Products

| Service  | Persistent Disk | Cloud Storage | Cloud SQL | Firestore | Cloud Bigtable | Cloud Spanner  | BigQuery |
| ------------- | ------------- | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| Products Service  | Content Cell  | Content Cell | Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| Payment Service  | Content Cell  | Content Cell | Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| Orders Service  | Content Cell  | Content Cell | Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |
| Authentication Service  | Content Cell  | Content Cell | Content Cell | Content Cell | Content Cell | Content Cell | Content Cell |

## Network Characteristics

| Service  | Internet faacing or Internal Only | HTTP | TCP | UDP | Multiregional |
| ------------- | ------------- | ------------ |------------ |------------ |------------ |
| Content Cell  | Content Cell  | Content Cell | Content Cell | Content Cell | Content Cell |
| Content Cell  | Content Cell  | Content Cell | Content Cell | Content Cell | Content Cell |

## Load Balancers

| Service Name  | HTTP | TCP | UDP |
| ------------- | ------------- | ------------ | ------------ |
| Content Cell  | Content Cell  | Content Cell | Content Cell |
| Content Cell  | Content Cell  | Content Cell | Content Cell |
