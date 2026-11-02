# AniMarket: Local Crop Price and Buyer Connector

# Week 1 — Research and Validation

**SDG Alignment:** SDG 2 — Zero Hunger

## 1. Research Purpose

The research aims to understand how small-scale farmers make their crops available for sale, how buyers find local agricultural products, and what challenges both groups experience when communicating about crop availability and prices.

It also seeks to explore how farmers currently share information about their harvests, how buyers compare prices and identify potential suppliers, and whether a mobile application could make local crop discovery and buyer–farmer communication more accessible.

## 2. Research Method

The team may use surveys and, where possible, short interviews with potential AniMarket users, including small-scale farmers, household or individual buyers, and business buyers such as restaurants, market vendors, and grocery operators.

The research may explore:

- How farmers currently advertise available crops and communicate asking prices.
- How buyers discover local farmers and source agricultural products.
- Difficulties related to finding buyers, locating suppliers, comparing prices, and confirming crop availability.
- Preferred ways of communicating and sending purchase inquiries.
- Interest in using a mobile application to connect local farmers and buyers.

Responses should be organized into common themes to identify user needs, expectations, and opportunities for improvement. Any findings reported in the final documentation must be based on actual survey or interview feedback.

## 3. Key Findings

Actual survey and interview responses should be analyzed and summarized here after data collection.

- **Farmer Selling Practices:** Describe how participating farmers currently advertise crops, communicate availability, and set asking prices.
- **Buyer Sourcing Practices:** Identify how buyers currently find local produce suppliers and decide where to purchase crops.
- **Price Information:** Summarize difficulties or preferences related to viewing, comparing, and understanding crop prices.
- **Availability and Harvest Information:** Identify the information buyers need before contacting a farmer, such as crop type, quantity, location, and harvest or availability date.
- **Communication and Purchase Inquiries:** Describe how farmers and buyers prefer to communicate about product details, quantity, pickup, and delivery arrangements.
- **Application Expectations:** Identify features respondents consider useful, such as crop listings, search and filtering, price comparison, farmer contact information, and purchase inquiries.
- **Suggested Improvements:** Document recommendations about usability, accessibility, trust, listing accuracy, and continued engagement.

Do not insert assumed percentages, quotations, or conclusions. Use only information collected from participants.

## 4. Impact on Project Design

Research results will guide the design and prioritization of AniMarket features according to the needs of intended users.

Potential design decisions include:

- Providing farmers with a straightforward way to create and manage crop listings.
- Allowing buyers to browse and search available local crops.
- Displaying crop details such as asking price, unit, quantity or availability, farmer, and location when provided.
- Providing a price comparison view that clearly distinguishes farmer asking prices from verified market reference prices.
- Enabling buyers to send purchase inquiries to farmers.
- Giving farmers a way to review and respond to inquiries if this function is included in the project scope.
- Showing relevant dates and sources for any market reference prices.
- Designing separate, role-appropriate experiences for farmers and buyers.

The team will use actual research findings to refine the user personas, user flow, wireframes, and feature priorities. Features will be prioritized according to user feedback, project requirements, feasibility, and relevance to SDG 2 — Zero Hunger.

## 5. Conclusion

Week 1 research and validation will establish an initial understanding of the challenges small-scale farmers and local buyers experience when sharing crop information, discovering agricultural products, and communicating about potential purchases.

The collected evidence will help the AniMarket team make informed design decisions and develop a mobile application prototype that responds to users' needs while supporting local agricultural access and market connections.

Research conclusions and final feature priorities should be updated after actual survey and interview responses have been reviewed.

---

# Week 2 — Component Design System & Clickable Interactive Figma Prototype

**SDG Alignment:** SDG 2 — Zero Hunger

## 6. Week 2 Objectives

Week 2 focuses on translating the initial AniMarket concepts and low-fidelity wireframes into a consistent and interactive Figma prototype.

The team will establish a reusable component design system, improve the visual consistency of the application, and connect the main screens through clickable interactions.

The design process will prioritize clear navigation, accessibility, readable crop and price information, and role-based experiences for farmers and buyers.

## 7. Design Implications and Priorities

The initial research objectives and preliminary user personas will guide the design of the AniMarket interface. Since research findings must be documented after data collection, these priorities should be refined as feedback becomes available.

### 7.1 Farmer Crop Listings

The farmer interface should make it straightforward to publish and maintain information about crops available for sale.

Planned design elements include:

- A crop listing form with fields for crop name, description, asking price, unit, available quantity, and location, as applicable.
- An option to add a crop photograph, if supported.
- Availability or listing status indicators.
- A My Crop Listings screen for reviewing published listings.
- Edit and remove or deactivate controls, if included in the application scope.
- Clear confirmation and validation messages.

