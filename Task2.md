***Task-02: Compatibility Testing for Basic Web Page***

**Website Tested**
E-commerce Demo Website (DemoShop)

**Test Environment**

**Browsers Tested**
Google Chrome (Desktop)

**Devices Tested**
Desktop
Mobile (Chrome DevTools – Responsive View)

**Overview**
Compatibility testing was conducted to ensure the website displays and functions correctly across different screen sizes. The testing focused on layout alignment, navigation menus, search functionality, footer links, and basic user actions such as browsing products and adding items to the cart.

---

## **Test Findings**

### **TC_001:**

Verify website behavior on Chrome Desktop

**Expected Result:**
Website should load correctly with smooth scrolling

**Actual Result:**
Website loads successfully with smooth scrolling and proper alignment

**Status:**
**“Pass”**

---

### **TC_002:**

Verify header navigation – Men menu

**Expected Result:**
Clicking the Men menu should open the men’s product listing page

**Actual Result:**
Men menu opens the product listing page correctly

**Status:**
**“Pass”**

---

### **TC_003:**

Verify header navigation – Women menu

**Expected Result:**
Women menu should redirect to the women’s product page

**Actual Result:**
Women menu redirects to an incorrect page

**Status:**
**“Fail”**

---

### **TC_004:**

Verify header search bar functionality

**Expected Result:**
Search bar should return relevant product results

**Actual Result:**
Search bar is visible but returns no results

**Status:**
**“Fail”**

---

### **TC_005:**

Verify Add to Cart and checkout functionality

**Expected Result:**
Products should be added to the cart and checkout should complete successfully

**Actual Result:**
Add to Cart and checkout features work as expected

**Status:**
**“Pass”**

---

### **TC_006:**

Verify footer navigation links

**Expected Result:**
Footer links such as Home, About Us, Products, Contact, and Help should be clickable

**Actual Result:**
Some footer links respond while others do not open

**Status:**
**“Fail”**

---

### **TC_007:**

Verify responsiveness on mobile view

**Expected Result:**
Website should adjust properly to mobile screen size without layout issues

**Actual Result:**
Website adapts well to mobile view with no overlap or horizontal scrolling

**Status:**
**“Pass”**

---

## **Issues Identified**

1. Women menu redirects to an incorrect page
2. Header search bar does not return search results
3. Some footer links are not functional

---

## **Recommendations**

* Fix incorrect routing for the Women menu
* Implement proper backend support for search functionality
* Ensure all footer links are clickable and lead to valid pages
* Perform testing on additional browsers for better coverage

---

## **Conclusion**

The website shows good performance in layout responsiveness and checkout functionality across desktop and mobile views. However, navigation and search-related issues were identified. Fixing these issues will improve usability and overall compatibility.
