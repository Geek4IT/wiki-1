========
Glossary
========

.. contents:: Table of contents
    :depth: 1
    :local:

Items
-----

    Address
        An address is a public key. A public-private key pair consisting can be generated through an algorithm. The public key is accessible to network while the private key isn't. The public key is usually used for session key encryption, signature verification and encrypting data which could be unencrypted with a corresponding private key.
    Allowance
        Block production rewards are sent to a sub-account. SRs can claim their reward on Tronscan.
    API
        API is mainly used for the development of client terminals. With API support, token issuance platform can be designed by developers themselves.
    Application Layer
        Developers can utilize interfaces for the realization of diverse dAPPs and customized wallets.
    Asset
        In TRON's documents, asset is the same as token.
    Asset Issue
        Issuing a token on the Tron Protocol can be done by anyone who has at least 1024 TRX in their account.
    Balance	TRX
        A TRX account shows the balance of TRX and of other tokens and their USD equivalent.
    Bandwidth
        To keep the network operating smoothly, TRON network only allows every account to initiate a limited number of transactions. To engage in transactions more frequently requires bandwidth points. Like TRON Power (TP), bandwidth points can be obtained through freezing TRX. Transactions are transmitted and stored in the network in byte arrays. Bandwidth points consumed in a transaction equals the size of its byte array. The ratio of bandwidth points in an account to the bandwidth capacity of TRON’s network equals the ratio of frozen balance in an account to frozen balance on the entire network.
    Block
        Blocks contains the digital records of your transactions. A complete block consists of the magic number, block size, blockheader, transaction counter and transactions.
    Blockheader
        A blockheader is part of a block. It contains the hash of the previous block, the Merkle root, the timestamp, the difficulty and the nonce.
    CDN
        CDN is short for Content Delivery Network. It aims to achieve faster and more stable transmission through avoiding as many links which could affect its speed and stability of transmission as possible.
    Cold Wallet
        Cold wallet, also known as offline wallet, keeps the privated key completely disconnected from any network. Cold wallets are usually installed on "cold" devices (computers or mobile phones stayin offline) to ensure the security of TRX private key. Private keys are kept away from the network by utilizing QR codes for payment.
    Consensus
        The consensus mechanism verifies and confirms transactions very swiftly through voting by special nodes. If several uninterested nodes can reach consensus on a transaction, we can deduce that the entire network can also reach consensus.
    Core Layer
        Smart contract module, account management module and consensus module are three modules of the core layer. It’s TRON’s vision to base its functions on a stacked virtual machine and optimized instruction set.
    DApp
        Decentralized application, Service that operates without a central trusted party. An application that enables direct interaction/agreements/communication between end users and/or resources without a middleman.
    Freeze
        Freezing a certain amount of TRX earns users Tron Power to vote and bandwidth points for transactions and smart contract running. The number of bandwidth points equals the amount of TRX frozen*frozen duration (days). Frozen TRX cannot be traded or used for transfer.
    Frozen account
        Unfrozen TRX re-enters circulation and can be traded.
    Google Protobuf
        Independent from language platforms, ProtoBuf is a flexible and efficient means of data structuralization which can be used for communication protocols and data storage. It is faster, simpler and more compact. You can customize your own data structure of ProtoBuf and use a ProtoBuf compiler to generate source code in mainstream programming languages like C++, Java and Python to easily serialize or deserialize.
    GRPC
        GRPC is a language-neutral, platform-neutral open-source RPC system, with which apps in the client end can directly invoke another app on a different device like local one. It facilitates the creation of Dapps and decentralized services. Like many other RPC systems, gPRC is based on the following concepts: define a service and designate a way inlcluding the parameters and return type for it to be invoked remotely; deploy such an interface on server and run a gRPC server to process client end invoke; install a stub on the client end to allow remote invoke.
    Hot Wallet
        Hot wallet, also known as online wallet, allows the network to access user's private key. Others can access the user's private key through the Internet, which reduces its security while increasing its convenience as compared with a cold wallet.
    JDK
        JDK is the Java SDK used for java applications on mobile devices and embedded systems. It is the core of Java development, comprising the Java application environment (JVM+Java class library) and Java tools.
    KhaosDB
        TRON has a KhaosDB in the full-node memory that can store all the new fork chains generated within a certain period of time and supports witnesses to switch their own active chain swiftly into a new main chain.
    Level DB
        Level DB will be initially adopted with the primary goal to meet the requirements of fast R/W and rapid development. After launching the main net, TRON will upgrade its database to an entirely customized one catered to its very own needs.
    Private Testnet
        Private Testnet: its developers configure their ID and server IP according to Tron's deployment configuration file to participate in testing. Only readily deployed developers are allowed access.
    Public Testnet
        Public testnet: it is similar to TRON's mainnet launched on May 31, which everyone can visit and use.
    RPC
        Remote Procedure Call.
    Scalability
        Scalability is a feature of TRON Protocol. It is the capability of a system, network, or process to handle a growing amount of work, or its potential to be enlarged to accommodate that growth.
    Storage layer
        The tech team of TRON designed a unique distributed storage protocol consisting of block storage and state storage. The notion of graph database was introduced into the design of the storage layer to better meet the need for diversified data storage in the real world.
    Sun
        Sun, abbreviated as S, replaced drop as the smallest unit of TRX.
    Super Representative
        The 27 Super Representatives are the bookkeepers on TRON network. They are responsible for the verification and packing of all transaction data broadcasted on the network. Background information of the SRs are posted on TRON network for public access, and the most convenient way to check out the list of SRs and their information is by using Tron’s Blockchain explorer.
        High throughput is a feature of TRON mainnet. It is also known as TPS, namely the maximum transaction capacity in a second.
    Timestamp
        The approximate of block production time is recorded as Unix timestamp, which is numbr of seconds that have elapsed since 00:00:00 UTC.
    TKC
        Token configuration.
    Token（Asset）
        In TRON's documents, asset is the same as token.
    Transaction
        Transaction refers to the process of token transfer between different accounts.
    Transaction Broadcasting
        Transaction information is verified by nodes and broadcasted in the blockchain network.
    TRON Power
        TRON Power (TP), the power to vote for Super Representatives, can be obtained through balance freezing. TRON Power (TP) can be obtained from balance freezing. All users in TRON's network are entitled to vote for Super Representatives they approve of. To vote, TP is needed, the amount of which is determined by the amount of frozen asset. Calculation of TP: 1 frozen TRX equals to 1 TP. When users unfreeze all balance, they also loose their TPs, which invalidates their votes. To prevent invalid votes, users can refreeze balance.
    TVM（TRON Virtual Machine）
        TRON Virtual Machine (TVM), is a lightweight, Turing complete virtual machine developed for Tron’s ecosystem, aimed at providing millions of global developers with custom-built blockchain system which is efficient, convenient, stable, secure and scalable.
