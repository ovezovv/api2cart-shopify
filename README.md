## Adding Shopify to API2CART:
API2Cart provides a single API to integrate with many shopping platforms, including industry leaders like Shopify, Magento, WooCommerce, Bigcommerce, Volusion, PrestaShop, OpenCart, and others.

### Shopify Custom App Setup

***

***PRE-REQUISITIES***  
1. Creating an account in Shopify Partners Platform  ***https://partners.shopify.com***
    *Note: Make sure you have completed email verification.*
    
***

***CREATING SHOPIFY STORE***

1. Enter ***Stores*** from left sidebar menu and click on the ***Add store*** button.
2. Choose ***Development store*** and fill in required fields with desired store info.
3. Click on the ***Save*** button after complete filling required fields.
4. Let's create some products and make an order for further testing our app

***
    
***LET'S CREATE SOME PRODUCTS AND MAKE AN ORDER FOR FURTHER TESTING OUR APP***


   1. ***Add product for testing***
      - If you have closed previous screen, so navigate to `https://{STORE_NAME}.myshopify.com/admin`.
      - Enter to the ***Products*** section from the sidebar menu and click on the ***Add product*** button.
      - Fill in mainly required fields with raw info (for example: Title, Description, Pricing, Weight).
      - After filling change ***Product status*** from ***Draft*** to ***Active*** in the right sidebar on top of the page. As it is shown below:
      ![Screen Shot 2022-03-28 at 19 23 06](https://user-images.githubusercontent.com/39469199/160438562-88f4661c-f399-4024-b53d-e38192888a65.png)
      - Click on Save button.

   2. ***Make an sample order for testing***
      - Enter to the ***Orders*** section from the sidebar menu and click on the ***Create order*** button.
      - Search for recently added product title and click on the ***Add*** button.
      - Please do ***Payment due later*** checkbox to checked and click on the **Create order** button.

***

***CREATING SHOPIFY CUSTOM APP***
1. Enter to the Shopify Partners ***https://partners.shopify.com***
2. Click on the **Create app** button and choose **Public app** type.
3. Fill in the **App name** and type `http://localhost` in **App URL** and **Allowed redirection URL(s)**.
4. After creating an app, copy **API key** and **API secret key** into custom app project's `.env`. It should be shown below image.

![Screen Shot 2022-03-28 at 20 20 49](https://user-images.githubusercontent.com/39469199/160438262-540c2ace-84e5-4859-aba9-81632616b359.png)

***

### API2CART Setup

***

***PRE-REQUISITIES***
1. Enter API2CART and create an account ***https://api2cart.com***.
2. Copy ***API key*** into custom app project's `.env`. It should be shown below.

![Screen Shot 2022-03-28 at 20 59 25](https://user-images.githubusercontent.com/39469199/160439223-307c120f-4ee6-438c-86f3-6b2d3125d72c.png)

    
