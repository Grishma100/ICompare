# ICompare
#### Price Comparison Portal using Semantics API

  ICompare portal allows users to make informed decision before placing order for a product. It lets users make quick decision by providing a price comparison the buyers can search for product without having to login. The result displayed contains product name, least price, price from various vendors, product image, brand, product short description and links to websites. This Portal allow users to access price comparison web application without login. The users can save the search result by adding it to a Wishlist. When user tries to add a product to Wishlist, they are redirected to login. Login is handled by Amazon Cognito integrated with Google and Facebook. Under Wishlist they can buy the product or remove from Wishlist. The user can search for desired product without logging in to the portal. The result will be shown according to search criteria. Also, the result will be sorted by lowest price available. 
  An admin portal is developed with the idea of providing a hassle-free login experience for administrators and developers to update api keys and access the SaaS apps within the organization. When the API keys expire, admin can update it via this portal. The CICD apps like Jenkins are accessible via this portal, all these apps are integrated with Okta for a SAML based SSO. Admin can configure and trigger builds to ICompare portal using Jenkins.
  
  - Demo
    <br> [ICompare Price Comparison Portal](https://youtu.be/41FNnWSZSik)
    <br> [Admin SSO with Okta Portal](https://youtu.be/Vz9yebzo_js)

  
  
  - System Architecture
  
  <img src="https://user-images.githubusercontent.com/1582196/41491686-9b6fe302-70af-11e8-99c1-26348d19a618.png" width="500" height="500">
  
  - Okta AWS Integration
  
   <img src="https://user-images.githubusercontent.com/1582196/41491707-c5cedb6c-70af-11e8-8cc8-40c2a4b749c8.png" width="500" height="300">
  
  - Okta Spring Boot Integration
  
  <img src="https://user-images.githubusercontent.com/1582196/41491721-db13b4ac-70af-11e8-8b9f-365ce15d150f.png" width="500" height="300">
  
  - Application Screenshots

<img src="https://user-images.githubusercontent.com/1582196/41491874-80b3f7c8-70b0-11e8-9164-73b515d73eda.png" width="300" height="300"> <img src="https://user-images.githubusercontent.com/1582196/41491881-8e08d79a-70b0-11e8-8955-7be303a84918.png" width="300" height="300"> <img src="https://user-images.githubusercontent.com/1582196/41491887-9a4bb810-70b0-11e8-9087-38e90f19620a.png" width="300" height="300"> <img src="https://user-images.githubusercontent.com/1582196/41491897-a56f2d62-70b0-11e8-95d6-33b4ccbca657.png" width="300" height="300"> <img src="https://user-images.githubusercontent.com/1582196/41491903-af0024a8-70b0-11e8-9878-8937b7f78841.png" width="300" height="300">
  
  
