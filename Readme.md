# RapydPay Payment System

# Overview

### This is a Payment Platorm that supports sending and transfering of payments. This application uses [Rapyd](https://www.rapyd.net/) payment APIs to handle payments of the user.

# Features

## 1. Create Wallet Features

- ### [User can fill up their credentials and create wallet which generates a unique wallet ID.](https://github.com/adarshRsinha/RapydPay/assets/93790691/d3b4f81a-3a55-412d-a10e-e6d7d211bae3)


- ### [All the Wallet Details with the unique wallet ID shows up in the wallet Section.](https://github.com/adarshRsinha/RapydPay/assets/93790691/6da81533-42b8-44a5-8c37-3b4370d6a3a8)


- ### [Money Transactions can be done between wallets with Sender's WalletID , Amount (in USD) and Recievers WalletID.](https://github.com/adarshRsinha/RapydPay/assets/93790691/538006ac-f27d-49f8-b1cc-eb504b6edde9)


- ### [The total balance of both the wallets gets updated after successfull Transaction between wallets.](https://github.com/adarshRsinha/RapydPay/assets/93790691/4c897a74-d0d0-4d2c-b5fd-5dae82349c3f)


## 2. Accesing Transactions of a Wallet

- ### [Transactions of a particular wallet can be viewed by clicking on the view transaction button on each wallet card.](https://github.com/adarshRsinha/RapydPay/assets/93790691/44003a7b-a2a8-4fd6-a665-3f078798d310)

- ### [Transaction detail conatins the transacion ID , Amount Debited/credited, Date and wallet id of the wallet to which the amount is paid or recieved.](https://github.com/adarshRsinha/RapydPay/assets/93790691/44003a7b-a2a8-4fd6-a665-3f078798d310)

- ### [If the amount is credited to the wallet it shows in green and if the amount is debited it shows in Red.](https://github.com/adarshRsinha/RapydPay/assets/93790691/44003a7b-a2a8-4fd6-a665-3f078798d310)

### Important Points To remember for creating wallet

- #### You can create only one wallet with single Email-ID or Phone Number.
- #### The number should be in E.164 format (Ex- +918247564782)

## 3. Creating customer with a wallet

- ### [Customer can be created for each wallet with a default Visa card number and details of the customer.](https://github.com/adarshRsinha/RapydPay/assets/93790691/962c4375-bca3-4a76-8c0b-280441ba7313)

- ### [Customer Section will contain the information of all the customers. Each customer will have their own customeID and walletd id associated with it.](https://github.com/adarshRsinha/RapydPay/assets/93790691/4edfa9b9-a263-4010-8618-e8003d2d7264)


### Important Points To remember for creating customer

- #### You can create only one customer using one wallet but you can fund multiple wallets using a single customer.

## 4 . Accessing payments of a Customer

- ### [Customers can pay to any wallets and the amount will be debited from the associated default visa card of the cutomer from which it was initially created.](https://github.com/adarshRsinha/RapydPay/assets/93790691/d153470d-28ed-4740-a7da-af5ab63cf790)

- ### [The amount paid by the customer is added to the wallet and the balance gets updated in the total balance of the ewallet.](https://github.com/adarshRsinha/RapydPay/assets/93790691/f4061550-750d-4ffb-b3b0-70f85862009f)

- ### [The payment details of a particular customer conatins the Pament Id and the wallet id to which the amount was paid.](https://github.com/adarshRsinha/RapydPay/assets/93790691/fea28f4a-263f-431d-a6ff-5d23d780bd1d)


- ### [If the amount is paid from the customers associated wallet it shows up in green and if it is paid to another wallet it shows in green.](https://user-images.githubusercontent.com/67522406/123187677-3b5db500-d4b8-11eb-9dfd-cfe4483c31b5.png)

## 5 . Checkout

- ### [Products can be buyed from the products section using rapyd hosted checkout](https://github.com/adarshRsinha/RapydPay/assets/93790691/7f33ef4b-d61a-403d-bd0a-e3e217b975b0)


# Snapshots

![HomeSection1](https://github.com/adarshRsinha/RapydPay/assets/93790691/acc68325-af65-4730-b8e7-43b029233916)
![HomeSection2](https://github.com/adarshRsinha/RapydPay/assets/93790691/8121181b-eb45-4de0-abc1-30a70ba50d94)
![HomeSection3](https://github.com/adarshRsinha/RapydPay/assets/93790691/6b22061f-ba0d-41a8-a83e-b339325e9dc8)
![HomeSection4](https://github.com/adarshRsinha/RapydPay/assets/93790691/5351b0c5-a6b0-4fc3-a982-2d185fa7eaef)


![ServiceSection1](https://github.com/adarshRsinha/RapydPay/assets/93790691/52e744bf-cf78-445b-aa0b-cbc36992ae03)
![ServiceSection2](https://github.com/adarshRsinha/RapydPay/assets/93790691/ce91a1ff-4ea3-42e9-88dd-1299082947c7)
![ServiceSection3](https://github.com/adarshRsinha/RapydPay/assets/93790691/14c34c54-5da7-47fb-bdee-71b627322e36)


![WalletSection](https://github.com/adarshRsinha/RapydPay/assets/93790691/034440d5-2780-4987-bd45-56e2d3dfe8f4)
![CreateWallet](https://github.com/adarshRsinha/RapydPay/assets/93790691/f9e49143-0d75-4c19-96d7-2472c604c162)
![Transfer](https://github.com/adarshRsinha/RapydPay/assets/93790691/75dd6d96-2b50-4210-9b0d-abd49f765b2d)
![View Transactions](https://github.com/adarshRsinha/RapydPay/assets/93790691/44003a7b-a2a8-4fd6-a665-3f078798d310)


![Customer Section](https://github.com/adarshRsinha/RapydPay/assets/93790691/bd163c03-ff98-499b-a23c-771c0c430bb0)
![Create Customer](https://github.com/adarshRsinha/RapydPay/assets/93790691/862ef5d6-163f-4851-b2f6-fc85daab9efb)
![Payment](https://github.com/adarshRsinha/RapydPay/assets/93790691/80318bb7-e56f-46d7-b3d0-882faa69fea0)
![View Payments](https://github.com/adarshRsinha/RapydPay/assets/93790691/1801fd20-d2e6-4b98-b22c-4010c440d4b4)


![ProductsSec1](https://github.com/adarshRsinha/RapydPay/assets/93790691/df7212ab-32c4-4d97-b279-c68fe68a1804)
![ProductsSec2](https://github.com/adarshRsinha/RapydPay/assets/93790691/d67452cd-eb45-4bdb-8d3b-a65b0df9403f)




