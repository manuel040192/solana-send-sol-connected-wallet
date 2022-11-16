**Solana Next.js TypeScript Send SOL with A Connected Wallet**

Highlighted information:

In the file components/SendSolForm.tsx, in the return statement, there's the code { publicKey ? ... : ...} and the code { txSig ? ... : null } . The first code means that when there's a connected wallet where a Solana address that has a public key (that is read by the web app) is logged in, a code will be rendered, and if there's no read public key, another code will be rendered. And the second code is like the first one but has to do with a completed transaction's information that can be seen on Solana Explorer with a link that's rendered after the transaction has finalized.
