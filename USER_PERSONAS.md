# AniMarket: Local Crop Price and Buyer Connector

## User Personas

**SDG Alignment:** SDG 2 — Zero Hunger

These are preliminary fictional personas created to guide the design and development of AniMarket. They represent potential users who may benefit from a mobile platform for listing locally available crops, discovering agricultural products, comparing listed prices, and communicating about potential purchases. These personas should be validated and updated through interviews or surveys with actual potential users.

## 1. Small-Scale Farmer

**Name:** Maria Santos
**Age:** 46  
**Occupation:** Small-Scale Farmer  
**Role:** Primary User — Farmer

### About

Ramon manages a small farm and sells seasonal crops to buyers in nearby communities. He relies on personal contacts, local markets, and word of mouth to let potential buyers know what produce is available. He wants a straightforward way to display his harvest information and receive inquiries from interested buyers.

### Goals

- Make nearby buyers aware of available crops.
- Share crop prices and available quantities.
- Reach potential buyers beyond his usual contacts.
- Update listings when crop availability changes.
- Receive clear purchase inquiries from interested buyers.

### Frustrations

- Difficulty reaching new buyers.
- Repeatedly answering questions about crop availability and prices.
- Limited visibility for the crops he has available.
- Changes in harvest quantity can make older information inaccurate.
- Difficulty coordinating purchase details with potential buyers.

### Needs

- A simple form for creating crop listings.
- Clear fields for crop name, price, unit, quantity, and location.
- A way to update or manage listings.
- A place to review buyer inquiries.
- An easy-to-understand mobile interface.

### How AniMarket Helps

AniMarket aims to give farmers a digital place to publish crop listings and connect with potential buyers. Farmers can present available crop information and receive purchase inquiries through the application, depending on the features implemented.

### Design Implications

The AniMarket farmer interface should make listing management and inquiry review straightforward.

- A Farmer Dashboard with clear actions.
- An Add Harvest Listing form with understandable field labels.
- My Crop Listings cards showing crop name, asking price, unit, and availability.
- Edit controls for updating listing information.
- A Farmer Inquiries section for reviewing buyer messages.
- Clear confirmation and validation feedback.

## 2. Local Produce Buyer

**Name:** Osten Verano  
**Age:** 29  
**Occupation:** Office Employee and Household Buyer  
**Role:** Primary User — Buyer

### About

Angela purchases fresh produce for her household and prefers to find crops from nearby sources when possible. She wants to browse available products, understand the listed prices, and contact farmers without having to search through multiple social media posts or personal contacts.

### Goals

- Discover crops available from local farmers.
- Review crop details before making a purchase decision.
- Compare listed prices using consistent units.
- Contact farmers to ask about availability and quantity.
- Find relevant crop listings in a convenient way.

### Frustrations

- Difficulty finding reliable information about which crops are currently available.
- Prices may be presented using different units.
- Crop listings may not include enough information.
- Contacting several sellers individually can take time.
- Older posts may no longer reflect current availability.

### Needs

- A searchable list of local crop listings.
- Clear crop photographs and descriptions.
- Prices with visible units.
- Farmer and location information.
- A simple purchase inquiry process.
- Clear indications when listing information may be outdated.

### How AniMarket Helps

AniMarket aims to help buyers discover local crop listings, review available price information, and send inquiries directly to farmers. This can make local produce discovery and initial buyer–farmer communication more convenient.

### Design Implications

The AniMarket buyer interface should make crop discovery and price information easy to understand.

- A Buyer Dashboard with access to Browse Crops.
- Crop cards with photographs, names, asking prices, units, and location details.
- A Crop Details screen with relevant listing information.
- A price comparison interface that uses consistent units where possible.
- Clear distinction between farmer asking prices and any verified market reference prices.
- A Send Purchase Inquiry action and confirmation screen.
- A My Inquiries section if inquiry tracking is implemented.

## 3. Business Produce Buyer

**Name:** Jose Cruz 
**Age:** 38  
**Occupation:** Restaurant Owner / Food Business Operator  
**Role:** Secondary User — Buyer

### About

Mark operates a small restaurant and regularly sources vegetables, fruits, and other agricultural products. He needs to identify potential local suppliers, understand available quantities and asking prices, and contact farmers to discuss purchase requirements.

### Goals

