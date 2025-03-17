### **Step 1: Initialize Git in Your Project Folder**
1. Open your terminal or command prompt.
2. Navigate to your project folder using:  
   ```bash
   cd path/to/your/project
   ```
3. Initialize Git:  
   ```bash
   git init
   ```

### **Step 2: Connect to GitHub**
1. Go to **GitHub** and create a **new repository** (without README, `.gitignore`, or license).
2. Copy the **repository URL**.

3. Add your remote repository:
   ```bash
   git remote add origin your-repository-url
   ```

### **Step 3: Add and Commit Your Files**
1. Add all files:  
   ```bash
   git add .
   ```
2. Commit your changes:  
   ```bash
   git commit -m "Initial commit - IMDB Project"
   ```

### **Step 4: Push to GitHub**
1. If your branch is `main`:
   ```bash
   git branch -M main
   ```
2. Push your code:  
   ```bash
   git push -u origin main
   ```

---

### **Step 5: Create a README File**
1. Create a `README.md` file in your project folder:
   ```bash
   touch README.md
   ```
2. Open `README.md` and add project details:
   ```markdown
   # IMDB Clone (ReactJS)

   ## 📌 Overview
   A mini IMDB clone built using ReactJS, fetching movie data from the OMDB API. The app allows users to search for movies dynamically, view details, and save favorite movies.

   ## 🚀 Features
   - **Real-time search** (movies appear as you type, like Google search)
   - **Movie details page** (displays movie name, photo, plot, etc.)
   - **Favorites page** (stores favorite movies, even after refresh)
   - **Styled using CSS**
   - **Hosted on Bytexl**

   ## 🔗 Live Demo
   https://2211cs050090.bytexl.live/
   [Click here to view the project](your-hosted-url)

   ## 📦 Setup Instructions
   1. Clone the repository:
      ```bash
      git clone your-repository-url
      ```
   2. Install dependencies:
      ```bash
      npm install
      ```
   3. Run the app:
      ```bash
      npm start
      ```
   ```

### **Step 6: Push README to GitHub**
1. Add and commit the file:
   ```bash
   git add README.md
   git commit -m "Added README file"
   ```
2. Push to GitHub:
   ```bash
   git push origin main
   ```

---

