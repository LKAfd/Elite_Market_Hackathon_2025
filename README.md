# **Elite Market**

## **1. Project Overview**
Elite Market is a dynamic and responsive e-commerce web application designed to provide a seamless shopping experience. Built with **Next.js**, **TypeScript (TSX)**, and **Tailwind CSS**, the platform incorporates modern web development practices and a user-friendly interface.

### **Features**
- Product Listing and Filtering
- Product Detail Pages
- Shopping Cart and Checkout Functionality
- Responsive Design for Mobile and Desktop
- Secure Deployment on Vercel

---

## **2. Day-wise Activities Summary**
### **Day 1: Project Initialization**
- **Tasks:**
  - Initialized the project using `npx create-next-app@latest`.
  - Set up TypeScript and Tailwind CSS for styling.
  - Created a GitHub repository for version control.
- **Output:**
  - Project structure established.
  - GitHub repository pushed with initial commits.

---

### **Day 2: Core Functionality Development**
- **Tasks:**
  - Created product listing and product detail pages using mock data.
  - Designed responsive layouts with Tailwind CSS.
  - Configured routing for navigation between pages.
- **Output:**
  - Functional product listing and detail pages.

---

### **Day 3: Shopping Cart Implementation**
- **Tasks:**
  - Integrated state management using React Context for the shopping cart.
  - Built the "Add to Cart" functionality.
  - Displayed cart items and calculated totals dynamically.
- **Output:**
  - Shopping cart functionality completed.

---

### **Day 4: Checkout Flow**
- **Tasks:**
  - Designed and implemented a checkout page with form validation.
  - Set up mock API endpoints for handling checkout data.
  - Tested the checkout process for both desktop and mobile views.
- **Output:**
  - Checkout flow implemented with mock API integration.

---

### **Day 5: Testing and Optimization**
- **Tasks:**
  - Performed unit and integration tests using Jest.
  - Ensured cross-browser compatibility.
  - Improved load time performance by optimizing images and code splitting.
- **Output:**
  - Testing completed; performance improved.

---

### **Day 6: Deployment and Documentation**
- **Tasks:**
  - Deployed the application on Vercel.
  - Created this **README.md** file summarizing the activities.
  - Organized all reports, test cases, and instructions into a structured GitHub repository.
- **Output:**
  - Application live on Vercel: [Elite Market Live](https://elite-market.vercel.app/)
  - Comprehensive documentation added.

---

## **3. Deployment Instructions**
1. Clone the repository:  
   ```bash
   git clone https://github.com/LKAfd/Elite_Market_Web_Project_Hachathone2025.git
   ```
2. Install dependencies:  
   ```bash
   npm install
   ```
3. Run the development server:  
   ```bash
   npm run dev
   ```
4. Build and export for production:  
   ```bash
   npm run build
   npm start
   ```

---

## **4. Reports and Test Cases**
- **Lighthouse Report:** *(https://drive.google.com/file/d/1D5P3yqGS6x5VHXAM3VxCPJciJmNjnSJU/view?usp=drive_link)*

- **Integration Tests:**
  - Covered areas: Navigation, cart functionality, checkout flow.

---

## **5. GitHub Repository Structure**

The project is organized as follows:

```plaintext
elite-market/
├── public/
│   ├── assets/
│   ├── images/
├── script/
│   └── importData.js
├── src/
│   ├── app/
│   │   ├── about/
│   │   │   └── page.tsx
│   │   ├── blog/
│   │   │   └── page.tsx
│   │   ├── contact/
│   │   │   └── page.tsx
│   │   ├── login/
│   │   │   └── page.tsx
│   │   ├── products/
│   │   │   └── page.tsx
│   │   ├── register/
│   │   │   └── page.tsx
│   │   ├── shop/
│   │   │   └── page.tsx
│   │   ├── studio/
│   │   │   └── [[...tool]]/
│   │   │       └── page.tsx
│   │   ├── global.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── components/
│   │   ├── EditorPics.tsx
│   │   ├── FeaturedPosts.tsx
│   │   ├── Footer.tsx
│   │   ├── HeroSection.tsx
│   │   ├── Navbar.tsx
│   │   ├── ProductGrid.tsx
│   │   └── VitaClassic.tsx
│   ├── sanity/
│   │   ├── lib/
│   │   │   ├── client.ts
│   │   │   ├── image.ts
│   │   │   └── live.ts
│   │   ├── schemaTypes/
│   │   │   ├── index.ts
│   │   │   └── product.ts
│   │   ├── env.ts
│   │   └── structure.ts
├── .gitignore
├── README.md
├── eslint.config.mjs
├── next.config.ts
├── package-lock.json
├── package.json
├── postcss.config.mjs
├── sanity.cli.ts
├── sanity.config.ts
├── tailwind.config.ts
└── tsconfig.json


---

### **6. Key Learnings and Future Scope**
- **Learnings:**
  - Hands-on experience with Next.js, TypeScript, and Tailwind CSS.
  - Managing project structure and routing effectively.
  - Implementing responsive designs and state management.
- **Future Scope:**
  - Add payment gateway integration.
  - Implement user authentication and profiles.
  - Enhance product filtering with real-time search.

---
