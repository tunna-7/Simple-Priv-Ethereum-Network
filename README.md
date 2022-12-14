# A Very-Simple-Private-Ethereum-Network
Setting up my own private Ethereum network (for fun)

---
---

## 1) Pre-requisites => Installing Ethereum & Puppeth

    sudo add-apt-repository ppa:ethereum/ethereum
    sudo apt update
    sudo apt install ethereum
    sudo apt install puppeth
    sudo apt install tree

---

## 2) Creating directory structure

![image](https://user-images.githubusercontent.com/66274690/191575644-07d16538-ce0a-4793-8ddd-bc6a7e64c570.png)

---

## 3) Creating Accounts for each Node

![image](https://user-images.githubusercontent.com/66274690/191576631-e09ea057-e2c4-4d58-bc8f-da3bb3fe38bb.png)
#
![image](https://user-images.githubusercontent.com/66274690/191576808-b672fb6f-ea49-4037-bf88-cfb811a5c4a4.png)
#
![image](https://user-images.githubusercontent.com/66274690/191576902-6b939dc6-e0ea-4581-8dee-99d76a87e1f7.png)
#
    Just for simplicity, I've kept all my passwords same and that too is the password for my ubuntu device
#
![image](https://user-images.githubusercontent.com/66274690/191577425-db4c8a82-5b6d-4ba2-a252-f0929a445ba7.png)

---

## 4) Configuring Genesis

![image](https://user-images.githubusercontent.com/66274690/191579715-9e422dbe-e8c7-4986-9e00-c94404ce180d.png)

![image](https://user-images.githubusercontent.com/66274690/191579847-3b357154-58c5-4609-997d-8f112d43ef34.png)

---

## 5) Creating Genesis for each Node

![image](https://user-images.githubusercontent.com/66274690/191597730-d2cc8c16-d463-43e2-8a88-655af2c29fd2.png)

![image](https://user-images.githubusercontent.com/66274690/191597830-65cc1849-3209-4f34-9fc1-cdcdd43493b3.png)

![image](https://user-images.githubusercontent.com/66274690/191598103-ce45a84f-f804-4bb3-bb7a-bca6a070596e.png)

---

### 6) Running a Boot Node

#

URL:
                            enode://f53a17d53f5cf9596295b7e25d142e9c3f93382023e14bf14c27946aafe91257ac03fee3caee6d6ffce237c114cadd55f5cce0e7d0d2f45a5dfb84cdc1dda7ff@127.0.0.1:0?                   discport=8009
 
 Command:
                      
    geth --datadir data/node3 --nodiscover --syncmode ???full??? -verbosity 6 --ipcdisable ??? port 30303 ??? bootnodes ???enode://f53a17d53f5cf9596295b7e25d142e9c3f93382023e14bf14c27946aafe91257ac03fee3caee6d6ffce237c114cadd55f5cce0e7d0d2f45a5dfb84cdc1dda7ff@127.0.0.1:0?discport=8009??? --networkid 9876 --gasprice ???1??? -unlock ???0x219789a1844eF774Da4810e0437A105989b76332??? --password password.txt --mine

#

![image](https://user-images.githubusercontent.com/66274690/191599767-d7803e6c-d475-423e-8c38-c352dae9e4b5.png)

---

### 7)
### 8)
### 9)

