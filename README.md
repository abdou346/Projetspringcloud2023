# Projetspringcloud2023
- [Spring cloud and angular front-end](#spring-cloud-and-angular-front-end)
- [I. Backend :](#i-backend--)
  * [1. use case](#1-use-case)
  * [2 Inventory service - get all products](#2-inventory-service---get-all-products)
  * [3 Inventory service - get product by ID](#3-inventory-service---get-product-by-id)
  * [4 Customer Service - get All Customers](#4-customer-service---get-all-customers)
  * [5 Customer Service - get Customer by ID](#5-customer-service---get-customer-by-id)
  * [6 Bill Service - get bills](#6-bill-service---get-bills)
  * [7 Bill Service - get bill by id](#7-bill-service---get-bill-by-id)
  * [8 Eureka Service](#8-eureka-service)
- [II. Frontend Angular Client :](#ii-frontend-angular-client--)
  * [1 Login screen](#1-login-screen)
  * [2 Show all products](#2-show-all-products)
  * [3 Edit products](#3-edit-products)
  * [4 Delete products](#4-delete-products)
  * [5 Search for a product](#5-search-for-a-product)
  * [6 New Product](#6-new-product)
  * [7 Show all customer](#7-show-all-customer)
  * [8 Edit Customer](#8-edit-customer)
  * [9 Delete Customer](#9-delete-customer)
  * [10 Search Customer](#10-search-customer)
  * [11 New Customer](#11-new-customer)
  * [12 Show Bills](#12-show-bills)
- [III Secured Angular Client with keycloak](#iii-secured-angular-client-with-keycloak)
  * [1 Setup](#1-setup)
  * [2 Postman](#2-postman)
  * [3 Refresh Token](#3-refresh-token)
  * [4 Client Auth Credentials](#4-client-auth-credentials)



# I. Backend :
## 1. use case

![image](https://user-images.githubusercontent.com/62290643/206123723-0f5d7345-b23d-4ecb-84cb-83346104a73d.png)

## 2 Inventory service - get all products
-http://localhost:8888/PRODUCT-SERVICE/products

![image](https://user-images.githubusercontent.com/101510983/206921870-72327b83-9f52-45a3-a165-a258fec9ebfc.png)



## 3 Inventory service - get product by ID 
-http://localhost:8888/PRODUCT-SERVICE/products/id

![image](https://user-images.githubusercontent.com/101510983/206922542-ff3bc375-78ba-4956-92f4-0cc57ac762b8.png)



## 4 Customer Service - get All Customers
-http://localhost:8888/CUSTOMERS-SERVICE/customers

![image](https://user-images.githubusercontent.com/101510983/206921889-6f2333f5-b2ac-4d27-839b-c0989720c140.png)


## 5 Customer Service - get Customer by ID
-http://localhost:8888/CUSTOMERS-SERVICE/customers/id

![image](https://user-images.githubusercontent.com/101510983/206922673-eb757211-bc70-4d62-a1c2-8248050f3133.png)


## 6 Bill Service - get bills
-http://localhost:8888/BILLING-SERVICE/fullBills

![image](https://user-images.githubusercontent.com/101510983/206922042-3f83dfcb-cb8e-4227-ae03-b5013cbf62f5.png)


## 7 Bill Service - get bill by id
-http://localhost:8888/BILLING-SERVICE/fullBill/id

![image](https://user-images.githubusercontent.com/101510983/206922866-21e9873d-ca97-4434-8cf6-57dfcaadc571.png)


## 8 Eureka Service 
-http://localhost:8761/

![image](https://user-images.githubusercontent.com/101510983/206922145-5a50d39f-704c-4ca9-a1cc-ed65cbd20569.png)

# II. Frontend Angular Client :
## 1 Login screen 

![image](https://user-images.githubusercontent.com/101510983/206923607-8e842b94-d208-4dc6-8cbe-fb68db9037ec.png)

## 2 Show all products 

![image](https://user-images.githubusercontent.com/101510983/206923734-2a653e3a-5b6a-4fdf-a758-193c372adf04.png)

## 3 Edit products 

![image](https://user-images.githubusercontent.com/101510983/206923795-26a19423-e941-4acd-878e-8a0ce1e3df11.png)

## 4 Delete products 

![image](https://user-images.githubusercontent.com/101510983/206923844-354757e5-d805-4aa8-a5f8-1162b36b50fd.png)


## 5 Search for a product

![image](https://user-images.githubusercontent.com/101510983/206923941-e4a48d4a-5be2-47e9-8c73-2013aa954bff.png)


## 6 New Product

![image](https://user-images.githubusercontent.com/101510983/206923990-6c5d704c-f9fc-465f-98fd-173eafcf609a.png)

![image](https://user-images.githubusercontent.com/101510983/206924032-52c194f3-e533-4eff-aebf-4da34e40ad28.png)


## 7 Show all customer

![image](https://user-images.githubusercontent.com/101510983/206924185-35323819-2215-4df8-be55-98bd6b6c452f.png)



## 8 Edit Customer

![image](https://user-images.githubusercontent.com/101510983/206924228-151e1ed2-e1d6-406d-8849-34da1dc34937.png)


## 9 Delete Customer 

![image](https://user-images.githubusercontent.com/101510983/206924348-36b8b439-311d-4c9d-952f-c69ad8ba4d86.png)


## 10 Search Customer 

![image](https://user-images.githubusercontent.com/101510983/206924393-66f44274-38b3-4f4a-9bd8-41562c45735d.png)


## 11 New Customer 

![image](https://user-images.githubusercontent.com/101510983/206924512-b94b94e8-3d18-4329-acfc-0e49cadc7a62.png)

![image](https://user-images.githubusercontent.com/101510983/206924543-8c6cf554-0e5a-424b-894c-40341bc4bcaa.png)


## 12 Show Bills  

![image](https://user-images.githubusercontent.com/101510983/206924663-b135405a-fa87-49b9-b707-12d2eaaa8f52.png)


# III Secured Angular Client with keycloak 

## 1 Setup


## 2 Postman
![image](https://user-images.githubusercontent.com/46407388/206116789-117ba8a2-f337-4fa4-9e01-5d34998c82e5.png)


## 3 Refresh Token
![image](https://user-images.githubusercontent.com/46407388/206116912-121fab06-38fc-4e4b-81ee-cb8013bd2ff1.png)


## 4 Client Auth Credentials
![image](https://user-images.githubusercontent.com/46407388/206117029-7f95a0d9-d7d1-453d-8b0b-8b157098d418.png)



# IV. Kafka :
## 1. Supplier

![image](https://user-images.githubusercontent.com/73041687/219654966-8ed99356-f63b-449b-b782-480121de32f6.png)

![image](https://user-images.githubusercontent.com/73041687/219687628-a8c20cbe-a87a-4375-9636-b932406c01ac.png)


## 2. Consumer

![image](https://user-images.githubusercontent.com/73041687/219677290-25fc52df-3a92-4a65-8e3e-dbf559b2f1de.png)

## 3. Kafka streams 

![image](https://user-images.githubusercontent.com/73041687/219668084-72ac27e1-849e-4fe5-bec0-9eb63685b965.png)



# V. Docker :

## Billing service 
![image](https://user-images.githubusercontent.com/101510983/219879092-282bb834-042e-4f65-9d6b-4c2fb7de907a.png)
## Inventory service
![image](https://user-images.githubusercontent.com/73041687/219698461-5131e970-68b0-4978-a159-a0c628cdb856.png)

![image](https://user-images.githubusercontent.com/73041687/219706814-b5b679ad-30b0-4848-a57c-743ddd0b2798.png)
## Customer service
![image](https://user-images.githubusercontent.com/101510983/219879121-1e19a1ac-918a-4aba-97b0-1f2d4998d074.png)
## gateway service
![image](https://user-images.githubusercontent.com/101510983/219879138-39c2db05-48b4-45a5-bf4a-12454b222c31.png)
## Eureka discovery
![image](https://user-images.githubusercontent.com/101510983/219879150-9c7b7f41-869d-4606-8738-97669a50a05f.png)
## Frontend catalog
![image](https://user-images.githubusercontent.com/101510983/219879165-ceadf4fe-d301-4c64-87a7-e45b51a16b5a.png)






