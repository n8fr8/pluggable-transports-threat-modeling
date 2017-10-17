## Chapter 7: People and Stories

 \*\*\*\*\*

 PERSONA / USER or ADVERSARY STORIES

  


Student activist expulsed from Chad, by government that had been listening to his email traffic. 

  


Balai Citoyen -- Collaboration of rap singers and bloggers that arranged large-scale demonstrations in Ouagadougou that lead to the military inviting the dictator Blaise Campoare to leave the country.

  


CPJ representative in West Africa coordinating activities to defend journalists.

  


Journalist attempting to put in place research that would embed him within Boko Haram to write articles explaining their world-view.

  


One of our trainees had a friend tortured to death in Cameroon for being gay. Gay people in sub-Saharan Africa under constant threat of violence. Need to hide their identity. Private communications needed to remain safe.

  


Journalist for BBC/Deutsche Welle recieved leaked information from police identifying him as some-one to be arrested on sight. Uses Tor to contact collegues to arrange travel to leave country.

  


Popular blogger receives threats of violence from local organized crime group. Uses Tor to contact colleauges to arrange travel to leave country and get to safety.

  


  


  


  


  


Adversary: Joe is an Enterprise IT network administrator at a health provider company who has been told to monitor all outbound network traffic to detect any incident of improper use of personally identifiable information or other health data. To do so, he has configured all work stations to have a corporate certificate installed, allowing him to decrypt and re-encrypt any TLS/HTTPS traffic on the network. While data is encrypted, a basic pattern match is run to look for strings matching names, social security numbers, dates, addresses or other private data. As a pre-caution Joe has also blocked Tor, common VPN protocols and services, and other network traffic he may not be able to intercept.

Developer: Pema is a software developer at VPN company whose service was recently blocked in the United Kingdom. She has been tasked with coming up with new variants of their protocol that can get around the fairly simple techniques that the local ISPs and mobile operators have been using, including DNS poisoning, blocking common ports, and throttling to sites that are not whitelisted. She has some really cool ideas related to hiding servers in cloud servers, using P2P tricks, and maybe even the super cool blockhain ninja magic. Unfortunately, she doesn't really know anyone who has done this before, and has just found some academic papers on interesting techniques like Domain Fronting and Decoy Routing.

  


Adversary: Fred is a manager for a commercial censorware provider.  To sell upgrades, Fred must credibly promise that they can prevent users from viewing unauthorized content.  Fred has an incentive not to offer permanent solutions, since if today's tool still works next year, Fred won't be able to sell upgrades.

  


Adversary: Lisa is a manager for a government-operated internet censorship division. She generally agrees that harmful content should be blocked, and tries to make sure that anticensorship tools are ineffective.  Left alone, she is mostly concerned with blocking popular tools.  But whenever an issue risks presenting an embarrassment to her division, her boss, or some other influential political figure, it takes top priority. She used to buy Fred's software, but it scaled poorly, and it took too long to adapt to new tools.

  


Adversary: Heidi works together with Lisa, but specializes in intelligence instead of censorship.  She does not try to \_disrupt\_ anticensorship tools, but instead wants to compromise them so she can monitor their users.  She would like to collect as much data as she can, but she is especially interested in "dissident" groups of people.  She loves it when a dissident group starts using software nobody else uses.

  


Adversary: Katrina works together with Lisa and Heidi, but she isn't in the network security business. Instead, she wants to recruit others to do their censorship work for them!  So Katrina's team tries to troll and smear the anticensorship world, commit obnoxious and public crimes through PTs, and generally lower the morale and public image of the anticensorship world.  She's thinking about funding "Malvolio" below.

  


Adversary: Kevin hates some group of people, and has time on his hands. He likes to run wireshark at a coffee shop where a lot of them hang out, and see if he can find confidential information about them. He posts this information on a public message board, hoping that others will harrass his victims.  Soon, he's going to start running a PT server to eavesdrop on more of these people.  He reads a clandestine blog that Katrina's group runs.

  


Adversary: Malvolio writes pluggable transport code.  He's a great marketer, and a good network programmer, but he sucks at security.  He doesn't care.  He wants everybody to run his pluggable transport anyway, so he can get more publicity \(and maybe funding?\).  He has decided that effort in marketing will produce higher marginal returns than effort in security.

  


Adversary: Gemma is the IT director at a corporation. She doesn't approve of censorship or oppression, but she she won't tolerate any threat to her network.  An attacker uses a PT-enabled tool to try to launch a SQL injection attack against her website; or ran a successful attack, and used a PT to hide the backdoor. After closing the hole, Gemma tells her team to make tools to identify and block all PT-delivered traffic, and plans to share the tools with as many others IT departments as possible.  Fred and Lisa and Heidi will use her work.

  


  


User: John lives in Shenzhen, China, and tries to use a PT to get around the GFW. It seems to work fine for a while, but then the government detects the PT from his connection. His internet ends up being suspended by his ISP, and his ISP has forwarded a message from the police to go to the police station to sign a waiver that he will not try to circumvent the firewall again.

  


User: Bob works for a government agency with extremely stringent internet restrictions. All workstations have a self-signed root certificate installed \(So all HTTPS communications may be decrypted\), and only traffic on TCP port 80 and 443 traffic are allowed through. He has tried VPN protocols that run on those ports, only to discover that they are also blocked. He is looking for a PT that can wrap around his connection so that he may use the internet freely at work.

  


Adversary: George works at a VPN company that is really a front run by a government known for censorship. He helps to set up and market a PT that claims to circumvent said government's censorship, but really, it just helps the government identify those who are trying to bypass said censorship.

  


A Security company was hired by the Syrian government to analyze worth of 6 month of traffic for what is known to be a PT traffic generated by a custom designed human rights violations documentation tool which was found on an activist’s smartphone. 

The goal is to get as much as they can META data generated and by using AI, trying to build a character for the PT then find who is using it to take actions the users inside the country and maybe create a filter/script to block the traffic in the future.

  


  


User: Fatima - Working for women's rights in Saudi Arabia, has been recruited by a known women's rights activist "XX" under surveillance by the government.  Because all of XX's computer usage is monitored and her systems can be seized at any time, Fatima, who is not currently under suspicion \(as far as we know\) will serve as XX's contact to transmit and receive information electronically.

  


A concealed server is maintained in the U.S. by the State Department for transmission.  She needs to:

  1\) Be able to transmit/receive the data in encrypted form.

  2\) Needs to beat deep packet inspection

  3\) Needs to appear to be totally innocuous. \(Web surfing for innocuous data.\)

  4\) Needs to download updates/instructions without appearing to do so.

  5\) Needs to be able to destroy the traces of data if she does come under 

   suspicion/surveillance.

Agent XX is under direct and targeted surveillance by her government, with her computer able to be seized without warning and her belongings searched without warning or possibly her knowledge.  Can she appear to be innocous web traffic under this kind of highly targeted surveillance?  What options are open?

User: Greg uses Tor at a coffee shop in the U.S., but a lack of background Tor traffic makes his traffic personally identifiable.

  


User: State actors need to connect with other agents in a contested environment with both network and physical surveilance.

  


Adversary: A hostile government wants to identify power grid traffic \(VISA, etc.\), so they perform BGP highjacking to re-route the traffic through their AS.

  


Adversary?: non-hostile entity wants to identify potential bots by analyzing Tor traffic.

Alternatively: a botmaster wants to hide C

&

C traffic.

  


