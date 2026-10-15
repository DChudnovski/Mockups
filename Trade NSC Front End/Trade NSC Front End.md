# Summary

We are looking to implement a trade account for the NSC front end for Designers/Retailers. This will be a means of giving direct access to the 47th St./ Instagem inventory directly to trade clients.

Some of the main features of this are as follows:

1. Monthly Subscription model ($25/month Flat Fee) [Question: Do we want to sell a tier with Memo service? Should all users have Memo access?]
2. Items \$2000 and below are handled directly B2B (47th St as Intermediary) ; Items above \$2000 have a similar dynamic markup structure to NXC with obscured vendor details with 47th acting as intermediary 
3. Trade orders would either be handled directly B2B or we would have Trade pricing built into MSX. That way we don't have to facilitate 
4. Document verification and handling facilitated directly through webforms.


## Systems Needed

- User to Vendor Chat [Pull from SaaS]
- Orders Interface (Including Cart, History, Comparison)(Likely handled directly through MSX Memo System) [Pull from Front End]
- Shipping/Tracking System [Pull Fdocsrom Front-End]
- Analytics [Pull from SaaS/MSX]
- Best Value [AI based on Analytics]
- Document Verification System [New System - Tool for filling out a blanket resale certificate (or upload)]


## Breakdown

### Signup

When a user goes to sign-up for an account they will request an invitation. We will confirm initial details and then we send a **form** requesting trade details.

This **form** will handle verifying their tax ID, verfying business details and generating documentation (Resale Certificates). We can implement a DocuSign flow, that will allow us to have directly signed forms handled through a signup page. 

We can also direct to this form for documenting for any Trade discount sale regardless of if it comes from B2B side or Retail side.

### Marketplace

Mirroring the B2B Marketplace, we will have a Trade Marketplace front end that is very similar. This Marketplace will show only on login so it will not be browseable unless they sign up. (We should have a homepage that has some sizzle images of examples of the inventory and maybe even a simplified browse)

Before document verification; a user with an invited account is welcome to browse and add items to their cart/favorites but they cannot checkout until verified.

Statuses for items will be the same as on the front end.

### Purchase Flow

Segmented Cart: 
- <$2000 Cart: Clicking checkout will send memo requests to all relevant vendors
- \>$2000 Cart: Clicking Checkout will work like standard NSC front end.

### Vendor Possibilities

**Lots; Parcels; Melee; Layouts:** We should start requesting that Vendors list these items, less expensive ones can be facilitated as listing directly by the Vendor (<\$2000). >$2000 should be vetted further but shouldn't be as detailed.
**Direct Contact:** We can offer direct access to trade customers outside of just suppliers. 

## Potential Extensions [Ideas]

- Trusted Retailers - We could offer trusted retailers the ability to use our systems for their showrooms; effectively buying our flow for custom jewelry creation [Higher Tier Subscription]
- Marketplace Syndication - Hosting sellable items on retailer front ends, similar to a VDB. 
  - Related Function: Purchasable Shopify integration, certain accounts allow for syndicated search through Shopify; Retailers can use our search on their websites through an extended subscription
- STL upsell - We can offer to sell the STL file during a purchase for an upcharge potentially.

## Questions

### Branding Questions

1. Do we want this to act as a seperate website with no direct affiliation to NXC? (Use 47th St Name? Or Market Org? )
2. Do we want to collapse B2B Marketplace into this? Do we want to directly distinguish between this and the B2B Marketplace (i.e. Tell vendors that B2B marketplace is to Vendors in Network and B2Trade is for people we don't take items from)?

### Payment Questions 

1. Are we going to facilitate a credit system for account holders on the platform?
2. Are we going to offer a Memo system directly through the front-end?

### Platform Questions

1. Are we going to give access to a dedicated Sales apperatus? Will Trade customers who buy access get access to Sales support as far as finding items, seeing items in person?
2. Mediation: If there are issues between a Vendor and a Trade side customer what is our level of involvement in those direct B2B sales (<\$2000 items)?
3. Moderation: Are we going to have a review of what items go up on the B2B front-end; AI Review?
4. Do we want to honor a return policy? Same 14-day policy as NXC?