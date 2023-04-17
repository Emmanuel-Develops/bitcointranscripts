---
title: How Bitcoin Actually Works - Episode 3 | Hello Bitcoin
transcript_by: adamjonas via TBTBTC v1.0.0
 
media: https://www.youtube.com/watch?v=6vQB3XGB7ig
speakers: ["Raghaski"]
date: 2023/04/14
---

## Intro

 Hi, I'm Raghakshi with the Hello Bitcoin Project. Today, we're going to talk about how Bitcoin actually works. You'll see. It's not as complicated as you might think. Let's jump in. If you are going to use Bitcoin, you want to be confident that it will work as you expect it will. Since Bitcoin is a savings technology, there's no messing around. Who would trust their harder and savings to a system they can be absolutely sure about? We've previously made some big claims about all the amazing things Bitcoin can do, like being able to transact instantly with anyone in the world without censorship, like protecting against the threat of inflation, like the freedom to take your money wherever you want. Like perhaps one day becoming a universal global currency. My hope is to help you understand how all these things are possible, thanks to the way Bitcoin is designed and get you comfortable with how it works. And to appreciate how Bitcoin works, let's take a look at how you use it. There's really only two things you can do with Bitcoin. You can own it or you can send it. Send it.

## Owning Bitcoin

 Let's start with owning Bitcoin. Since there are no banks in Bitcoin and it's entirely digital, what does it mean to own some? The first thing we need to do is discard the metaphor of a coin. Bitcoin is not like a coin. More accurately, you should think of Bitcoin as a huge public ledger or spreadsheet that keeps track of who owns what? And kind of incredibly, this ledger is fully public and transparent for all to see. Imagine two columns. In one column you have the who and in the other you have the how much. Instead of using people's names, this ledger refers to owners of Bitcoin with a long sequence of random looking letters and numbers called a public address. Now for the important part. Each entry in this ledger is effectively locked and protected by an unbreakable secret code called a private key that only you have. Knowing the private key to an entry allows you to unlock that amount of Bitcoin for sending. And so it's critical for that secret code or private key to be stored very safely. Loosing your private key means losing access to your Bitcoin forever. Fortunately, there are plenty of straightforward and secure ways of taking care of your private keys. We'll discuss all the possibilities and trade-offs in a future video. Now what?

## Sending Bitcoin

 But if you want to send Bitcoin to someone, for instance, I have lots of relatives in India who are becoming more interested in Bitcoin. Let's look at how I might send some Bitcoin to my cousin there. It's pretty simple. The one and only piece of information I need for my cousin is her public address. Once I have that, I would then open my Bitcoin wallet and add the keeps track of the Bitcoin I own, paste in my cousin's public address, enter an amount, and hit send. That's it. Very soon, my cousin will see your Bitcoin arrive, and then in a little while, those funds would be fully confirmed. This might seem pretty boring. It's exactly what you would expect, right? You send money, it arrives. What's the big deal? What's the big deal?

## The Big Deal

 Well, the big deal is all the stuff you don't see or necessarily think about. First off, the transaction is settled permanently, with no central authority, just a network of computers like mine and yours. It didn't require any identifying information. It was practically impossible to block. It took about an hour to settle rather than days like most international transfers and cost relatively little too. And finally, the big-line I spend could only be spent once. Let's double-click on this last point because it's important. Think about digital things. Because they're just ones and zeros, they're generally not scary.

## Digital Money

 Take photos for example. I can copy and share the same photo with as many friends as I want and basically no cost. Now imagine trying to do this for money. Copying and sending the same $20 bill to as many friends as I want wouldn't work so well would it. So that's why we currently need banks to keep track of everything and make sure that digital money can't be spent more than once. And that's why they coin is so special because even though it is digital it's inherently scarce. The same Bitcoin can't be spent twice and we don't need a bank to keep track of anything. Understanding how all this is possible is where the beauty and power of Bitcoin lie. Let's look under the hood so we can appreciate what's going on.

## Under the Hood

 When my wallet sent my transaction, some fancy math called cryptography was used to sign it with my private key. This proves that I have the permission to unlock and transfer the Bitcoin I want to send. The transaction was then sent to the Bitcoin network. This peer-to-peer network is made up of computers that run the open source Bitcoin software, which is publicly available for anyone to run for themselves. These computers are often referred to as Bitcoin nodes. Some of these nodes take on an important job for the network, arguably the most important job, processing transactions. That is, carefully updating the ledger in a permanent way. This process is referred to as mining and those computers as miners. So, when I send Bitcoin to my cousin in India, it is a miner that would ultimately process the transaction that spends the Bitcoin I am sending and adds a new ledger entry saying my cousin now owns that amount. Updating the ledger like this is obviously a big responsibility and preventing corruption is essential. So, we need to understand a little bit more about how mining works and to understand mining, we need to know about blog.

