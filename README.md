

Implementation of ecrecovery in solidity using truffle 

run test:

Open testrpc in another tab

in test derictory:
```
truffle test Authorization.test.js
```

output:</br>
```
    Contract: Authorization
    √ register: owner verify signer (verified[owner][signer] = true) (63ms)
    √ user1 => CheckSig(TEST_MESSAGE, v, r, s, owner) === true
    √ user1 => CheckSig(WRONG_MESSAGE, v, r, s, owner) === false
    √ Random user => CheckSig(TEST_MESSAGE, v, r, s, user2) === false


  4 passing (332ms)
 ```
