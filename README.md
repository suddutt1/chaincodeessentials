# Fabric chain code enssentials 
Hyperledger Fabric Chain code essentials.


InvokersIdentity.go : Refer to the readTransaction method for reading the creator ( invoker) signature details. This may be utilize the invoker and take appropriate actions in the chain code. 

# Govendoring for chaincode 

```sh

go get -u github.com/kardianos/govendor
govendor init
govendor add github.com/hyperledger/fabric/core/chaincode/shim/ext/cid
govendor add github.com/golang/protobuf/proto
govendor add github.com/pkg/errors


```
