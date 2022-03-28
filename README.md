# README.md

This is an implementation of the Tabbre Proof of Majority Protocol (POMP), a decentralised consensus protocol that scales linearly, the more network and processing capacity that is added, the more transaction throughput the system can handle. 

This implementation is built using node.js, mongodb, mongoose and express.js. The interfaces between the components are all implemented as RESTful APIs.







![](https://raw.githubusercontent.com/tabbre-blockchain/tabbre-pomp/main/documents/xferReqPart01%20Debit%20Sender%20Account%20i.jpg)





![](https://raw.githubusercontent.com/tabbre-blockchain/tabbre-pomp/main/documents/xferReqPart02%20%20%20debit%20sender%20account%20ii%20.jpg)



![](https://github.com/tabbre-blockchain/tabbre-pomp/raw/main/documents/xferReqPart03-accept-xferInstruction.jpg)





![](https://raw.githubusercontent.com/tabbre-blockchain/tabbre-pomp/main/documents/xferReqPart04-accept-xferInstruction.jpg)







# **Proof of Majority Protocol - POMP**

# **Witness Registry**

## **Genesis Event**

Witness Registry launched with a genesis file containing initial witness accounts and ip addresses

## **API**

### Register Witness

Witness account id

Commencement date:time

Termination date:time

Witness signatures

### List Witnesses

Date range - blank is current date

### Renew Witness Lease

Witness account id

Commencement date:time

Termination date:time

Witness signatures



### Cancel Witness

Witness account id

Termination date:time

Witness signatures



# **Witness Service**

## **Genesis Event**

Witness launched with a genesis file containing initial witness accounts and ip addresses initial accounts and balances

## **API**



### Register Account



# **Wallet Service**



The Wallet Service  has two components: the Wallet Key manager and the Wallet Transaction Manager.

# Wallet **Key manager**

UserAgent to KeyManager

# **Wallet Transaction Manager**
