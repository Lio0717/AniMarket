# AniMarket: Local Crop Price and Buyer Connector

**Project Documentation: Week 1 and Week 2**

**SDG Alignment:** Sustainable Development Goal 2 — Zero Hunger

**Figma Prototype:** [AniMarket — Local Crop Price and Buyer Connector](https://www.figma.com/design/WAwp0pWeFDDAoaughxp6bJ/AniMarket-%E2%80%94-Local-Crop-Price-and-Buyer-Connector?node-id=51-1353&t=HvNC1SP1lblYl2O6-1)

---

# WEEK 1 — Research and Validation

## 1. Project Overview

AniMarket is a mobile application concept designed to connect small-scale farmers with potential buyers through a more accessible platform for discovering local agricultural products. The project focuses on helping farmers present their available crops, provide asking prices, and communicate with interested buyers.

For buyers, AniMarket provides a way to browse local crop listings, view product information, compare available prices, and send purchase inquiries directly to farmers.

The project supports **UN Sustainable Development Goal 2: Zero Hunger**, particularly its emphasis on supporting food systems and improving opportunities for small-scale food producers.

## 2. Research Purpose

The purpose of the initial research and validation stage is to understand the challenges experienced by small-scale farmers and potential buyers when selling, finding, and purchasing local agricultural products.

The research aims to explore how farmers currently advertise their crops, communicate their prices, and find potential customers. It also seeks to understand how buyers discover local produce, identify suppliers, compare available prices, and confirm crop availability.

The information gathered will help the team determine whether AniMarket's proposed features address relevant user needs and identify areas that should be prioritized during the design and development process.

## 3. Target Users

AniMarket primarily focuses on two groups of users:

### 3.1 Small-Scale Farmers

Farmers are the primary providers of agricultural products on the platform. They need a convenient way to publish crop listings, display asking prices, update availability, and receive inquiries from interested buyers.

### 3.2 Buyers

Buyers include individuals, households, and business operators who purchase agricultural products. They need an accessible way to discover available crops, review product information, compare listed prices, and communicate with farmers.

## 4. Research Method and Validation Approach

The team may use surveys and short interviews with potential users, particularly small-scale farmers and individuals or businesses that regularly purchase agricultural products.

The research will focus on the following areas:

- **Current Selling Practices:** How farmers advertise their harvests, establish asking prices, and communicate with potential buyers.
- **Buyer Sourcing Practices:** How buyers find local agricultural products and identify reliable suppliers.
- **Price Information:** How farmers and buyers communicate about prices, quantities, and units of measurement.
- **Crop Availability:** What information buyers need before contacting a farmer, including crop type, quantity, location, and availability.
- **Communication Challenges:** Difficulties experienced when coordinating purchase inquiries between farmers and buyers.
- **Technology Preferences:** Whether potential users are comfortable using a mobile application to discover crops and communicate about agricultural products.
- **Feature Expectations:** Which application features users consider useful and necessary.

Responses should be organized into common themes to identify recurring concerns, user expectations, and possible improvements.

**Research integrity:** Actual findings, participant quotations, percentages, and conclusions must only be included after the team has collected and analyzed real responses.

## 5. Initial Project Problem and Proposed Solution

Small-scale farmers and potential buyers may experience difficulties connecting with one another because information about available crops, asking prices, and product availability can be scattered across different communication channels.

Farmers may need more accessible ways to present their available harvests and reach interested buyers. Meanwhile, buyers may spend additional time searching for local suppliers and gathering information before making purchase inquiries.

AniMarket proposes a mobile platform where farmers can publish crop listings and buyers can browse available agricultural products, review listing information, compare available prices, and send purchase inquiries.

The application aims to make local crop information easier to access and improve communication opportunities between farmers and buyers.

## 6. Research Findings

This section should be completed using actual survey and interview results.

The following themes will guide the presentation of findings:

- **Farmer Experiences:** Common challenges in advertising crops, finding buyers, and updating listing information.
- **Buyer Experiences:** Difficulties in discovering local produce and identifying potential suppliers.
- **Price-Related Concerns:** Challenges in understanding and comparing asking prices and units.
- **Availability Information:** The crop details buyers consider important before contacting a farmer.
- **Communication Preferences:** Preferred ways of sending inquiries and discussing crop purchases.
- **Technology Acceptance:** Willingness and ability to use a mobile application for crop discovery and communication.
- **Feature Recommendations:** Suggestions from participants regarding usability, accessibility, and application functions.

The findings should be summarized objectively and used to support decisions about the application's design and features.

## 7. Impact of Research on Project Design

The research objectives and identified user needs provide the foundation for AniMarket's initial design direction.

The proposed application features address the two main user groups:

**For Farmers:**
- Create and publish crop listings.
- Provide crop descriptions, asking prices, units, and availability information.
- Add crop photographs when supported.
- View and manage published listings.
- Receive and review buyer inquiries.

**For Buyers:**
- Browse available local agricultural products.
- Search or filter crop listings when supported.
- View crop details and farmer-provided information.
- Compare available asking prices.
- Send purchase inquiries to farmers.
- Review submitted inquiries when supported.

The design separates farmer and buyer experiences to make the available functions relevant to each user's role.

---

# WEEK 2 — Component Design System and Interactive Figma Prototype

## 8. Week 2 Objectives

Week 2 focuses on transforming AniMarket's initial concepts and wireframes into a more organized, visually consistent, and interactive mobile application prototype.

The team worked on establishing a recognizable visual identity, maintaining consistent styling, organizing reusable components, and improving navigation across the farmer and buyer interfaces.

The Figma prototype serves as a visual representation of the proposed application and demonstrates how users may navigate its main features.

## 9. AniMarket Figma Prototype

**Prototype Link:** [Open AniMarket — Local Crop Price and Buyer Connector in Figma](https://www.figma.com/design/WAwp0pWeFDDAoaughxp6bJ/AniMarket-%E2%80%94-Local-Crop-Price-and-Buyer-Connector?node-id=51-1353&t=HvNC1SP1lblYl2O6-1)

The Figma design presents AniMarket's proposed interface and visual direction. It is intended to demonstrate the application's layout, user navigation, and core features for farmers and buyers.

The prototype is organized around the following design priorities:

- A consistent visual identity throughout the application.
- Clear navigation between the main screens.
- Separate user experiences for farmers and buyers.
- Organized presentation of crop information and asking prices.
- Reusable components for consistent interface elements.
- Accessible layouts that are appropriate for mobile devices.

## 10. Visual Design System

### 10.1 Color Palette

AniMarket uses a dark, nature-inspired color palette that reflects agriculture while providing a modern marketplace appearance.

| Color Token | Hex Code | Intended Use |
|---|---|---|
| Primary Background | `#172B21` | Main screen background |
| Secondary Background | `#1C3025` | Secondary screen areas |
| Card Surface | `#22382B` | Crop cards and content panels |
| Elevated Surface | `#2A4232` | Dialogs and elevated elements |
| Primary Green | `#78A85A` | Primary actions and selected controls |
| Dark Green | `#245C3A` | Strong green accents |
| Harvest Yellow | `#F2C14E` | Price highlights and important indicators |
| Primary Text | `#F1F5EF` | Headings and important information |
| Secondary Text | `#B8C7B8` | Descriptions and supporting text |
| Muted Text | `#91A494` | Metadata and less prominent information |
| Border | `#34483A` | Card outlines and dividers |
| Error | `#F07878` | Error messages and validation feedback |

The dark green shades establish the application's agricultural identity, while harvest yellow highlights important information such as crop prices. Soft white and secondary text colors maintain readability against the dark backgrounds.

### 10.2 Typography

A consistent typography system is applied throughout the interface to establish a clear visual hierarchy.

The typography should distinguish:

- Screen titles and section headings.
- Crop names and descriptions.
- Asking prices and measurement units.
- Supporting information such as location and availability.
- Button labels, instructions, and feedback messages.

Consistent text sizing, weight, and spacing help users understand information more easily.

### 10.3 Reusable Components

Reusable components help maintain a uniform appearance and make the prototype easier to organize and update.

The design system includes or plans for reusable interface elements such as:

- Navigation elements.
- Buttons and action controls.
- Input fields and form elements.
- Crop listing cards.
- Price displays.
- Availability indicators.
- Profile elements.
- Inquiry information and status indicators.
- Feedback and confirmation messages.

Components with similar functions should maintain consistent styling and behavior across the application.

## 11. Main Application Features and Design Priorities

### 11.1 Farmer Interface

The farmer interface is designed to help users manage information about their available agricultural products.

Its main design priorities include:

- Providing a clear dashboard.
- Making crop listing creation straightforward.
- Displaying crop names, descriptions, asking prices, and availability.
- Allowing farmers to review their published listings.
- Providing access to listing management functions.
- Presenting buyer inquiries in an organized manner.

### 11.2 Buyer Interface

The buyer interface focuses on making local agricultural products easier to discover and review.

Its main design priorities include:

- Providing a buyer dashboard.
- Organizing available crop listings.
- Presenting crop details in an understandable format.
- Making asking prices and measurement units visible.
- Providing access to price comparison.
- Making purchase inquiry actions easy to identify.

### 11.3 Crop Price Comparison

The price comparison feature is intended to help buyers review available price information for agricultural products.

The interface should clearly identify farmer-provided asking prices and distinguish them from any external market reference prices.

If market reference prices are included, their sources and update dates should be identified. Farmer-submitted listing prices should not be presented as verified market prices.

### 11.4 Purchase Inquiries

The purchase inquiry feature provides a communication channel between interested buyers and farmers.

The design should make it easy for buyers to express interest in a crop listing and provide relevant inquiry information.

The prototype should only represent functions included in the actual project scope. Payment processing, delivery booking, and completed transactions should not be implied unless they are implemented as project features.

## 12. Navigation and User Interaction

The prototype is intended to demonstrate the main user journeys of AniMarket.

### 12.1 Account and Authentication Flow

The authentication experience may include:

1. Welcome or Login screen.
2. Create Account screen.
3. Farmer or Buyer role selection.
4. Account creation confirmation.
5. Role-appropriate dashboard.
6. Forgot Password and reset confirmation, if included.

### 12.2 Buyer Journey

The buyer journey focuses on discovering crops and contacting farmers.

1. Open the Buyer Dashboard.
2. Navigate to Browse Crops.
3. Browse or search available crop listings.
4. Select a crop to view its details.
5. Review the available price, unit, location, and farmer information.
6. Open the price comparison feature when available.
7. Send a purchase inquiry.
8. View the inquiry confirmation.
9. Review submitted inquiries when supported.
10. Access the buyer profile and settings.

### 12.3 Farmer Journey

The farmer journey focuses on publishing crop listings and reviewing buyer inquiries.

1. Open the Farmer Dashboard.
2. Navigate to Add Harvest Listing.
3. Enter the required crop information.
4. Add a crop photograph when supported.
5. Submit or preview the listing.
6. Review published listings.
7. Edit listing information when needed.
8. Open Farmer Inquiries.
9. Review buyer messages and available inquiry details.
10. Access the farmer profile and settings.

### 12.4 Profile and Logout

Both user roles should have access to their respective profile and settings screens. A logout confirmation interaction should allow users to confirm or cancel the action.

The final navigation documentation should reflect the actual screens and connections available in the Figma prototype.

## 13. Prototype Review and Refinement

The AniMarket Figma prototype should be reviewed to assess the consistency, usability, and clarity of the interface.

The review focuses on:

- Consistency of colors, typography, and reusable components.
- Clear navigation between farmer and buyer screens.
- Readability of crop names, asking prices, and units.
- Organization of crop listing information.
- Ease of understanding the crop discovery process.
- Clarity of the purchase inquiry interaction.
- Consistency of buttons, cards, and other interface elements.
- Correct prototype connections between screens.
- Suitability of the layouts for mobile devices.

Reusable components and consistent styling improve usability by creating a uniform appearance across the application. They also make navigation easier and help users become familiar with recurring interface elements.

Further refinements should be based on prototype review and, where available, feedback from potential users.

## 14. Week 1 and Week 2 Deliverables

The project documentation and design activities cover the following deliverables:

**Week 1 — Research and Validation**
- Project overview and problem identification.
- Alignment with SDG 2 — Zero Hunger.
- Identification of target users.
- Research purpose and validation approach.
- Initial feature planning based on user needs.
- Preliminary design direction.

**Week 2 — Design System and Figma Prototype**
- AniMarket visual design direction.
- Defined color palette and typography standards.
- Reusable UI component planning.
- Farmer and buyer interface design.
- Main application navigation and user journeys.
- Figma prototype for presenting the proposed application.

The team should distinguish completed design outputs from planned or unvalidated activities when reporting project progress.

## 15. Conclusion

Week 1 established the initial direction of AniMarket by identifying the project's target users, defining the problem it aims to address, and outlining the research needed to understand the experiences of small-scale farmers and potential buyers.

Building on this foundation, Week 2 focused on translating the initial concepts into a more organized and visually consistent Figma prototype. The design emphasizes a dark, nature-inspired visual identity, reusable components, and clearer navigation across the farmer and buyer interfaces.

Through its crop listing, crop discovery, price information, and purchase inquiry features, AniMarket aims to provide a more accessible way for small-scale farmers and potential buyers to connect.

The project supports SDG 2 — Zero Hunger by focusing on opportunities for small-scale food producers and improving access to local agricultural product information.

Further improvements should be guided by actual user feedback, prototype evaluation, and the project's development requirements.
