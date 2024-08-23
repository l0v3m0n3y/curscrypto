# curscrypto
JavaScript library for curscrypto.ru
# main
```js
async function main(){
    const {curscrypto} = require('./curscrypto');
    const curs= new curscrypto();
    let req=await curs.crypto_list("ru","USD")
    console.log(req)
}
main()
```
