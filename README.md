**Solana Next.js TypeScript Send SOL with A Connected Wallet**

https://solana-send-sol-connected-wallet.vercel.app/

Información destacada:

En el archivo components/SendSolForm.tsx, en la declaración return, hay el código { publicKey ? ... : ...} y el código { txSig ? ... : nulo } . El primer código significa que cuando hay una billetera conectada donde hay una sesión iniciada con una dirección de Solana que tiene una clave pública (que es leída por la aplicación web), un código será ejecutado, y si no hay una clave pública leída, se ejecutará otro código. Y el segundo código es como el primero pero tiene que ver con la información de una transacción completada que puede ser vista en Solana Explorer con un enlace que es renderizado después que la transacción ha finalizado.

Highlighted information:

In the file components/SendSolForm.tsx, in the return statement, there's the code { publicKey ? ... : ...} and the code { txSig ? ... : null } . The first code means that when there's a connected wallet where a Solana address that has a public key (that is read by the web app) is logged in, a code will be executed, and if there's no read public key, another code will be rendered. And the second code is like the first one but has to do with a completed transaction's information that can be seen on Solana Explorer with a link that's rendered after the transaction has finalized.

![This is an image](https://i.postimg.cc/SsjCKS1g/Send-SOL-with-A-Connected-Wallet.png)