Listing information should be accurate and updated by the farmer. The interface should not imply that a crop is available when its listing has not been confirmed or updated.

### 7.2 Buyer Crop Discovery

The buyer interface should help users find local agricultural products and understand the information available before contacting a farmer.

Planned design elements include:

- A Browse Crops screen with crop cards.
- Search and category filters, if supported.
- Crop photographs, crop names, asking prices, units, and available locations.
- A Crop Details screen with the available listing information and farmer details.
- Clear navigation between browsing, crop details, and purchase inquiry actions.

### 7.3 Crop Price Comparison

The price comparison interface should help buyers review available price information without confusing different types of prices.

Planned design elements include:

- A comparison view for selected crops or listings.
- Clear display of price, unit, location, and listing information.
- A visible distinction between farmer asking prices and market reference prices.
- Source and last-updated date for market reference prices, when such data is available.
- Consistent units to support meaningful comparisons.
- An explanatory note when prices are based on user-submitted listings or sample data.

Do not label farmer-submitted asking prices as official, verified, or prevailing market prices unless they have been independently verified by a reliable source.

### 7.4 Purchase Inquiry

The purchase inquiry interface should guide buyers through contacting a farmer about a crop listing.

Planned design elements include:

- A clear Send Purchase Inquiry action.
- Fields for inquiry message and requested quantity, if included.
- A review or confirmation step.
- A successful inquiry confirmation screen.
- A My Inquiries screen for viewing inquiry records and their status, if implemented.

The prototype should represent only the inquiry actions included in the actual design. It should not imply that payment, delivery booking, or order fulfillment is available unless those functions are part of the project.

### 7.5 Farmer Inquiry Management

The farmer interface should make buyer inquiries easy to review.

Planned design elements include:

- An inquiry list.
- Inquiry details, including the buyer's message and requested quantity when provided.
- Clear inquiry status labels, if supported.
- Response actions such as accepting, declining, or replying, if included in the project scope.

Any inquiry status workflow should reflect the functions actually designed and implemented.

## 8. Component Design System

The team will establish a consistent visual design system to support reusable UI components throughout AniMarket.

### 8.1 Color Palette

AniMarket will use a dark, nature-inspired visual identity that reflects agriculture while maintaining a modern marketplace appearance.

Recommended color tokens:

| Token | Hex Code | Intended Use |
|---|---|---|
| Primary Background | `#172B21` | Main screen background |
| Secondary Background | `#1C3025` | Secondary page areas |
| Card Surface | `#22382B` | Crop cards, dashboard cards, and panels |
| Elevated Surface | `#2A4232` | Dialogs, dropdowns, and elevated elements |
| Primary Green | `#78A85A` | Primary actions and selected controls |
| Dark Green | `#245C3A` | Strong green accents |
| Harvest Yellow | `#F2C14E` | Price highlights and important indicators |
| Primary Text | `#F1F5EF` | Headings and important text |
| Secondary Text | `#B8C7B8` | Descriptions and supporting information |
| Muted Text | `#91A494` | Metadata and less prominent text |
| Border | `#34483A` | Card outlines, dividers, and input borders |
| Error | `#F07878` | Validation errors and failed actions |

Color combinations should provide sufficient contrast and support readability. Prices may use harvest yellow for emphasis, while long paragraphs should use soft-white or secondary text colors.

### 8.2 Typography

A consistent typography system will be used across the application.

It will define:

- Heading styles for screen titles and major sections.
- Body text styles for crop descriptions and instructions.
- Supporting text styles for locations, units, dates, and listing metadata.
- Price styles that emphasize the amount while keeping the unit visible.
- Consistent text sizes, weights, and line spacing.

Typography should remain readable across mobile screens.

### 8.3 Reusable UI Components

Proposed reusable components include:

- **Navigation Components:** Allow users to move between the dashboard and major application features.
- **Crop Listing Cards:** Display crop images, names, asking prices, units, and availability information.
- **Price Display Components:** Present prices and units consistently.
- **Price Comparison Rows or Cards:** Allow buyers to review comparable listing information.
- **Availability Badges:** Indicate whether a listing is available or has another supported status.
- **Inquiry Status Badges:** Display inquiry statuses if status tracking is included.
- **Form Components:** Standardize text fields, dropdowns, quantity inputs, and action buttons.
- **Profile Components:** Display farmer or buyer account information.
- **Feedback Messages:** Communicate successful actions, missing information, and errors.

Reusable components will help maintain visual consistency and simplify future design updates.

### 8.4 Layout and Spacing

The application will use consistent spacing, alignment, padding, and corner radii across screens.

