# Make An Offer / Customer Conversion Pushes Outline

## Summary of Needs
- Currently NXC sites have targeted ads through Google; Should be looking into more targeted pushes to customers through an Email service that prompts engagement (Need to strike a balance between pushy and indifferent)
- We want to have customers engaged with the system in the process of purchasing their stone, while also limiting the need for salespeople to engage in discount discussions. 
    - Want to increase the number of customers who actively sign up for accounts with Market Org. so that we can email offers and facilitate negotiations directly through the website
    - Hope is that this will increase conversion and also lock-in
- For the Vendor side we want to be able to give them more exposure to the end customer and influence thier ability to sell directly. Also we want to make sure that the features are optional and that Vendors that are interested can use it easily while Vendors while not pressuring others who may be more skeptical
- <u>*Intentions overall:*</u> Increased engagement, Increased Customer Conversion, Incresed Customer Lock-In and reduced returns, Inventory Churn, Decreased Useless Back-and-Forth, Larger tool set for facilitating discounts.
___

## Customer Side Considerations

- **Utilizing Data to Create Pushes with MAO:** Ensure that we are monitoring Customer activity well and that we can keep track of different levels of int erest and who may be amenable to additional pursuit. Example; Customer who looks at an item a few times or holds an item in their cart for a period and is moving slow on placing an order.
- **Incentivising Sign Up:** Be sure we push a bunch of features that make it desirable for more prospective customers to sign up directly to be served items.
- **Create Consumer Profile:** Curious about how we develop a profile for a customer and how we can look into tooling that Customers with accounts can use.
  - Maybe create a center for customers to engage and select their interests so that we can send them personalized emails and offers.
    - With that in mind we can send them email reminders to mention that they should develop a profile for us to serve them items from the inventory and ideas from our MTOs as well as items that are candidates for Make-an-Offer.

### Customer Concerns

