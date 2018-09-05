"# Smart-Contract-ECDSA-signature-verified" 

The implementation of ecrecovery in solidity using truffle 

run test:

Open testrpc in another tab

in test derictory:
```
truffle test Authorization.test.js
```

output:</br>
```
  Contract: Authorization
    √ register: owner verify signer (verified[owner][signer] = true) (87ms)
    √ user1 => CheckSig(TEST_MESSAGE, v, r, s, owner) === true (64ms)
    √ user1 => CheckSig(WRONG_MESSAGE, v, r, s, owner) === false (46ms)
    √ user2 => CheckSig(TEST_MESSAGE, v, r, s, owner) === true (68ms)


  4 passing (447ms)
 ```