The layout should provide a clear visual hierarchy, make important actions easy to identify, and avoid overcrowding information on smaller mobile screens.

### 8.5 Component Consistency

Components with similar functions should maintain consistent appearances and behavior throughout the application.

For example, primary buttons should follow the same visual style, crop cards should use a consistent information hierarchy, and inquiry status badges should use consistent labels and colors wherever they appear.

## 9. Clickable Interactive Figma Prototype

The team will develop a clickable Figma prototype that demonstrates the intended navigation and interactions between the main AniMarket screens.

### 9.1 Authentication and Role Selection

The prototype should demonstrate:

- Opening the application and viewing the Welcome or Login screen.
- Navigating to Create Account.
- Selecting the Farmer or Buyer role.
- Completing the account creation screen.
- Viewing the account creation confirmation.
- Proceeding to the appropriate login or role-based dashboard, depending on the designed flow.
- Accessing Forgot Password and the reset-link confirmation screen, if included.

### 9.2 Buyer Navigation

The Buyer Dashboard should serve as the main entry point to buyer features.

Users should be able to navigate to:

- Browse Crops.
- Crop Details.
- Compare Crop Prices.
- Send Purchase Inquiry.
- Inquiry Confirmation.
- My Inquiries.
- Buyer Profile and Settings.

### 9.3 Buyer Crop Discovery and Inquiry Interaction

The prototype should demonstrate a typical buyer flow:

1. Open the Buyer Dashboard.
2. Select Browse Crops.
3. Browse or search available crop listings.
4. Select a crop to view its details.
5. Review available price, unit, location, and farmer information.
6. Open the price comparison view when available.
7. Select Send Purchase Inquiry.
8. Enter the requested information included in the design.
9. Proceed to the inquiry confirmation screen.
10. Open My Inquiries to review the inquiry, if included.

### 9.4 Farmer Listing Interaction

The prototype should demonstrate a typical farmer flow:

1. Open the Farmer Dashboard.
2. Select Add Harvest Listing.
3. Enter the crop information required by the form.
4. Add a crop image if supported.
5. Review or submit the listing in the prototype.
6. View the confirmation or return to My Crop Listings.
7. Open an existing listing.
8. Edit the listing information if the edit function is included.

### 9.5 Farmer Inquiry Interaction

The prototype should demonstrate how farmers access and review buyer inquiries.

The flow may include:

1. Open Farmer Dashboard.
2. Select Farmer Inquiries.
3. Open an inquiry.
4. Review the buyer's message and requested quantity, if provided.
5. Select an available response action.
6. View the corresponding confirmation or updated inquiry state, if designed.

### 9.6 Profile, Settings, and Logout

The prototype should provide a clear route from the buyer or farmer dashboard to the appropriate profile and settings screens.

Users should be able to open the Logout Confirmation screen and either confirm logout or cancel and return to the previous screen.

## 10. Validation and Refinement

The team will review the AniMarket design system and clickable prototype to identify opportunities for improvement.

The review will consider:

- Consistency of colors, typography, icons, buttons, and crop cards.
- Clarity of buyer and farmer navigation.
- Readability of crop names, prices, units, and availability information.
- Whether price comparisons distinguish asking prices from market reference prices.
- Ease of creating and editing crop listings.
- Ease of sending and reviewing purchase inquiries.
- Accessibility and usability on mobile screens.
- Correct connections between screens in the Figma prototype.

Where possible, the team will gather feedback from potential users to determine whether the design is understandable and whether the proposed features address their needs.

Feedback and identified design issues will guide further revisions. Claims about user validation must be based on actual testing or feedback collected.

## 11. Expected Week 2 Deliverables

Expected Week 2 deliverables include:

- A consistent AniMarket component design system.
- Defined color, typography, spacing, and layout standards.
- Reusable UI components for buyer and farmer features.
- Updated screen designs based on Week 1 wireframes.
- A clickable Figma prototype connecting the main buyer and farmer screens.
- Documented design refinements based on review and available user feedback.

Verify that each deliverable is completed before reporting it as finished.

## 12. Conclusion

Week 1 establishes the research objectives, preliminary user needs, and design direction for AniMarket. Week 2 builds on that foundation by translating the initial concepts and wireframes into a consistent component design system and clickable interactive Figma prototype.

Together, these stages aim to create a user-centered mobile application design that connects small-scale farmers with potential buyers, improves access to local crop listings and price information, and supports more accessible communication about agricultural products.

The AniMarket design should continue to evolve as the team collects actual user feedback, evaluates the prototype, and prepares for mobile MVP development.

The project remains aligned with UN Sustainable Development Goal 2 — Zero Hunger.
