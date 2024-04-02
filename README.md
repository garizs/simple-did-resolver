# DID Resolver

A simple Decentralized Identity (DID) resolver package for JavaScript.

## Installation

Install the package using npm:

```bash
npm install simple-did-resolver
```

## Usage

```javascript
const DIDResolver = require('simple-did-resolver');

const resolver = new DIDResolver();

const didToResolve = 'did:example:123456789';
resolver.resolve(didToResolve)
  .then((resolvedDocument) => {
    console.log('Resolved DID Document:', resolvedDocument);
  })
  .catch((error) => {
    console.error('Error resolving DID:', error);
  });
```

## API

### `resolve(did)`

Resolves the given DID and returns the corresponding DID document.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
