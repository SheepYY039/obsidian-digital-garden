---
{"dg-publish":true,"permalink":"/62-encyclopedic/20220418185143-pragma-in-solidity/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Pragma in Solidity

A pragma is an indicator of the acceptable solidity versions. Because the language is still in its early stages, it has to be included in case there are future breaking changes that modifies the stuff used in a code.

```java
pragma solidity >=0.5.0 <0.6.0;
```

Praga should be the first line in a solidity contract, so it should come before [[61-Archive/20220415192511-contract-in-solidity|the contract block]].
