# User Story: Quotation Creation Workflow

This user story describes the process a sales person follows to create a new quotation for a client using the pricing application.

---

### **User Story**

**As a** salesperson,
**I want to** use a step-by-step wizard to build a detailed quotation for shutters, motors, and controllers,
**So that** I can provide an accurate and professional price estimate to a client quickly and efficiently.

---

### **Acceptance Criteria (The "Happy Path")**

1.  **Given** I am on the "Create Quotation" page,
2.  **When** I enter the client's name, email, and phone number,
3.  **And** I select the client's location on the interactive map using google map free api to drop the pin and get the lat, lang location also add button for select current location on the map,
4.  **And** I proceed to the next step,
5.  **Then** the system saves the client's information.

6.  **And When** I am on the "Shutter Details" step,
7.  **And** I add one or more shutter openings, specifying the shutter type, width (cm), and height (cm) for each,
8.  **Then** the system automatically calculates and displays the Area (m²), Weight (kg), and Shutter Price for each opening.
9.  **And** the system displays a running total for all shutter prices.

10. **And When** I proceed to the "Motor Selection" step,
11. **And** the system displays each opening with its calculated weight and required motor power,
12. **And** I select an appropriate motor for each opening from a filtered list of suitable options,
13. **Then** the system displays the price for each selected motor and updates the grand total.

14. **And When** I proceed to the "Controller Selection" step,
15. **And** I select an optional controller for each opening that has a motor,
16. **Then** the system displays the price for each selected controller and updates the grand total.

17. **And When** I proceed to the "Summary" step,
18. **And** I review the final summary of all selected items and the final grand total,
19. **And** I add any optional notes for the quotation,
20. **And** I click the "generate with Gemini Ai" button,
21. **Then** the system send data through google gemini api and get the response of Quotation with best content massage and suggestions to the client end user ,
22. **And** open final Quotation as pdf file converted.

---

### **Data**
* for data select in all inputs just make dummy data as simulation for the system.
* it's static application for demo.


### ** Stack **
create project as single page app html,css,js and one page wizard steps form, use bootstrap latest version for ui building ( css + js )



