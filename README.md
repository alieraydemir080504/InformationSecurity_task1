# InformationSecurity_task1

## x)

### Threat modelling

#### Braiterman et al 2020

- Threat modeling allows the user to simulate and imagine what could go wrong in a system
- Threat modeling follows 2 guidelines called Values and principles, values are more about communicating and collaborating with people to find solutions, whilst principles focus more on viewpoints and approaches to fix said issue
- Anyone who is interested in protecting various aspects of safety and security should concern themselves with threat modeling

#### Shostack 2022

- We threat model to anticipate problems when it's inexpensive to deal with them
- 4 Questions you need to know about threat modeling: What are we working on, what could go wrong, what are we going to do about it and did we do a good job?
- Developing a document of record can contribute to learning and development on the system a person is currently working on
- Data flow entities are very frequently used for  threat modeling which contains: external entities, data flows, data stores, trust boundaries and processes
- STRIDE helps us to think structured about possible threats

#### OWASP CheatSheets Series Team 2021

- Threat modeling is usually performed in the early stages of the design phase
- Applying this concept places us into the perspective of the attacker which can help discover security risks early on
- Data flow diagrams are the most common approach for threat modeling
- There can be many challenges for a development team such as the lack of knowledge regarding security, too much time involvement, lack of tools and communication between different parties
- Investment in IT security training is necessary for the development of firm systems

### Infosec scene (Stacc Attack)

- The story starts from the perspective of a person called Jack Rhysider who speaks with someone else called Jarett
- Jarett is someone who stole millions of dollars worth of cryptocurrency which is why this episode is called Stacc Attack
- Jack and Jarett talk about cryptocurrencies in general and if they're worth investing into, for example Ethereum or Bitcoin and about the collapse of several markets
- Jarett talks about his mothers death and how he struggled in his life 
- He later then talks about a scheduling software called Clockwork and how he used it to benefit himself
- They talk about Pump.fun which is like a online casino to trade Meme Coins and how addictive it was
- Later in his life, Jarett got hired by Pump.fun and moved to the UK, he was very thrilled
- We also discover that Jarett is on antipsychosis medication because of ADHD, we also hear from him that Pump.fun makes hundreds of millions of dollars per month
- Jarett finds it ridicoulous how Meme Coins can be that popular
- Jarett claims that there are videos of underage girls on certain telegram sites but Jack doesn't ask any further questions, these sites are comparable to 4chan according to Jarett
- The team which works for Pump.fun claims that they have never encountered such issues like Jarett mentioned before, Jack talks about the nasty things he has found out
- Jarett accepts that his actions have consequenses and confronts his past mistakes which is also to blame for the amount of suffering he had to endure
- The more Jack talks with Jarett the more he understands why he is in such a dark place
- Jarett was surprised himself wehn he noticed that his approach worked, it multiplied over time, he says he was able to see what people were doing on the system
- In the end, he pled guilty on the internet, he got caught at 2-3 am in the morning and has to serve a minumum of 7 years in prison
 

## a) Security Hygiene

- When leaving your device unattended, always make sure to lock it
- Always try to use strong passwords and multi-factor authentication
- Unknown/Suspicious pop-ups, links or webpages should be avoided
- When using puplic Wifi-networks, make sure to use VPN for privacy and anonymity
- Use firewall protection
- Please backup your files and keep your security software up to date
- Do read the privacy policy
- Invest in training and education to protect yourself
- Think twice when sharing personal information


  ## b) Make-belief boogie-man

  ### What are we working on?

  #### Company idea

  MediaKing is a company which sells several different technical components from PC parts to video games themselves. They have an online shop where the customer can order whatever they which, but they have to be registered first. When the customer orders an item, this order is being processed in the backend of the system. As the order has been completely validated in the system, it is ready for shipment.

  #### Priorization

  - Security of the customer data (name, adress, etc.)
  - Products and service data (Webshop)
  - Database for orders and items in general
  - A good system to manage orders and shipments
  - Different payment methods (ApplePay, Paypal, ...)
  - The customers trust into the company
 
  #### Customer related matters (crown jewels and interactions)

  - Customer interacts with the webshop and searches for different items
  - Reaching support and interacting with the payment page is no issue
  - After an order, the customer is being informed that the order was successful and is being shipped, notification via webpage itself or email
  - Employees provide customer with the maximum amount of security for their personal data and payment
  - They make sure that the order itself cannot the manipulated in any way

  #### Tech company sketch


<img width="1561" height="621" alt="ThreatModel drawio" src="https://github.com/user-attachments/assets/692eed6f-9754-4df0-b954-837fcc959b71" />

### What can go wrong?

#### CIA

##### Confidentiality

- Phishing scams can happen to customers/employees
- Personal information can be sent to the false people
- Relationship between customers and employees can be severely damaged over time
- Company projects can be leaked

##### Integrity

- General human errors like typos, deletions, misconfigurations, etc. may occur
- Installations of Malware could be utilized by hackers to damage webpage credentials
- Software bugs can lead to calculation errors which could produce payment imbalance
- Webpage may enounter synchronization errors which can lead to customer dissatisfaction
- Product data or customer orders can be manipulated 
  
##### Availiability

- Webshop could become way too slow or even unusable for the customer
- Product transactions could fail
- Inevitable environmental factors such as floods, storms, etc. can hamper the companys revenue
- Company files and systems could be attacked by ransomware, demanding payment from the company
