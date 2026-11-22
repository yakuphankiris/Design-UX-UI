# Vatkon WMS — Product Location Finder

UX/UI Design — Final Project Presentation

Find the product. Confirm its location. Go to the right place.

[Open the clickable Figma prototype](https://www.figma.com/design/5vIbAk89dQ74VoOOKOOjuN/VatkonWMS?node-id=2-3049&t=YqOBJsXGXZpIL1Pe-1)

---

# The warehouse location problem

- **Primary user:** warehouse staff responsible for finding and picking products
- **Main task:** identify the correct product and its physical storage location
- **Problem hypothesis:** product information can be difficult to scan, while a location code can be hard to interpret without warehouse context
- **Scope:** product search and location lookup; live ERP synchronization is excluded

---

# Product identity and readable location details matter

- Similar product names can make the product code useful for identification.
- The AI-simulated interview described searching through ERP information to find a product’s location.
- The worker wanted product details and location information together.
- A location code should be understandable as a **floor, shelf, and row**.

---

# Two ways to find the right stock

## Search by product
Search by product name or code, select the matching item, and view its storage locations and quantities.

## Browse by location
Choose a **Floor → Shelf → Row**, then view the products stored at that location.

---

# The prototype makes the location explicit

**Product:** 0203250 — FBI 10-6 (203250)

| Location code | Warehouse location | Quantity |
|---|---|---:|
| F1-01-02 | Floor 01 / Shelf-01 / Row 02 | 480 PCS |
| F1-01-03 | Floor 01 / Shelf-01 / Row 03 | 384 PCS |
| F2-03-01 | Floor 02 / Shelf-03 / Row 01 | 288 PCS |
| F3-02-04 | Floor 03 / Shelf-02 / Row 04 | 96 PCS |

**Location-browse example:** Floor 01 → Shelf A-01 → Row 02  
**Selected row:** 3 products · 624 PCS

---

# Feedback led to clearer selection and filtering

**Peer feedback**
- The selected floor, shelf, and row were not easy to distinguish.
- Manufacturer and stock-difference filters should be easier to use.

**Changes in the revised prototype**
- Made the selected location state more visible.
- Added dropdown filters for manufacturer and stock difference.
- Refined the search and location-selection interactions.

---

# The success criterion is not yet verified

**Initial criterion:** At least 4 of 5 target users find the correct product and its location within 15 seconds, without help.

- AI simulations followed the connected prototype paths.
- Two peers commented on selection visibility and filtering.
- **No timed retest was recorded.**
- The initial success criterion remains **unverified**.

---

# Next, validate the revised flow with warehouse staff

- **Strongest current evidence:** peer comments on selection visibility and filtering
- **Main uncertainty:** whether warehouse staff can find and confirm a location quickly in real work conditions
- **Next step:** retest the revised prototype against the 15-second success criterion
- **Reflection:** make both the selected location and product identity easy to confirm

---

# Final prototype

[Open the Vatkon WMS clickable prototype in Figma](https://www.figma.com/design/fkQJ4Uy1QycVWkiombdcTG/Vatkon-WMS-%E2%80%94-Clickable-Prototype?node-id=1-2)

**Limitations:** AI-simulated feedback is not real interview or usability-test data. The two peer comments were not timed task tests. No measured retest is available, so the original success criterion is unverified. The prototype uses illustrative data and is not connected to live ERP synchronization.


