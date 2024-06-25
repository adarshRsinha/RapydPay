# RapydPay Payment System

# Overview

### This is a Payment Platorm that supports sending and transfering of payments. This application uses [Rapyd](https://www.rapyd.net/) payment APIs to handle payments of the user.

# Features

## 1. Create Wallet Features

- ### [User can fill up their credentials and create wallet which generates a unique wallet ID.](https://github.com/adarshRsinha/RapydPay/assets/93790691/d3b4f81a-3a55-412d-a10e-e6d7d211bae3)


- ### [All the Wallet Details with the unique wallet ID shows up in the wallet Section.](https://user-images.githubusercontent.com/67522406/123187556-07828f80-d4b8-11eb-88e4-0dc331efa43d.png)

- ### [Money Transactions can be done between wallets with Sender's WalletID , Amount (in USD) and Recievers WalletID.](https://user-images.githubusercontent.com/67522406/123187599-19fcc900-d4b8-11eb-92fb-61e066a6fe71.png)

- ### [The total balance of both the wallets gets updated after successfull Transaction between wallets.](https://user-images.githubusercontent.com/67522406/123187556-07828f80-d4b8-11eb-88e4-0dc331efa43d.png)

## 2. Accesing Transactions of a Wallet

- ### [Transactions of a particular wallet can be viewed by clicking on the view transaction button on each wallet card.](https://user-images.githubusercontent.com/67522406/123187610-1ec17d00-d4b8-11eb-8025-baf86c48bbcc.png)
- ### [Transaction detail conatins the transacion ID , Amount Debited/credited, Date and wallet id of the wallet to which the amount is paid or recieved.](https://user-images.githubusercontent.com/67522406/123187610-1ec17d00-d4b8-11eb-8025-baf86c48bbcc.png)

- ### [If the amount is credited to the wallet it shows in green and if the amount is debited it shows in Red.](https://user-images.githubusercontent.com/67522406/123187610-1ec17d00-d4b8-11eb-8025-baf86c48bbcc.png)

### Important Points To remember for creating wallet

- #### You can create only one wallet with single Email-ID or Phone Number.
- #### The number should be in E.164 format (Ex- +918247564782)

## 3. Creating customer with a wallet

- ### [Customer can be created for each wallet with a default Visa card number and details of the customer.](https://user-images.githubusercontent.com/67522406/123187664-3436a700-d4b8-11eb-83cb-3d575d62820e.png)

- ### [Customer Section will contain the information of all the customers. Each customer will have their own customeID and walletd id associated with it.](https://user-images.githubusercontent.com/67522406/123187650-30a32000-d4b8-11eb-93ce-9e3c937dac53.png)

### Important Points To remember for creating customer

- #### You can create only one customer using one wallet but you can fund multiple wallets using a single customer.

## 4 . Accessing payments of a Customer

- ### [Customers can pay to any wallets and the amount will be debited from the associated default visa card of the cutomer from which it was initially created. ](https://user-images.githubusercontent.com/67522406/123187670-3862c480-d4b8-11eb-80fe-1e4d5f0ac115.png)

- ### [The amount paid by the customer is added to the wallet and the balance gets updated in the total balance of the ewallet.](https://user-images.githubusercontent.com/67522406/123187556-07828f80-d4b8-11eb-88e4-0dc331efa43d.png)

- ### [The payment details of a particular customer conatins the Pament Id and the wallet id to which the amount was paid.](https://user-images.githubusercontent.com/67522406/123187677-3b5db500-d4b8-11eb-9dfd-cfe4483c31b5.png)

- ### [If the amount is paid from the customers associated wallet it shows up in green and if it is paid to another wallet it shows in green.](https://user-images.githubusercontent.com/67522406/123187677-3b5db500-d4b8-11eb-9dfd-cfe4483c31b5.png)

## 5 . Checkout

- ### [Products can be buyed from the products section using rapyd hosted checkout ](https://user-images.githubusercontent.com/67522406/123187785-6ba55380-d4b8-11eb-809c-41c8ebb9de12.png)

# Snapshots

![HomeSection1](https://user-images.githubusercontent.com/67522406/123187507-ec178480-d4b7-11eb-8db1-528deced35df.png)
![HomeSection2](https://user-images.githubusercontent.com/67522406/123187511-ef127500-d4b7-11eb-951c-c880c55e3286.png)
![HomeSection3](https://user-images.githubusercontent.com/67522406/123187517-f33e9280-d4b7-11eb-9b40-3c134c3fb1ed.png)
![HomeSection4](https://user-images.githubusercontent.com/67522406/123187525-f6398300-d4b7-11eb-97b7-97b85914d275.png)


![ServiceSection1](https://user-images.githubusercontent.com/67522406/123187724-4e708500-d4b8-11eb-829f-077d5394ddea.png)
![ServiceSection2](https://user-images.githubusercontent.com/67522406/123187737-53353900-d4b8-11eb-86ad-76a842ae9069.png)
![ServiceSection3](https://user-images.githubusercontent.com/67522406/123187742-56302980-d4b8-11eb-8ca6-5071d0249768.png)


![WalletSection](https://user-images.githubusercontent.com/67522406/123187556-07828f80-d4b8-11eb-88e4-0dc331efa43d.png)
![CreateWallet](https://user-images.githubusercontent.com/67522406/123187564-0baead00-d4b8-11eb-94c8-9d4cce6f294b.png)
![Transfer](https://user-images.githubusercontent.com/67522406/123187599-19fcc900-d4b8-11eb-92fb-61e066a6fe71.png)
![View Transactions](https://user-images.githubusercontent.com/67522406/123187610-1ec17d00-d4b8-11eb-8025-baf86c48bbcc.png)

![Customer Section](https://user-images.githubusercontent.com/67522406/123187650-30a32000-d4b8-11eb-93ce-9e3c937dac53.png)
![Create Customer](https://user-images.githubusercontent.com/67522406/123187664-3436a700-d4b8-11eb-83cb-3d575d62820e.png)
![Payment](https://user-images.githubusercontent.com/67522406/123187670-3862c480-d4b8-11eb-80fe-1e4d5f0ac115.png)
![View Payments](https://user-images.githubusercontent.com/67522406/123187677-3b5db500-d4b8-11eb-9dfd-cfe4483c31b5.png)


![ProductsSec1](https://user-images.githubusercontent.com/67522406/123187767-6516dc00-d4b8-11eb-8fc7-a8d7d6efedb2.png)
![ProductsSec2](https://user-images.githubusercontent.com/67522406/123187785-6ba55380-d4b8-11eb-809c-41c8ebb9de12.png)



