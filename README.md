# hardhat-plugin-noop

The [hardhat-verify](https://www.npmjs.com/package/@nomicfoundation/hardhat-verify) package is useful to reuse outside of Hardhat for other applications that wish to submit Solidity contract sources to Etherscan, Sourcify, and Blockscan but its dependency on the main `hardhat` package is a superfluous.

This package can be loaded in a `package.json` file like this:

```
{
  "dependencies": {
    "@nomicfoundation/hardhat-verify": "^2.0.8",
    "hardhat": "npm:hardhat-plugin-noop@0.0.1"
  }
}
```

## License

MIT