## How Mining Works

 A block is just a set of transactions that get processed by the network. This happens in big batches a few times every hour. The blockchain is simply the name we give the public ledger that records these transactions over time. And it's done in a way that links every block to the previous one, keeping everything perfectly consistent. Adding a block to the chain or mining a block is very hard work. It takes a huge amount of calculation. It's like a wide open contest that requires lots of computing power in order to participate. Where each mining computer is trying to be the first to successfully do the math that constructs a valid block. And when one minor eventually succeeds, all transactions in this newly added block get processed. Meaning, the ledger is now updated with the new transaction information. Another way, mining blocks is kind of like the heartbeat of the Descartes network. It's what makes transactions flow. But you might be thinking, what's in it for the miners? Why do they bother competing in this global contest to mine blocks in the first place? The answer is straightforward. Mining is a business, like any other. They're just trying to make money. So performing this mission critical transaction processing work for the network, whenever a winning miner mines a block, they get a reward. Payed out in Bitcoin, which maybe seems a bit mundane. Of course, miners should get paid for providing a valuable service to users, right? Here's the cool part.

## New Bitcoin

 A big portion of the reward a minor gets is brand new Bitcoin, like Bitcoin that has never existed before and newly entered circulation. In fact, these mining rewards are the only way that new Bitcoin can ever be minted. You may remember from our first video that it is Bitcoin's absolute scarcity that gives it its power to protect against inflation. With mining, the creation of new money supply happens in a predetermined rate set out in a schedule in the Bitcoin code. There is no room for subjectivity or mismanagement by human beings. Eventually, this schedule gets us to the 6th 21 million Bitcoin maximum, which can never be increased. As important as miners are to the functioning of Bitcoin, equally important is the verification work done by the tens of thousands of people running the open source Bitcoin software on their own computers or nodes. Each of these nodes has their own copy of the big public Bitcoin ledger and it's their job to make sure miners don't cheat. You see, they will only add new blocks to their copy of the ledger once they've verified that miners followed all the rules, like staying in line with the supply schedule we talked about earlier. While no one controls Bitcoin, the strength of the design lies in the fact that everyone participating in Bitcoin users, nodes, miners say their own small part in making it work. Let's do a quick recap. The process of Bitcoin mining does the work of processing transactions and also handles the issuance of new Bitcoin. That's already a lot, but it also does one more absolutely crucial thing that I have to talk about before we close. The thing is what secure is the Bitcoin ledger? How? To answer this, let's go back to my cousin in India. When I sent her Bitcoin, I mentioned that it would take some time before the transaction was fully confirmed. What did I mean by that? What's actually going on here is that we need to wait for a miner to construct a block with my transaction and have it added to the blockchain. Once that happens, the transaction is processed and starts becoming nearly impossible to ever be reversed. As every new block is added to the chain afterwards, all of the work it takes miners to create each block adds more and more permanence or irreversibility to the transaction. After six blocks, sometimes referred to as confirmations in this context, which takes about an hour, most wallets will consider a transaction fully confirmed, essentially etched in stone. And so this is what mining gets us, a ledger that is so secure that after just one hour, transactions become fully permanent and cannot ever be tampered with. This security is all thanks to the underappreciated fact that mining blocks is so computationally difficult that it requires a lot of energy. It may seem counterintuitive at first, but this energy cost is actually a very good thing. Here is why. If you wanted to tamper with Bitcoin by changing an old entry in the ledger, say to spend some of your Bitcoin again, you'd have to outmine the rest of the network. And to do that, you'd need to access more energy than all other miners combined. And so the point is this, the more computing power miners bring online, the harder it is for anyone to come along and mess with Bitcoin. In my mind, I think of mining as creating a giant, impenetrable shield of energy that protects the Bitcoin ledger. We want this energy shield to be as big as it needs to be to keep trillions of dollars to savings completely secure. So in short, Bitcoin mining doesn't waste energy. Instead it transforms it directly into the security that gives Bitcoin its scarcity, permanence and thus value. So to review, today we've covered what it means to own Bitcoin. Look at what happens when you send it to someone and then see that mining gives us the triple benefit of making transactions flow, putting new Bitcoin into circulation and securing the Bitcoin ledger. All of this without any intermediaries we need to trust. Just a big network of computers running free software, coming together to agree that two human beings anywhere on this planet should have the freedom to exchange value and store it securely over time. That's the beauty of Bitcoin. Of course, there's a lot more detail to how it all works. But I wanted to cover just enough so that you can appreciate how special Bitcoin is and so that you too are able to use Bitcoin with complete confidence. See you next time!

