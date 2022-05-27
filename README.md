# Demo of on-chain verification

## [Front-End](ll)

- Make the user sign a message
- The message consist of:
  - Signature Verifier Contract's address
  - Sender's Address
- Console.log the signature

## [On-chain Contract](signature-verification-demo/src/App.js)

- Take the signature
- compare the two address embedded in the message with contract address and sender address
- extract the signer of the message
- if the sender of the message is the signer of the signature, revert true
- otherwise revert false
