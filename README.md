# web-wallet

Nebulas wallet for the web. Nebulas users can use it to send transactions and submit smart contracts.

Nebulas already has a JavaScript library [neb.js](https://github.com/nebulasio/neb.js) that implements address generation, transaction signing, and submission. Web-wallet can be implemented using this library.

### TODO list

- api server testnet.nebulas.io returns access-control-allow-origin: (origin in request header), when open index.html through file: it's origin is null and in this case chrome disallows js from accessing ajax content, so this api setting needs change
- generate nebulas address/account [done]
- send transaction (NAS & NRC20) [send NAS has done.]
- send offine transaction [done]
- view address/account info [done]
- view transaction status & info
- deploy/call smart contract
- choose nebulas network(Testnet, Mainnet etc.)


Thanks to @luoman for implementing a pre-version [naswallet](https://github.com/nebulasio/explorer/tree/master/nasWallet) for us.

## Contribution

We are very glad that you are considering to help Nebulas Team, including but not limited to source code, documents or others.

If you'd like to contribute, please fork, fix, commit and send a pull request for the maintainers to review and merge into the main code base. If you wish to submit more complex changes though, please check up with the core devs first on our [slack channel](http://nebulasio.herokuapp.com) to ensure those changes are in line with the general philosophy of the project and/or get some early feedback which can make both your efforts much lighter as well as our review and merge procedures quick and simple.

Please refer to our [contribution guideline](https://github.com/nebulasio/wiki/blob/master/contribute.md) for more information.

Thanks.

## License

The go-nebulas project is licensed under the [GNU Lesser General Public License Version 3.0 (“LGPL v3”)](https://www.gnu.org/licenses/lgpl-3.0.en.html).

For the more information about licensing, please refer to [Licensing](https://github.com/nebulasio/wiki/blob/master/licensing.md) page..

