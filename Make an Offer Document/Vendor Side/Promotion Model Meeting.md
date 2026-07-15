# Promotion Object

Made up of 2 Sides; **Filter** and **Effect**:

- **Filter** properties determine the inventory items that the promo applies to within a user's inventory. Filter Props are similar to *Advanced Search* properties that create a filtered list of items.
- **Effect** properties determine what effects the promotion object imparts on the item. Some notes on changes to items; Items should have new properties called "MAO Enabled", "Promo Active" "MAO Percent" and "Promo Percent".
  - **Make-an-Offer:** A make an offer promotion is an on off switch for a new Item property. 
    - No Date Range 
    - If "MAO Enabled" is True the "MAO Percent" acts as a reserve percent that creates a range of values that represent "Auto-Accept" offers.
    - A **Make-an-offer** promotion in the **Promotion Center** will effectively act as an on-off switch that turns on **MAO Enabled** and pushes the **MAO Percent** to those items fitting the filter.
  - **Standard:**
    - Have a Date range associated with that defines the time period they will be in effect
    - **Promo Percent** will be pushed to items and **Promo Active** will be turned on for any items in the filter that don't have the filter turned on.
- We should keep track of the enabled date of the promos as a means of tracking priority for items that fall into multiple promo filters.

## Functions
- Promos point to items and items can point to promos that include them in their filters
- Active promos should catch new additions to the inventory or items that change and meet the filter criteria.
- Promos should be editable and can be reinstated after expiry if they have an associated term. Not sure if we want to strictly divide Promos and MAO, might be worth it.
- There will be a history list of promotions that applied to an item previously and they can be accessed from that item.
- Want to offer the ability for a "Final Sale" offer reserve that is a differential 

## Edge Cases
- Promo is turned on & Promotion items in the filter have existing promos that are already active.
- MAO is on on an item that lands in a promo's filters.
- An items props changes pulling it out of a filter for a currently active promo
- If a promo is turned into a MAO Filter after the fact
- What if some items have the switch on and others don't

## Promo Object Model Draft

![alt text](<Promotion Model.png>)
