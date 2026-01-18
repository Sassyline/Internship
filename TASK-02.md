# Task-02: Compatibility Testing for Basic Web Page (Updated Values)

**Website Tested**
Online Retail Demo Website (ShopSphere)

---

## **Test Environment**

**Browsers Tested**
Google Chrome (Desktop)

**Devices Tested**
Desktop
Mobile (Responsive Mode)

---

## **Overview**

Compatibility testing was conducted to verify consistent functionality and visual appearance of the website across selected browsers and device views. The testing focused on layout alignment, navigation menus, product listing, search functionality, footer links, and core user actions such as viewing product details and placing orders.

---

## **Test Findings**

### **TC_001:**

**Test Case:** Verify website behavior on Chrome Desktop

**Expected Result:**
Website should load quickly with proper layout and smooth page transitions

**Actual Result:**
Website loads successfully with correct layout and smooth transitions

**Status:**
**“Pass”**

---

### **TC_002:**

**Test Case:** Verify header navigation – Products menu

**Expected Result:**
Products menu should display all product categories

**Actual Result:**
Products menu displays categories but overlaps with banner section

**Status:**
**“Fail”**

---

### **TC_003:**

**Test Case:** Verify header navigation – Offers menu

**Expected Result:**
Offers menu should redirect to the promotions page

**Actual Result:**
Offers menu redirects to a page with missing images

**Status:**
**“Fail”**

---

### **TC_004:**

**Test Case:** Verify header search bar functionality

**Expected Result:**
Search bar should display relevant products based on entered keywords

**Actual Result:**
Search bar displays results but takes significant time to load

**Status:**
**“Fail”**

---

### **TC_005:**

**Test Case:** Verify Add to Cart and order placement functionality

**Expected Result:**
Items should be added to the cart and order confirmation should be displayed

**Actual Result:**
Items are added successfully and confirmation message is shown

**Status:**
**“Pass”**

---

### **TC_006:**

**Test Case:** Verify footer navigation links

**Expected Result:**
Footer links such as About Us, FAQ, Help Center, and Contact should be accessible

**Actual Result:**
All footer links are visible, but Help Center link opens an error page

**Status:**
**“Fail”**

---

### **TC_007:**

**Test Case:** Verify responsiveness on mobile view

**Expected Result:**
Website should adapt to mobile resolution with proper alignment and readability

**Actual Result:**
Website adapts correctly with readable text and no layout distortion

**Status:**
**“Pass”**

---

## **Issues Identified**

1. Products menu overlaps with the banner section
2. Offers page loads with missing images
3. Search results take too long to load
4. Help Center footer link redirects to an error page

---

## **Recommendations**

* Optimize header menu layout for better alignment
* Fix broken image paths on the Offers page
* Improve performance of the search feature
* Correct the Help Center link routing
* Extend testing across additional browsers and real mobile devices

---

## **Conclusion**

The website demonstrates good responsiveness and stable cart functionality across desktop and mobile views. However, issues related to navigation layout, search performance, and broken links were identified. Addressing these issues will enhance compatibility, performance, and overall user satisfaction.
