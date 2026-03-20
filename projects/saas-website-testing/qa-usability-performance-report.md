# QA Usability & Performance Report
**Website:** RentPotty

---

## 1. Usability Findings

### 1.1 Navigation Clarity Issues
- The navigation includes both **“Order Management”** and **“My Orders”**, which appear to serve overlapping purposes.
- This redundancy can confuse first-time users and make navigation less intuitive.

### 1.2 Map Interaction & Mobile Usability
- The map on pages like **“Add a Unit”** is overly large and dominates the screen.
- Users may unintentionally interact with the map while trying to scroll, especially on mobile devices.
- This creates friction and reduces usability for field users (e.g., construction managers).

### 1.3 Order History Structure
- Actions such as:
  - “Change User Info”
  - “Service Frequency”
- are displayed at the same hierarchy level as the original order.
- This makes the order history harder to read and less logically structured.

### 1.4 Page Purpose & Context Clarity
- Some pages (e.g., Add Units, Request Actions) lack a clear explanation of:
  - what the action does
  - what happens after submission
- Users may feel uncertain about outcomes (e.g., request vs immediate change).

### 1.5 Order Flow Complexity
- The order process involves multiple steps and long forms.
- This is not user-friendly for:
  - first-time users
  - mobile users
- Lack of:
  - step indicators
  - clear progress feedback

### 1.6 Submission Feedback
- After clicking **Submit**, users may not receive clear feedback.
- Risks include:
  - confusion about whether submission succeeded
  - accidental double submissions

---

## 2. Performance Observations

### 2.1 Interaction Performance
- Large interactive elements (e.g., map) can impact smooth scrolling and responsiveness, particularly on mobile devices.

### 2.2 Mobile Experience
- The current layout is not fully optimized for mobile workflows:
  - Long forms require excessive scrolling
  - Lack of sticky CTAs slows task completion

### 2.3 Perceived Performance
- Lack of loading indicators (e.g., spinners, disabled buttons) creates uncertainty during actions like form submission.
- Users may perceive the system as slow or unresponsive even if backend performance is acceptable.

---

## 3. Top 5 Improvement Suggestions

### 1. Simplify Navigation Structure
- Remove redundancy between **“Order Management”** and **“My Orders”**
- Replace with clearer structure (e.g., Dashboard + Profile)  
  

### 2. Optimize Map Usability
- Reduce map size or make it collapsible
- Prevent accidental interactions during scrolling
- Optimize for mobile touch behavior  


### 3. Improve Order Flow Experience
- Break long forms into **step-by-step flow**
- Add **progress indicator (Step 1 → Step 4)**
- Add **mobile sticky CTA (e.g., “Start Your Order”)**  


### 4. Enhance Order Tracking Visibility
- Add:
  - **Timeline view**
  - **Status indicators (Pending / Approved / Completed)**
- Group updates as sub-records under the original order  


### 5. Improve Submission Feedback & Validation
- Add **confirmation summary before submission**
- Update submit behavior:
  - Disable button after click
  - Show loading spinner
  - Use clearer button text (e.g., “Submit Request”)  


---

## Overall Summary
The platform is functionally solid, but several usability and interaction issues create friction—especially for **first-time and mobile users**. By improving navigation clarity, simplifying workflows, and enhancing feedback mechanisms, the platform can significantly improve **ease of use, user confidence, and conversion rates**.
