# 🚀 Project Setup & Development Guide

## 📌 Getting Started

### 1⃣ Install Dependencies  
Before running the project, install all required dependencies:

```bash
npm install
npm i axios
npm install drizzle-orm
npm i @google/generative-ai
npm i drizzle-orm @neondatabase/serverless dotenv
npx shadcn@latest init

```

### 2⃣ Start the Development Server  
Run the following command to start the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

### 3⃣ Open in Browser  
Once the server is running, open:  
👉 [http://localhost:3000](http://localhost:3000)  

---

## 🛠 Additional Commands

### 🔄 Restart the Server
If you make changes and need to restart:

```bash
npm run dev
```

### 🏧 Build for Production  
To create an optimized production build:

```bash
npm run build
```

### 🚀 Start the Production Server  
Once built, run the production server:

```bash
npm start
```

---

## 🛠 Troubleshooting  

- If you face dependency issues, try:
  ```bash
  rm -rf node_modules package-lock.json && npm install
  ```
- Ensure you have the correct Node.js version installed. **Recommended: `>=16.x`**  
- Check the logs for any errors and verify environment variables if needed.
- Refer inngest, drizzle and Clerk Documentaion

---

