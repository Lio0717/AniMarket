# AniMarket: Local Crop Price and Buyer Connector

## User Flow

*SDG Alignment:* SDG 2 — Zero Hunger

### 1. Purpose

This user flow illustrates how farmers can publish and manage crop listings and how buyers can discover local agricultural products, review crop and price information, and send purchase inquiries through AniMarket.

The application provides separate role-based experiences for farmers and buyers. The exact functions available to each role depend on the features included in the prototype and mobile implementation.

### 2. App Entry and Exit Flow

1. Open the AniMarket application.
2. View the Splash Screen, if included.
3. Proceed to the Welcome or Login screen.
4. Log in or select Create Account.
5. If creating an account, select the appropriate role: Farmer or Buyer.
6. Complete the required account information.
7. View the account creation confirmation, if included.
8. Access the appropriate Farmer Dashboard or Buyer Dashboard.
9. Select a feature based on the user's role.
10. Complete the intended task.
11. Return to the dashboard or navigate to another available feature.
12. Open Profile or Settings, if available.
13. Select Logout and confirm the action when finished.

### 3. Buyer Crop Discovery Flow

1. Open AniMarket and log in as a buyer.
2. View the Buyer Dashboard.
3. Select Browse Crops.
4. Browse the available crop listings.
5. Use search or category filters, if implemented.
6. Select a crop listing.
7. View Crop Details.
8. Review the crop name, image, asking price, unit, availability, location, and farmer information where provided.
9. Return to Browse Crops or proceed to another available action.

### 4. Crop Price Comparison Flow

1. Open the Buyer Dashboard.
2. Select Browse Crops or another entry point to the comparison feature.
3. Select Compare Crop Prices.
4. Review the available crop listings or price information.
5. Compare prices using clearly displayed units and relevant listing details.
6. Review the source and last-updated date for market reference prices, if these are provided.
7. Distinguish farmer-submitted asking prices from verified market reference prices.
8. Select a listing to view its details or return to browsing.

Price comparisons should only be made between values that are meaningfully comparable. If units, locations, dates, or sources differ, the interface should make those differences clear.

### 5. Purchase Inquiry Flow

1. Open Browse Crops.
2. Select a crop listing.
3. View Crop Details.
4. Select Send Purchase Inquiry.
5. Enter the required inquiry information, such as a message or requested quantity, if those fields are included.
6. Review the inquiry details.
7. Submit the inquiry in the prototype.
8. View the Inquiry Confirmation screen.
9. Open My Inquiries to review the sent inquiry, if inquiry tracking is implemented.

The inquiry process represents initial communication with a farmer. It should not be presented as a completed purchase, payment, or delivery booking unless those features are implemented.

### 6. Farmer Crop Listing Flow

1. Open AniMarket and log in as a farmer.
2. View the Farmer Dashboard.
3. Select Add Harvest Listing.
4. Enter the crop name and other required crop information.
5. Enter the asking price and unit.
6. Enter the available quantity and location, if required.
7. Add a crop photograph, if supported.
8. Review the listing information.
9. Submit or save the listing in the prototype.
10. View a confirmation or return to My Crop Listings.
11. Open My Crop Listings to review the published or saved listing.

### 7. Edit and Manage Crop Listing Flow

1. Open the Farmer Dashboard.
2. Select My Crop Listings.
3. Browse the farmer's existing listings.
4. Select a listing to view or edit.
5. Open Edit Listing.
6. Update the relevant crop information, such as price, quantity, description, or availability.
7. Review the changes.
8. Save the updated listing if the feature is implemented.
9. Return to My Crop Listings and review the updated information.

Any remove, deactivate, or availability-status actions should only be shown if they are included in the application.

### 8. Farmer Inquiry Management Flow

1. Open the Farmer Dashboard.
2. Select Farmer Inquiries.
3. Browse inquiries received from buyers.
4. Select an inquiry to view its details.
5. Review the buyer's message and requested quantity, if provided.
6. Choose an available response action, such as replying, accepting, or declining, if implemented.
7. View a confirmation or updated inquiry state, if included.
8. Return to Farmer Inquiries or the Farmer Dashboard.

The application should clearly distinguish an inquiry from a confirmed transaction. Any inquiry status labels should reflect the actual workflow supported by the application.

### 9. Profile, Settings, and Logout Flow

1. Open the Buyer or Farmer Dashboard.
2. Select Profile.
3. Review the account information.
4. Open Settings, if available.
5. Select Logout.
6. View the Logout Confirmation dialog or screen.
7. Confirm logout to return to the Login or Welcome screen.
8. Select Cancel to return to the previous screen if the user does not want to log out.

### 10. Navigation and Return Flow

1. From the appropriate dashboard, select a feature.
2. View the selected feature screen.
3. Review information or complete the required action.
4. Use the Back button or navigation menu to return to the previous screen or dashboard.
5. Select another feature if needed.
6. Repeat the process until the intended task is complete.

Buyer-only and farmer-only actions should remain separated according to the account role.

### 11. Error and Empty-State Flow

1. The user opens a crop listing, form, comparison screen, or inquiry feature.
2. The application checks whether the required information is available.
3. If listings or information are available, display the relevant content.
4. If no crop listings are available, display a clear empty-state message and an appropriate next action.
5. If a required form field is missing, highlight the incomplete field and explain what information is needed.
6. If a listing has incomplete or outdated information, avoid presenting it as confirmed current availability.
7. If an inquiry cannot be submitted, display an error message and allow the user to review or retry.
8. Provide a Back or Dashboard navigation option so the user can continue using the application.

### 12. Expected Outcome

The AniMarket user flow is designed to help farmers present crop availability and asking-price information and help buyers discover local agricultural products, review listing details, compare available price information, and contact farmers through purchase inquiries.

By organizing these tasks into clear farmer and buyer journeys, AniMarket aims to make local crop discovery and initial buyer–farmer communication more accessible in support of SDG 2 — Zero Hunger.

Crop availability, market reference prices, inquiry tracking, transaction handling, payment, and delivery functions depend on the data sources and features actually implemented.
