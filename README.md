# Project Overview


##Problem with existing application
![Probelm with Existing System](https://github.com/Pushkar-Nikumb/Crowdfunding/assets/109033497/313ae6cb-49ff-4282-8b82-75304936b905)

 
This diagram shows the workflow of a traditional crowdfunding application. Campaigns In an ideal world, managers could create campaigns and raise funds from donors to make products and other things.Many of them make good products and backers/donors are happy with their products, but many campaigns are fraudulent and run away once the minimum donation requirements are met. This is a serious issue, because many people trust the campaign and donate to the campaign, eager to use their products.


##Our Solution
![Decentralized Solution](https://github.com/Pushkar-Nikumb/Crowdfunding/assets/109033497/954d4dac-29da-4dc7-bcc9-1e9323989b5d)

 
Our approach is to reduce fraud by introducing consensus voting into our campaigns. When a manager creates a campaign, he creates or deploys a new smart contract. This contract behaves differently than other smart contracts deployed by other managers in his campaigns.

The manager has to create a spending request and send money/ether to the vendor. He cannot send donations directly to vendors. Once a request is generated, a backer can vote on the request and approve the request so that the manager sends funds to a verified/authenticated vendor instead of his account.

When a person funds a campaign, the donated Ether is collected securely in the contract wallet, so managers have no control over the funds and cannot withdraw funds from the contract. This ensures security and completely eliminates fraud that can occur due to inappropriate behavior of the campaign manager , and the entire campaign is managed by  the Smart Contract.

Consensus Rule : If at least 50% of backers agree to the request, the request is approved and only managers can finalize the request, thus providing a reasonable amount to the vendor.

##Smart Contract
Our smart contract contains 2 contracts : 
1. CampaignFactory
2. Campaign
 ![Campaign Contract](https://github.com/Pushkar-Nikumb/Crowdfunding/assets/109033497/29a2fe1e-2981-4c63-858e-37d0a5868cc3)
 ![Campaign Contract](https://github.com/Pushkar-Nikumb/Crowdfunding/assets/109033497/d24e381a-88be-4c7e-835a-7743f8e95c2a)
 ![Campaign Contract](https://github.com/Pushkar-Nikumb/Crowdfunding/assets/109033497/09fa4eeb-e7d7-498c-8461-06f6b8417d85)
 ![campaign Factory](https://github.com/Pushkar-Nikumb/Crowdfunding/assets/109033497/fbc65aa3-04ba-4fb8-96c5-77f47980b48b)








