# ICompare
Price Comparison Portal using Semantics API

  ICompare portal allows users to make informed decision before placing order for a product. It lets users make quick decision by providing a price comparison the buyers can search for product without having to login. The result displayed contains product name, least price, price from various vendors, product image, brand, product short description and links to websites. This Portal allow users to access price comparison web application without login. The users can save the search result by adding it to a Wishlist. When user tries to add a product to Wishlist, they are redirected to login. Login is handled by Amazon Cognito integrated with Google and Facebook. Under Wishlist they can buy the product or remove from Wishlist. The user can search for desired product without logging in to the portal. The result will be shown according to search criteria. Also, the result will be sorted by lowest price available. 
  An admin portal is developed with the idea of providing a hassle-free login experience for administrators and developers to update api keys and access the SaaS apps within the organization. When the API keys expire, admin can update it via this portal. The CICD apps like Jenkins are accessible via this portal, all these apps are integrated with Okta for a SAML based SSO. Admin can configure and trigger builds to ICompare portal using Jenkins.
  
  - System Architecture
  - Okta AWS Integration
  
