### Is there a real-world use case for crypto for a normal person that doesn't involve breaking the law? 

Yes.

Let's imagine you are an investigative journalist who needs online privacy due to the sensitive nature of your work. Imagine you're investigating powerful people in the government. Or, if you're of a certain [ideological persuasion](https://www.unqualified-reservations.org/2009/01/gentle-introduction-to-unqualified/#cha-0_footnote-5) and this an uncomfortable fiction, just imagine you are hiding from the state while you wait for it to implode. Either way, strap on your tinfoil hat and let's proceed.

### You need a VPN

The first step in achieving online privacy is to cloak your [[IP address]]. The most user-friendly way to cloak your address is through a Virtual Private Network (VPN) provider. When you use a VPN and visit a website, the website sees the VPN IP address instead of yours.

There's a pretty large issue with VPNs, however: You are centralizing all your web-based activity into one location -- the VPN provider. You have to trust that the VPN provider isn't collecting your browsing information and storing it or and selling it.

To help alleviate your concerns you [find a service](https://mullvad.net/en/servers/) that not only accepts an anonymous crypto payment, it also keeps no payment records other than an account number (no Know Your Customer rules), stores no logs, and runs its software in RAM only. Nothing is ever completely private on the internet, but this is about as good as you can get. And unlike with something like [Tor](https://www.torproject.org/), speeds are fast. You'll be able to use all of that gigabit internet speed that you're paying for.

### Let's buy some crypto

Now you just need to turn your silly fiat dollars into crypto and pay for a few months of service. But there's a problem. You can buy Bitcoin on an exchange like Coinbase, no problem. But Bitcoin is famously public. Anything you buy with Bitcoin is stored on the blockchain for everyone to see, forever. And since you had to go through Know Your Customer onboarding on Coinbase to purchase the Bitcoin, the VPN payment can easily be traced back to you. No bueno.

### Let's buy some other crypto with our crypto

To address this issue, the VPN accepts a truly private crypto currency called Monero. Coinbase doesn't allow you to purchase Monero, however (presumably because US authorities are unable to trace it). So to privately buy this VPN service in a way that doesn;t lead directly back to you, you'll have to buy Bitcoin at Coinbase *and then* convert it to Monero...[somewhere else](https://localmonero.co/). Are you ready to be your own bank? Damn right you are. You buy $100 of Bitcoin through Coinbase and head over to localmonero.co with no "m".

You don't have a VPN you trust yet, and buying a coin that's mainly used for illegal activities directly from another person on the internet is about as risky as it gets. You're breaking no laws, but yikes on bikes. And remember, you have a reason to be paranoid. 

### Let's buy some other crypto with our crypto over Tor

Luckily, the site allows you to access the marketplace using an [onion address](http://nehdddktmhvqklsnkjqcbpmb63htee2iznpcbs5tgzctipxykpj6yrid.onion/) over the Tor network. So you fire up your Tor browser, input the onion address and...wait. And wait. Tor is very slow. After what feels like minutes, you're asked to solve a captcha because the site says it has been under attack recently. You feel uneasy. 

The site loads and you poke around and find a seller who has turned on the "[arbitration bond](http://nehdddktmhvqklsnkjqcbpmb63htee2iznpcbs5tgzctipxykpj6yrid.onion/nojs/faq#protection)" setting, which helps protect you from the seller stealing your Bitcoin. You place an order for $95 worth of Monero (that's your original $100 less the Coinbase fee) paid for in Bitcoin, which at the time of this writing is 0.00573322 BTC. While you are reading the directions the price of BTC changes and you are asked to confirm the new price.

You also note the warning in bright yellow. It says

>**Make sure the address you've pasted is the same as the address you've copied!** Some users have gotten their funds stolen by [malware replacing the address copied to clipboard with the attacker's address](https://reddit.com/r/Monero/comments/mcvuxc/beware_crypto_stealing_malware/).

You feel even more uneasy. You double check your Monero wallet address (you downloaded a [Monero wallet](https://www.getmonero.org/downloads/), right?), and click to proceed. 

### Chatting with bots

You're confronted with an automated chat bot that asks you to confirm the type of cryptocurrency you'll be paying with by typing the crypto's short code in the chat (i.e. "BTC"). This is so it can give you the appropriate wallet address. 

Before you do, you notice another message in bright red. It reads:

> Warning: only get the seller's address in this trade chat or from the payment details section on this trade page and do not send payment transaction IDs outside of this trade chat! We also recommend that you keep all communications in this trade chat.

Your ears start to tingle. You're glad you found a seller who uses arbitration bond because all of this feels massively shady. You inform the bot you'll be paying in Bitcoin, and it gives you an address. You copy it, then change your browser tab back to Coinbase. You input $95, watch it get converted to Bitcoin, enter the wallet address you got earlier and hit send. Coinbase alerts you it could take up to 30 minutes for the payment to process.

You head back to the Monero exchange site and inform the bot that you've paid. The bot replies

> 🤖 You have marked the trade payment as complete. Your Monero will be released as soon as your payment appears in the account. This usually depends on network congestion and the priority fee of your payment.  
> 
> If you accidentally didn't send enough, you will be notified. You can send from multiple wallets/accounts and it will be combined.

You don't understand what a priority fee is, so you wait. And wait.

About 28 minutes later you see the first confirmation of your payment on the [block explorer](https://www.blockchain.com)link that Coinbase provides. Excited, you check to see if the bot has updated the chat with information about your Monero. No such luck. So you wait some more.

Suddenly the bot comes to life.

>🤖 I have received 0.005691 BTC of the 0.005959 BTC requested.  
   0.000268 BTC remains.

The bot says that you're a little short. You're not sure what happened -- did the price of Bitcoin go down again? Was there a fee you forgot to account for? You head back to Coinbase and buy another $10 worth of Bitcoin, punch in the amount you owe (a little under $5) and send it to the bot.

The 30 minute timer resets for this new payment. You decide to doom scroll on Twitter to pass the time. 20 minutes later you get another message from the bot

> 🤖 Payment cleared. Your coins have now been released. Allow up to 2 hours for the funds to arrive. Thanks for the trade and good luck out there.

FML. More waiting. More doom scrolling. About a half an hour later you see the transaction appear in your Monero wallet as unconfirmed. Things are looking promising, but you can't spend anything just yet. More waiting. Twitter beckons. So does the abyss.

### Let's buy that thing we were going to buy

At last, 2 hours after starting this crypto adventure, your wallet informs you that you have .69 (nice) Monero to spend. What were we doing here? Oh, right, we're buying a VPN...which feels like such a let down? With all this tradecraft it would be way cooler if it were stolen Imperial plans.

You head over to Mullvad, open an account, and click on Monero. Mullvad kindly gives you 10% off your purchase for using crypto, which is good because right above it is a cash option that would have been cheaper without the discount. 

![[ksnip_20221119-173352.png]]

You send enough Monero for a year. 

And then wait another 30 minutes.

Congrats, you now have a VPN that can't be traced back to you, giving you pretty good privacy on the big, bad internet. All it took was two and a half hours and two crypto exchanges. You could have accomplished the same thing by mailing cash over to the company, which seems much more straightforward and perhaps even more private, but where's the fun in that? Cash is for plebes. We're going to the moon.


