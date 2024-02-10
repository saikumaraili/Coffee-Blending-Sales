
# Coffee Company Decision Analysis
Date: `02/14/2022`   
Author: `Sai Kumar Aili`   
Degree: `M.Sc, Data Analytics Engineering`   
Course: `OR531: Operations Research - Decision Analysis`

![Coffee-Shop](https://github.com/sk-aili/Coffee-Blending-Sales/assets/99275093/8d2da093-500d-4303-8b3f-3b78ff116020) 
<br>
*Image Credits: Unsplash*

Contents
1. [TL;DR](#tl;dr)
2. [Project Description](#project-description)
3. [Important Questions](#important-questions)
4. [Graphical Analysis](#graphical-analysis)
5. [What you need: tools](#what-you-need:-tools)
6. [Approach](#approach)
7. [Conclusion](#conclusion)

## :basecamp: TL;DR 
In this case study, Hill-O-Beans Coffee Company wants to make their coffee taste super good for fancy hotels, restaurants, and supermarkets. They are trying to figure out the best way to mix four different types of coffee beans – Robusta, Javan Arabica, Liberica, and Brazilian Arabica – to make the most money each week. They have to think about how many beans they can get, how much they cost, and the minimum amount they have to make for each hotel, restaurant, and supermarket. I used special math and visuals to help them make smart choices and decide how to blend the coffee beans.

## :basecamp: Project Description
Hill-O-Beans Coffee Company mixes four different types of coffee beans to create three coffee brands for luxury hotels, restaurants, and supermarkets. The beans they use are called Robusta, Javan Arabica, Liberica, and Brazilian Arabica. The company needs to decide how much of each type of bean should go into making each brand of coffee.

There are limits to how many of each bean they can get, as shown in the blue table. It also tells us how much each type of bean costs per pound.

The company's coffee-making factory can only handle up to 100,000 pounds of beans each week. While there's a lot of people who want to buy the coffee, the marketing department says they have to make at least 10,000, 25,000, and 30,000 pounds for the hotel, restaurant, and supermarket brands, respectively.

In simple terms, Hill-O-Beans needs to figure out the best way to use their beans to make coffee that people want, while staying within their budget and production limits.

The company has contractual requirements for the minimum amount of caffeine in each of the brands, shown in the second (orange) table. The caffeine contents of each of the beans in the supply chain are shown in the blue table.   

<img width="526" alt="blue table" src="https://github.com/sk-aili/Coffee-Blending-Sales/assets/99275093/017afc61-9eb6-410d-a8e9-86cfce025897"><br>
<img width="526" alt="orange table" src="https://github.com/sk-aili/Coffee-Blending-Sales/assets/99275093/7c332edb-0dd7-45b0-87aa-8e31889a0f14">

## :basecamp: Important Questions

**Optimal Purchase**: How many pounds of each bean should be bought to maximize weekly profit?  
Answer: The maximum weekly profit = $67,625
<br>
<img width="848" alt="Solution" src="https://github.com/sk-aili/Coffee-Blending-Sales/assets/99275093/9446596c-ee4f-410b-9534-895bf38febc2">
<br>

**Plant Capacity Value**: What is the economic value of an additional pound's worth of plant capacity?  
Answer is $0.425. It is the shadow price of the total plant's capacity
<br>

**Liberica Pricing**: How much should Hill-O-Beans pay per pound for Liberica to raise total profit?  
Answer is $0.825. The base cost of liberica is $0.55 and the shadow price is $0.275. So, Hill-O-Beans be willing to pay $0.83 for an additional pound of Liberica in order to raise total profit.
<br>

**Target Profit**: Determine the Robusta bean price required for a specific profit target, e.g., $68,625.
<img width="743" alt="Screenshot 2024-02-07 at 7 59 17 PM" src="https://github.com/sk-aili/Coffee-Blending-Sales/assets/99275093/de1c9e97-b196-4b85-9bfc-40b422d267a7">


## :basecamp: Graphical Analysis  
**Graph 1**: Optimal Profit vs. Minimum Weekly Production of Restaurant Blend  
Visual representation of how optimal profit changes with the minimum weekly production of the restaurant blend.
<br>
<img width="773" alt="Graph" src="https://github.com/sk-aili/Coffee-Blending-Sales/assets/99275093/33444ee5-7fa8-47c0-ad35-1b6057cba10b">
<br>

**Graph 2**: Optimal Profit vs. Unit Cost of Robusta Beans  
Graph illustrating the variation in optimal profit concerning the unit cost of Robusta beans.
<br>
<img width="843" alt="Graph" src="https://github.com/sk-aili/Coffee-Blending-Sales/assets/99275093/44463b55-ffe6-4ba0-bb95-7a55a72e75d2">
<br>


## :basecamp: What you need: tools
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)    
![Analytical Solver](https://github.com/sk-aili/Coffee-Blending-Sales/assets/99275093/3fb5d7cd-7410-4de5-9326-9a8fe8aad149)


## :basecamp: Approach
**Input**<br>
<img width="393" alt="redesigned input" src="https://github.com/sk-aili/Coffee-Blending-Sales/assets/99275093/c63dee97-7a0b-4a17-adf4-a5721918aafc">
<br>
**Design**<br>
<img width="1239" alt="Approach in excel" src="https://github.com/sk-aili/Coffee-Blending-Sales/assets/99275093/73ff122c-4f0d-45fa-8b9f-df570d34f502">
<br>
**Calculations**<br>
<img width="609" alt="formulation" src="https://github.com/sk-aili/Coffee-Blending-Sales/assets/99275093/75e49d6e-6eab-4fdd-b3ac-b618dacab9ee">

## 🏁 Conclusion

This comprehensive analysis guides Hill-O-Beans in making informed decisions to maximize profit while meeting production requirements, incorporating mathematical optimization and graphical representation for actionable insights.


## Thank you!