- **Balancing Pushy and Apathetic:** If we send out too many emails to customers we run the risk of them considering us spammy and we can gain a negative reputation. Conversely, we could lose out on potential conversions if our logic doesn't have the capacity to capitalize.
- **Ensuring Proper Targeting:** If we are not pushing the correct items to customers and balancing the interest we are not going to see the conversions we need from our efforts. Ensure that we have the algorithm tuned to deliver items that will pique interest in customers.
- **Exploiting Negotiations:** Nefarious actors could try to exploit the system and lead to frustration. We need to make sure that the system is able to identify issues quickly and flag them.
- **Potential Lackluster Interest:** Need to make the pushes accesible and engaging, whether it be email headlines or email wording to make the offer appealing and make sure the isn't lackluster interest in pulling prosepective customers into negotiation.
- **Lead Cooling:** Leads can get started `and we could have lapses where negotiation stops on Customer side so we have to be monitoring and ensuring auto follow-up in those lapses
___

## NXC Considerations

- **Push Center:** In MSX there should be a dashboard that allows us to tweak the logic of the pushes.
  - Editable Parameters for pushes should be as follows:
    - Age: Should be able to select multiple aging ranges and set rules per age ranging (Max Discount set per Age range)
    - Salability: Should be able to edit max discount according to how likely something is to sell and what factors go into it:
      - Rarity
      - Desirability
    - Time Before Push: Can adjust how aggressively we are pushing items that are in carts and have MAOs.
    - Similar Item: Based on certain item types we can have Pushes that push similar Make an Offer listings to customers based on items in their carts/favorites etc.

- **MAO Advanced Search:** Addition to Advanced Search in MSX that allows us to filter by items that have Make-An-Offer enabled.

- **Offer Records:** Under *Tools>Logs* we can access the list of all offers that have come through on MAO items.
    - Should be able to filter by the following: 
      - Vendor
      - Item Type
      - Stone Type
      - Percent
      - Successful?
    - Question: Do we want to have the full Advanced Search functionality to the MAO Search
  
- **Promo Search:** Each Promo that a Vendor creates should be browsable through MSX:
    - Parameters:
      - Vendor
      - Item Type
      - Active?
      - Timeframe
    - Fields:
      - ID
      - Vendor
      - Items on Promo

- **Customer Account Insights:** Build out a set of tools that allows us not just to see the activity on individual pieces but also the amount of time on average people are spending on our site, creating profiles for customer based on the insights of their activity.
- **Conversion Analytics:** Keep track of how many conversions we get from links that we provide for MAO items and have a center that allows us to view and judge the efficacy of strategy
- **Salesperson Relief:** Based on the ability for us to automate pushes we can even add a tool for a salesperson to push a negotiation email a prospective customer
- **Agentic Integrations:** Using AI Agents to scrub our Inventory listings for not just enabled MAOs but also for items that represent good matches with items that customers have in their carts/favorites that are MAOs.
- **Creating Jewelry with MAO Stones:** We have to think about how to treat stones that have been negotiated with MAO and how that jewelry works. What is the return policy for items that have stones that were purchased with Final Sale on MAOs, are we willing to accept returns on jewelry made with those items?

### NXC Concerns

- **Finding Target Recipe:** Requires tweaking and analysis to see how the features and strategy are effecting conversion rates. We also need to define metrics of success and see about attaining them by tuning the strategy of items we're pushing.
- **Ensuring Less Salesperson Work:** Need to be sure that the system is robust enough to not pour over heavily into the realm of customer service needs. As it is our salespeople are fully loaded with responsibilities and we do not want to add more to their load.
- **Managing Large Amounts of Data:** There is going to be alot of data that goes into tool implementation as well as profile generation for customers who may be amenable to pushes. 
- **Identifying Crucial Variables:** Need to be sure we understand what it is that leads to conversions through this method. Additionally conversations need to be had with salespeople to understand how we are currently converting larger sales to ensure that we are keeping those methods open and not cutting ourselves off from those with MAO conversions.
- **Processing Difficulties:** Need to be sure there are no headaches with processing payments or issues with fulfillment as well as keeping good track of terms and policies with regards to items that are purchased through negotiations
___

## Vendor Considerations

- **Functionality in Notification Center:** Recommendations to put stones up for Make an Offer based on their age. Make it easy to turn off but also make it give insights to the Vendor based on the analytics of the items.
- **Promotion Center:** Framed in the light of setting items up to be easier to sell on the B2C platform. It will allow a given vendor to set discounts on items based on factors similar to how our "Push" Center will work in MSX. Additionally will signal MSX directly and will populate discount amounts on items for our "Push" Center.
- **Recommended Discount:** We can create logic that feeds vendors recommendations for discounts given specific data about both their items as well as other offerings on the market.
- **Tie-ins with Analytics Features:** Analytics are on the docket for features that are going to be in development. When those features are implemented and they are available for all Vendors on 47th/Instagem.
- **Ease of Action:** Make it easy for the Vendors to access and create rules based on their inventory and ideas we can give to them based on our inventory analytics.

***Idea: Add a "Time in Inventory" field seperate from "Aging" that can give insights about items that may not have been up on 47th St for a long time but may have been sitting in their inventory for a while***

### Vendor Concerns

- **Indifference in Features:** Vendors are likely to ignore the features if they aren't prompted to engage. It's absolutely crucial to make sure that messaging, support and testing are on-point.
- **Educating Vendors:** Vendors may not understand initially and make mistakes when it comes to using the functionality we build into 47th Street and thereby get angry. We need to issue a large release about the features and ensure that they understand the utility. Daniel to be available given questions and strategy discussions.
- **Bitterness about Pricing:** There is a risk that some Vendors might see this as an attempt to muscle them into altering their pricing. Need to be clear that this is an attempt to increase utility of the platform to them and increase churn in their inventory. Additionally it gives them more direct exposure to the retail customer.
- **Logistics of Notification:** Need to make sure contact information is up to date and that Notifications are getting to Vendors so they are not blindsided by information about their stones. This ties into the Notification Center but is absolutely critical when it comes to making sure the Vendors feel that we are being transparent about our operations.