- Find farmers who list crops needed by the business.
- Review crop prices and available quantities.
- Identify potential suppliers in relevant locations.
- Send inquiries about bulk or recurring purchases.
- Communicate clearly about crop availability and purchase requirements.

### Frustrations

- Difficulty identifying local suppliers with the required crops.
- Uncertainty about quantities currently available.
- Time spent contacting multiple potential suppliers.
- Inconsistent price units or incomplete listing details.
- Difficulty following up on previous inquiries.

### Needs

- Crop listings with clear price and unit information.
- Available quantity information when provided by farmers.
- Farmer location and contact or inquiry options.
- A way to compare relevant listings.
- A record of sent inquiries, if supported.

### How AniMarket Helps

AniMarket aims to make it easier for business buyers to discover local crop suppliers and send inquiries about available products. The platform may support initial supplier discovery and communication; payment, delivery, and recurring-order functions should only be represented if they are included in the actual project scope.

### Design Implications

The AniMarket interface should support buyers who need to review several listings and communicate specific requirements.

- Search and category filters, if implemented.
- Crop details with quantity and unit information.
- A comparison view with clear price units and listing locations.
- Purchase inquiry fields that can capture a requested quantity or message.
- A My Inquiries view for reviewing previous inquiries, if included.

## 4. Persona-to-Feature Mapping

| User Persona | Priority Needs | Planned UI Components |
|---|---|---|
| Small-Scale Farmer | Publish and update crop information; review buyer inquiries | Farmer Dashboard, Add Harvest Listing form, My Crop Listings, Edit Listing, Farmer Inquiries |
| Local Produce Buyer | Discover crops, review details, compare listed prices, contact farmers | Buyer Dashboard, Browse Crops, Crop Details, Price Comparison, Purchase Inquiry |
| Business Produce Buyer | Find potential suppliers, review quantities and prices, send specific inquiries | Search and filters, Crop Details, Price Comparison, Purchase Inquiry, My Inquiries |

These mappings serve as design guidelines. The final selection of components depends on the actual application scope, research feedback, and features included in the Figma prototype and mobile implementation.

## 5. Design System and Prototype Priorities

### 5.1 Visual Consistency

- Maintain AniMarket's dark, nature-inspired visual identity.
- Use consistent typography, font sizes, spacing, and corner radii.
- Apply consistent icon styles and button designs.
- Use reusable color styles for backgrounds, surfaces, text, primary actions, prices, and status indicators.
- Keep text contrast and mobile readability in mind.

### 5.2 Reusable UI Components

- **Crop Listing Cards:** Display crop images, names, asking prices, units, and available listing information.
- **Price Display Components:** Present prices and units consistently.
- **Price Comparison Components:** Help buyers review comparable listing information.
- **Availability Badges:** Indicate listing availability where supported.
- **Inquiry Status Badges:** Display inquiry states if tracking is implemented.
- **Navigation Buttons:** Provide access to buyer and farmer features.
- **Listing Form Components:** Standardize crop information fields and image attachment controls.
- **Feedback Messages:** Communicate successful actions, validation issues, and errors.

### 5.3 Clickable Interactive Prototype

The Figma prototype should connect the main screens and demonstrate the intended user experience.

- Authentication and role selection to the appropriate dashboard.
- Buyer Dashboard to Browse Crops and Crop Details.
- Crop Details to Price Comparison or Purchase Inquiry.
- Purchase Inquiry to confirmation and My Inquiries, if included.
- Farmer Dashboard to Add Harvest Listing and My Crop Listings.
- My Crop Listings to Edit Listing.
- Farmer Dashboard to Farmer Inquiries and available response actions.
- Buyer and farmer profile screens to shared settings and logout.

## 6. Research and Validation

These personas are preliminary and fictional. They should be validated through surveys or interviews with potential farmers and buyers to understand actual selling practices, crop discovery habits, price information needs, communication preferences, and barriers to using a mobile marketplace.

Feedback should guide refinement of the personas and help the team prioritize features that are practical, accessible, and relevant to SDG 2 — Zero Hunger.

## 7. Expected Outcome

The AniMarket user personas provide a foundation for understanding potential farmers and buyers and translating their goals, frustrations, and needs into design decisions.

By connecting these personas to specific UI components and prototype interactions, the team can create a more consistent and user-centered application design. All personas and proposed features should be reviewed and refined as the project progresses.
