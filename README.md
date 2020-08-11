# Zoho Campaigns API: Subscribe Contact
Use the Zoho Campaigns API to subscribe a Contact to a mailing list. This will allow you to subscribe a Contact to a mailing list based on a Zoho CRM workflow rule and custom function. 

## Introduction
There are times you need explicit control over when a Contact is enrolled in a Campaigns List. This means that when a Contact meets specific criteria, you can subscribe them in a mailing list. Here are some marketing use cases:
* Post-purchase: A Contact or Lead makes a purchase on your eCommerce site, then they are enrolled in your post-purchase campaign.
* Upcoming renewals: An Account is set to renew in 90 days, so you subscribe them to your upcoming renewals campaign.
* Sales process: A CRM Blueprint for Leads triggers a custom function that will enroll them in a prospective customers list.

But each business has unique needs and constraints. If you need additional functionality, use this script as a blueprint for using the [Zoho Campaigns API](https://www.zoho.com/campaigns/help/developers/) in Deluge. 

One thing to note: the Zoho Campaigns API will send a subscription email to the contact. This can't be turned off for the API.

## Configuration
* You will need a Zoho CRM Connection to Zoho Campaigns. You can learn more about Connections [here](https://www.zoho.com/crm/developer/docs/connectors/set-up.html#Invoke_Connectors). You will need the following scopes: `ZohoCampaigns.contact.READ` and `ZohoCampaigns.contact.UPDATE`.

* This custom function uses the Contact ID as the only parameter. When configuring this, you will need to either add the Contact ID merge field, or modify the custom function.


## Contact Us
If you have any questions or issues, do not hesitate to reach out to us at https://theworkflowacademy.com/get-help/. We are always happy to help!
