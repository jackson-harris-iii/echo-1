MyEcho 
==================
DEMO: https://echo-1.vercel.app/

Abstract. Centralization is bad for all stakeholders. We’re providing a way to decentralize something the average internet user today will understand. If we do our job right, they won’t be sure they’re using crypto at all.

Introduction
What's broken about crowdfunding. 

What everyone knows is broken
Fees
Censorship
Payout time tables

What crypto positive people know is broken
Not your db not your data
Not your keys, not your crypto.

Everyone loses in the crowdfunding space. Users pay high fees, in many cases they don’t own their content, and the content they can and can’t create is subject to the whims of the platform. 

Platforms are constrained by payment gateways/processors/banks resulting in a struggle between doing what's best for users and what's best for the platform. 

By using scalable decentralized services we eliminate many of these concerns. 

We realize some issues may need to be resolved in part with (censorship), but we plan to implement self governance and voting where the community can decide what content should be disallowed.

The DApp

MyEcho provides a secure / decentralized way for creators and supporters to interact with each other. MyEcho will be Web 2.0 on the outside and Open web throughout. Accounts will use familiar features (google, facebook, etc.) on the surface, but NEAR protocol & Tor.us/Ceramic under the hood. Data will be accessible and permissioned through the DApp, but stored in and managed in decentralized services; Skynet/Ceramic.

This app was initialized with [create-near-app]

Quick Start
===========

To run this project locally:

1. Prerequisites: Make sure you've installed [Node.js] ≥ 12
2. Install dependencies: `yarn install`
3. Run the local development server: `yarn dev` (see `package.json` for a
   full list of `scripts` you can run with `yarn`)

Now you'll have a local development environment backed by the NEAR TestNet!

Go ahead and play with the app and the code. As you make code changes, the app will automatically reload.

***THIS APP USES NEXT JS AND REQUIRES SOME CHANGES TO THE create-near-app ***

Exploring The Code
==================

1. The "backend" code lives in the `/assembly` folder. This code gets deployed to
   the NEAR blockchain when you run `yarn deploy:contract`. This sort of
   code-that-runs-on-a-blockchain is called a "smart contract" – [learn more
   about NEAR smart contracts][smart contract docs].
2. The frontend code lives in the `/src` folder. `/src/index.html` is a great
   place to start exploring. Note that it loads in `/src/index.js`, where you
   can learn how the frontend connects to the NEAR blockchain.
3. Tests: there are different kinds of tests for the frontend and the smart
   contract. The smart contract code gets tested with [asp], and the frontend
   code gets tested with [jest]. You can run both of these at once with `yarn
   run test`.


