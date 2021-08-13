# Opsec 101

In this guide we'll cover the basics of Opsec in a way that most anyone should be able to understand. This guide is split up into topics designed to be linked to directly for the purpose of convenient educational discussion. 

<br/><br/>

Skip to:

<br/><br/>

1. 

<br/><br/>



## Don't start with countermeasures. Countermeasures come last.

<br/>

A countermeasure literally means a measure of response to counter a threat. It can be a lock on a door, a VPN or firewall on a computer, or even a strong password. All of these countermeasures exist to counter specific threats.

<br/>

* The lock on the door attempts to counter a potential home invasion.
* A VPN attempts to counter a number of cyber threats, but far from all of them.
* A strong password can frustrate attempts to gain unauthorized access

<br/>


Given what we know about home invasions *(2.5 million burglaries annually in the US)*, password cracking and account theft, and cyber threats in general, it would seem quite obvious to start using these countermeasures above without a second thought. But if we’re taking the countermeasure-first approach, why stop there? Let’s go countermeasure crazy!

<br/>


#### Thought experiment

<br/>


* If adding a deadbolt on your doors makes your home safer overall, shouldn’t you add one to every door in your house too so that each time you enter the bathroom you’ll need to find the key for it? This would make it harder for the home invader to access you even once inside.

<br/>


* If VPNs protect you from threats, shouldn’t you always use Tor and always be anonymous, all of the time, even when trying to connect to your bank’s website or to have a video call despite the latency issues?

<br/>


* If strong passwords make you safer, shouldn’t you use 256 character strings of random characters as the password for your phone at work that you frequently need to manually unlock, and change that password daily?

<br/>



It becomes evident that without a clear understanding of why the countermeasure is necessary, you end up down a rabbit hole of wasted energy and time. The countermeasure-first approach is unsustainable, deceptive, and it ignores two critical paradigms:

<br/>


* Convenience is inversely proportional to safety and security. The more secure we make things, the less convenient.

<img src="https://i0.wp.com/37prime.com/news/wp-content/uploads/2013/08/Security-vs-Convenience-Curved.png" width="50%">

<br/>


* The more you attempt to secure something, the more attention it gets, thus potentially increasing the risk of it being attacked or stolen.
To resolve this, we start instead with the opsec process. Opsec is a process and a mindset that is practiced that involves asking specific key questions to help rationally assess a threat and judge the practicality of specific countermeasures against it.

<br/>


*Don’t worry if it seems a little abstract in the beginning. It becomes more obvious as you learn how to ask the right questions.*

<br/>

<br/>

<br/>

## The Opsec process

<br/>

Opsec is a practice or methodology that like all practices, gets better with more practice.

<br/>

Before deciding what countermeasure you should use to stop a threat though, you need to ask the right questions to decide if the threat is serious and practical or not.

<br/>


### What needs protecting?

<br/>

These are referred to as critical assets. If critical assets sounds like a term the military might use, that’s probably because Opsec’s origins are from inside the military. What better way to properly protect a campaign’s mission and its assets using minimal resources than to understand what is and what isn’t actually important to protect in the first place.

<br/>


For most of us, the answer to this question is likely the same: family, home, valuable belongings, personally identifiable information, financial information, passwords, etc. While it might seem obvious that we’d want to protect everything in our lives, all of the time, the truth is it depends on what the threat is.

<br/>


#### Thought experiment

<br/>

* Have you ever left your phone on a desk at work while turning your back on it to talk to a colleague? Couldn’t it have been stolen in that moment?
* Have you ever left your front door open while carrying multiple loads of groceries or moving boxes from the car to the living room? Couldn’t someone have entered into the house in that moment?
* Have you ever given your credit card to a cashier and trusted them to charge it only for the amount of the goods being purchased? Couldn’t they have charged a much larger amount of even stolen your card number for later personal use?

<br/>


The truth is, whether something needs protecting or not largely depends on what the threat is, or more importantly the practicality of the threat. Just as it’s highly unlikely a worker in your office would steal your phone from your desk, it’s also unlikely it would matter if it were properly locked. While it’s true that the cashier could have overcharged you, it’s also true it would likely be easily remedied with very little issue for you but at a huge cost to the cashier.


