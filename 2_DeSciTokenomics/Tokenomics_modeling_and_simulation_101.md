# Tokenomics Modeling and Simulation 101 — By Dominikus Brian | DreamBrook Labs. (v1. 30/06/2024)

---

Let’s call this extra section Tokenomics Modeling and Simulation 101:Since there’s currently lack of clear definition specifically on what does in means to do Tokenomics Modeling and Simulation, here we attempt to first begin with a working definition. 

“Tokenomics Modeling and Simulation here will refer to a mathematical modeling approach toward designing the dynamics of how the economic system around a particular cryptocurrencty or blockchain-based token, the simulation part is the process in which the constructed model was allowed to interact with other system and evolves over time. “ 
(this definition is the first version of our thought, and should be refined as necessary in later updates)

Naturally, Tokenomics Modeling and Simulation can thus become a versatile tool in helping Web3 projects and crypto-related founders/team to design an economic incentive system that could help their project or platform move further toward their intended mission. Depending on the original mission or intention for the Token inception, the token could be categorized into different archetypes, and therefore each will require different emphasize on the way of what and how it should be modeled. The work of Luis et.al from Zurich univ back in 2018 “To Token or not to Token: Tools for Understanding Blockchain Tokens”, introduced 8 types of Token Archetypes that could be a general consideration/template designing new project. The archetypes include token as cryptocurrency, as equity token, consensus token, voting (or governance) token, asset token, and so on. In recent years there are also many new forms of tokens like soul-bound token, privilege token, citizenship token and many more.  

In regards to modeling and simulation, this avenue of study is inherently multidisciplinary requiring understanding on both microeconomics of the involved community, the macroeconomics that influence general trend outside the project,  and at the same time some degree of probability and statistics, along with leading concept like game theory mechanism.  

The designation of token mission as described above is in fact can be considered as the first key step in building Tokenomics model. The next step that follows is to define the Token Supply and Distribution, which will cover how many tokens will be generated, and what will be the distribution mechanism, schedule, and so on. Depending on the project agenda the token utility will led to creation of different economic agents. For instance, if we consider Decentralized Science (DeSci) as an illustration we will generally consider the funder of research and the researcher doing experiment to be main agent of economy that will be the driven and beneficiary of the token utility, and there will also be the general public that will benefit from reading or using the research output. Interestingly, here we note in passing, in a token-based system the boundary between supply (producer) and demand (consumer)
when it comes to economic agent is a bit blurred. In the neo-economics literature this usually described as Prosumer, following the term coined by renowned futurist Alvin Toffler in his book The Third Wave [2]. 

Having the Agents involved in the model the mechanics of the models will then be defined by means of setting the Incentives and Rewards for and between these different economic agents, and often also under different scenarios. Each of these agents will then be represented mathematically as a variable, and the incentive and rewards will in turn be a set of functions that illustrate or describe their interaction. The Governance Protocol should then be defined as a boundary condition for the interaction, and depending on the context where ever appropriate decision making will serve as a specific operation on the model. With all the above components the modeling of tokenomics can then began.  

For each simulation a specific scenario is ought to be defined, by means of setting the value of parameters in the above components to specific numbers which then group together to represent a particular possible scenario. For example, the supply will be fixed on 1 million tokens, the incentive is x number of tokens for activity a, and 2x amount for activity b. The Governance will be involved like what to do in different circumstances, and how token distribution or schedule may or may not be modified.  

With all the initial values set the tokenomics modeling could then be run say using a propagation algorithm like ordinary differential equations such as the Runge-Kutta methods, Euler, or even Finite Difference Methods, and so on. The propagation will involve the rate of change or interaction between variables defined in each scenario. Out of this tokenomics modeling and simulation, one could then observe and study properties of the system such as how the inflation will affect price of tokens after certain duration of time. Questions such as, how different vesting schedule will influence the dynamics of token availability in the market? What are the most appropriate incentive amount and reward mechanism to promote ecosystem growth? could then be asked and researched in detail. 

Of course, as in any mathematical modeling, any tokenomics model and simulation will never be perfect, but if they are designed meticulously and with ultimate care on assumptions and understanding of the ecosystem’s agent economic behavior (be it rational or not), ultimately the model and simulation produced will be of great value and can save huge amount of money and time which would otherwise lose to mistakes that can be avoided with enough foresight from the model. 

Experience from many existing and past projects have enormously demonstrate that the failure to not defining a clear use case for the token, or not having a clear token burning and emission mechanism, or not allocating appropriate amount of token to key stakeholders, could easily jeopardize the hole token supply-demand dynamics, and causing misalignment between the token role and the projects vision.   

[upcoming next]
Currently we do not include the actual mechanism and relationship functions and operations that will illustrate the conceptual components above mathematically. In the next update for this section, that will be the priority. In particular we will delve deeper into the different parameter base, static parameter, time-dependent parameters, templates of vesting schedule, and various activity flow or action items for each agent. To do so a case specific illustration will be necessary, thus the behavior such as holding, staking, earning, mint, burn, and so on would be well defined. 

References:
[1] Oliveira,Luis; Zavolokina, Liudmila; Bauer, Ingrid; Schwabe,Gerhard (2018). To Token or not to Token: Tools for Understanding BlockchainTokens. In: International Conference of InformationSystems (ICIS 2018), San Francisco, USA, 12 December 2018 - 16 December 2018,ICIS.
[2] Toffler, Alvin. (1980). The third wave. New York :Morrow,
[3] Barreiro-Gomez, J., & Tembine, H. (2019). Blockchain Token Economics: A Mean-Field-Type Game
Perspective. IEEE Access, 7, 64603–64613. https://doi.org/10.1109/ACCESS.2019.2917517
[4] Cong, L. W., Li, Y., & Wang, N. (2021). Tokenomics: Dynamic Adoption and Valuation. The Review of
Financial Studies, 34(3), 1105–1115. https://doi.org/10.3386/w27222
[5] Cong, Lin and Xiao, Yizhou, Categories and Functions of
Crypto-Tokens (June 29, 2020).  http://dx.doi.org/10.2139/ssrn.3814499


Supplementary Info

Token Archetypes defined in Ref. [1]

![image](https://github.com/DreamBrookLabs/RnD/assets/60097047/3861c97b-d923-4501-8a93-e0927b556749)
