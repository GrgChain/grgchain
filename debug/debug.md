# orderer.example.com
## env
``` 
FABRIC_CFG_PATH=/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/ordererOrganizations/example.com/orderers/orderer.example.com
FABRIC_LOGGING_SPEC=INFO
ORDERER_GENERAL_LISTENADDRESS=0.0.0.0
ORDERER_GENERAL_GENESISMETHOD=file
ORDERER_GENERAL_GENESISFILE=/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/channel-artifacts/genesis.block
ORDERER_GENERAL_LOCALMSPID=OrdererMSP
ORDERER_GENERAL_LOCALMSPDIR=/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/ordererOrganizations/example.com/orderers/orderer.example.com/msp
ORDERER_GENERAL_TLS_ENABLED=true
ORDERER_GENERAL_TLS_PRIVATEKEY=/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/ordererOrganizations/example.com/orderers/orderer.example.com/tls/server.key
ORDERER_GENERAL_TLS_CERTIFICATE=/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/ordererOrganizations/example.com/orderers/orderer.example.com/tls/server.crt
ORDERER_GENERAL_TLS_ROOTCAS=[/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/ordererOrganizations/example.com/orderers/orderer.example.com/tls/ca.crt]
ORDERER_GENERAL_CLUSTER_CLIENTCERTIFICATE=/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/ordererOrganizations/example.com/orderers/orderer.example.com/tls/server.crt
ORDERER_GENERAL_CLUSTER_CLIENTPRIVATEKEY=/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/ordererOrganizations/example.com/orderers/orderer.example.com/tls/server.key
ORDERER_GENERAL_CLUSTER_ROOTCAS=[/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/ordererOrganizations/example.com/orderers/orderer.example.com/tls/ca.crt]

```

# peer0.org1.example.com
## evn
``` 
CORE_PEER_MSPCONFIGPATH=/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/msp
FABRIC_CFG_PATH=/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com
CORE_VM_ENDPOINT=unix:///var/run/docker.sock
FABRIC_LOGGING_SPEC=INFO
CORE_PEER_TLS_ENABLED=true
CORE_PEER_ID=peer0.org1.example.com
CORE_PEER_ADDRESS=peer0.org1.example.com:7051
CORE_PEER_LISTENADDRESS=0.0.0.0:7051
CORE_PEER_CHAINCODEADDRESS=peer0.org1.example.com:7052
CORE_PEER_CHAINCODELISTENADDRESS=0.0.0.0:7052
CORE_PEER_GOSSIP_EXTERNALENDPOINT=peer0.org1.example.com:7051
CORE_PEER_LOCALMSPID=Org1MSP
CORE_VM_DOCKER_HOSTCONFIG_NETWORKMODE=host
CORE_CHAINCODE_BUILDER=hyperledger/fabric-ccenv:gm1.4.2
CORE_CHAINCODE_JAVA_RUNTIME=hyperledger/fabric-javaenv:gm1.4.2
CORE_PEER_TLS_CERT_FILE=/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_KEY_FILE=/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_TLS_ROOTCERT_FILE=/home/jonluo/gopath/src/github.com/hyperledger/fabric-sdk-go/example/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/ca.crt
```

## cmd 
```
node start
```