<br/>


### What is the potential threat?

<br/>


Most people don’t need help identifying a common or obvious threat. There are enough of those in our daily lives to become a habit. We identify them all the time naturally by asking ourselves questions to assess these potential threats.

<br/>

* Who is at my door at 2am and could they want?
* Is that person in the dark alley following me or just walking the same direction?
* Is that person behind me at the ATM intentionally too close to me?
* I’m late for work but the road is icy. Should I drive fast anyway?


<br/>


But not all potential threats are so obvious to everyone.

<br/>


* You sign up for a website to buy your friend a gift and there’s only one left! Out of convenience you use the same username and password you do for another site, which is now stored to their database. That database is later hacked and subsequently leaked on message boards of hackers who will now try those same credentials at various sites in hopes of gaining access to your life and finances.

* You’re on a flight and need to use the paid wifi. While entering your credit card, the passenger in the back seat takes a photo of your card and uses it to order the wifi also.

* You see someone fall over in the street in front of your car and you get out to help them. They start screaming that you hit them with your car (when you clearly didn’t) and call the police and demand compensation.


<br/>



It’s important to try to brainstorm and identify potential threats as early as possible: before you leave on the vacation, before you start the car, before you enter your information into the website’s form. Without practicing opsec, the above threats will need to be learned from experience at a potentially heavy price. 

<br/>



### What are the potential vulnerabilities?

<br/>


Now that you know what you want to protect (e.g. your credit card on a plane) and what the potential threat is (e.g. the person behind you able to see the card’s details or being stolen by other means during the flight), it can be quite straightforward to assess the vulnerabilities. 

<br/>


* Can someone see my card the way I’m holding it?
* If I were in a different seat, what would I see?
* Is the website I’m entering this card information on using an encrypted (HTTPS) connection?
* Is this wifi payment portal really operated by the airline?
* Is this the best or most secure way to pay for this service?

<br/>



Depending on the answers to these questions, you may find that you have none, few, or many potential vulnerabilities. Normally this kind of judgement is possible to do quite quickly.

<br/>



### What is the potential risk?

<br/>


It’s important to know the difference between a vulnerability and a risk. The vulnerability is how it might be possible to attack you. The risk is what you stand to lose if it succeeds.

<br/>


Now that you know the potential threat and potential vulnerabilities, you can ask the more practical questions about the realistic potential risk to you. This is where common sense, rationality, and statistics will serve you well. There is no room for fear and paranoia in this step. 

<br/>



* How much money is on this card?
* How much could be lost?
* How much can I afford to lose if I make a mistake?
* How difficult, time consuming, and inconvenient will it be if I need to order a replacement card if it’s stolen?
* Is the risk worth the trouble for some wifi?


<br/>


Assuming your questions lead you to continue forward, but safely, the next thing to do is to apply the countermeasures to close up the vulnerabilities that will ultimately serve to disable the threat.


<br/>


### What are the countermeasures?

<br/>


Based on the practical potential vulnerabilities already discussed, you’ll now want to remove any of the unrealistic or dismissed threats first.

<br/>


* Can someone see my card the way I’m holding it?
* If I were in a different seat, what would I see?
* ~~Is the website I’m entering this card information on using an encrypted (HTTPS) connection?~~
* ~~Is this wifi payment portal really operated by the airline?~~
* ~~Is this the best or most secure way to pay for this service?~~


<br/>


That leaves us with only two practical vulnerabilities we’re aware of:

<br/>



* Someone sees you typing the credit card information on your phone.

* Someone sees your card information directly.


<br/>


The easiest countermeasure to these is the same for both:

<br/>


* Cover your phone and card with a coat, or hold it down in your lap away from the line of sight of any other passengers until the process is complete.


<br/>




## Practice, practice, practice


The previous examples were largely obvious and wouldn’t necessarily need a document or checklist to discover them. What’s important is the thought process behind them: to be asking the right questions, and to get better at finding the right answers.

<br/>

In the following section, we’ll practice the opsec process and gradually increase the difficulty of these situations and scenarios in story form to gain experience and insight into where gaps in knowledge might lie.



