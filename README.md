# Create-Custom-Customer-Attribute-In-Magento-2
Code for creating custom customer attribute In Magento 2

Use the code on you custom extension.
Run **bin/magento setup:upgrade**

Now go to the admin **Customer->Edit Existing or Create New Customer**. You will see the additional field here.

<img width="1016" height="101" alt="image" src="https://github.com/user-attachments/assets/606089c8-7910-4fcc-8868-ea47d53b6e91" />

===========================================================================================================
**When you successfully create the customer attribute, go to PWA folder structure and find below files and add the below code**

**node_modules/@magento/venia-ui/lib/components/CreateAccount/createAccount.js**
<img width="700" height="470" alt="image" src="https://github.com/user-attachments/assets/c62b1bf1-5c70-464c-b6cc-7a91760fde09" />
            
**node_modules/@magento/peregrine/lib/talons/CreateAccount/useCreateAccount.js**
<img width="630" height="214" alt="image" src="https://github.com/user-attachments/assets/6ccd4d8a-9924-4f5a-be87-0d3b52c6cf48" />

**node_modules/@magento/peregrine/lib/talons/CreateAccount/createAccount.gql.js**
<img width="774" height="632" alt="image" src="https://github.com/user-attachments/assets/f24ad888-7a3c-4806-870b-417a86c2997e" />
