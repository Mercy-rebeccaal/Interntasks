# **Task-05: Automation Testing for E-Commerce Demo Website**

### **Objective**

The objective of this task is to study and evaluate how an automated testing strategy can be planned for an e-commerce application using **Playwright**. The focus is on understanding the website flow, identifying automation possibilities, and handling real-time application constraints.

---

### **Tools & Framework**

* Playwright
* Node.js
* Demo E-commerce Website (sample online store)

**Note:**
No automation scripts were executed for this task. The task primarily involved analysis and planning based on the current behavior of the demo website.

---

### **Website Review & Manual Analysis**

The demo e-commerce website was reviewed manually to understand the user journey and identify testable components. The following points were observed:

* Homepage and product catalog load correctly
* Product images, titles, and prices are displayed properly
* Navigation links function as expected
* Products are available only for viewing purposes
* Checkout and payment features are disabled in the demo version

Due to these conditions, a full purchase workflow could not be validated.

---

### **Identified Limitations**

1. Products cannot be purchased due to disabled checkout functionality
2. Complete order placement flow is unavailable
3. Embedded map section fails to load, indicating a missing integration

These limitations are related to the demo setup and not actual defects.

---

### **Planned Automation Strategy (Using Playwright)**

If automation testing were implemented, the following steps would be automated:

1. Open the e-commerce demo website
2. Validate homepage and product listing visibility
3. Verify product details such as name, image, and price
4. Check availability and state of Add to Cart buttons
5. Navigate to the cart section
6. Confirm that checkout options are disabled
7. Validate page navigation and UI stability
8. Capture and report demo-related limitations

This approach ensures realistic automation without marking known limitations as failures.

---

### **Key Observations**

* Website layout is stable and user-friendly
* Navigation between pages works smoothly
* Product information is displayed consistently
* Demo restrictions prevent full checkout validation
* Third-party map integration is non-functional

---

### **Conclusion**

This task provided insight into how automation testing can be planned even when a demo website does not support a complete transaction flow. Instead of forcing test failures, application constraints were analyzed and documented.

Task-05 helped improve my understanding of real-world testing scenarios, demo application analysis, and how to design effective automation strategies using **Playwright** based on actual system behavior.
