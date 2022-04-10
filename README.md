# Paper wallet generator for cryptocurrencies (QR codes)
By visiting [simplyjarod.github.io/crypto-paper-wallet](https://simplyjarod.github.io/crypto-paper-wallet/) you will be able to:  
- Generate new random private key.
- Use your private key from raw or base 58 format.
- Print (you can save as pdf) file with QR codes and plain text containing public and private keys.
- By now, only Solana (SOL) addresses are supported. 12 and 24 word seed phrases might be supported some day.  

**All the data used/generated/imported/exported will only be accesible from your browser/computer.**

**Don't trust, verify!** This project has been created as a public github repository to let you verify the code behind the website [simplyjarod.github.io/crypto-paper-wallet](https://simplyjarod.github.io/crypto-paper-wallet/) so you can prove that data never leaves your computer.

## Libraries/Frameworks used
- [Bootstrap v5.1.3 from jsdelivr](https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css)
- [Solana web3 v1.37.1 from unpkg](https://unpkg.com/@solana/web3.js@1.37.1/lib/index.iife.min.js)
- bs58 npm module (exported with browserify)
- [QR code JS (by davidshimjs) from cloudflare](https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js)