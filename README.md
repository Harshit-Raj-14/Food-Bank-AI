# Food-Bank-AI

An AI-based Food Bank App designed to connect NGOs and donors (such as households, restaurants, and organizations) based on their needs. The app facilitates food donation and minimizes food wastage by matching donors with NGOs efficiently based on factors like location, time, and type of food.

---

## Features

### 🔗 Connect Donors and NGOs
- Donors can easily register and connect with nearby NGOs or food banks.
- NGOs can specify their requirements, such as food quantity and type.

### 📍 Location-Based Matching
- Matches donors and NGOs based on their geographical proximity.
- Real-time tracking to identify the closest NGO or food bank.

### 🕒 Time Optimization
- Ensures timely delivery of food to prevent wastage.
- Prioritizes NGOs that need food urgently.

### 🍱 Food Wastage Prevention
- Tracks excess food from restaurants, homes, and other sources.
- Ensures surplus food is redistributed efficiently to those in need.

### 🤖 AI Integration
- Uses AI to analyze donor and NGO data for optimal matching.
- Predicts future food surplus patterns to improve planning.

### 🛠 User-Friendly Interface
- Simplified registration for donors and NGOs.
- Easy-to-use dashboard for managing donations and requirements.

---

## Tech Stack

- **Frontend:** React, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **AI Integration:** TensorFlow.js, OpenAI API
- **Geolocation:** Google Maps API
- **Deployment:** Vercel, AWS

---

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Food-Bank-AI.git
   cd Food-Bank-AI
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables:**
   Create a `.env` file in the root directory and add the following variables:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   OPENAI_API_KEY=your_openai_api_key
   GOOGLE_MAPS_API_KEY=your_google_maps_api_key
   ```

4. **Run the Development Server:**
   ```bash
   npm run dev
   ```

5. **Open the App:**
   Navigate to `http://localhost:3000` in your browser.

---

## How It Works

1. **Donor Registration:**
   - Donors sign up and provide details about their surplus food.
   - Donors - Home, Individuals, Restaurants
   
2. **NGO Registration:**
   - NGOs register and specify their food requirements.

3. **Matching Algorithm:**
   - The AI system matches donors with NGOs based on location, food type, and urgency.

4. **Food Pickup and Delivery:**
   - Donors and NGOs coordinate pickup/delivery via the app.

5. **Impact Tracking:**
   - The app tracks food donations and calculates the reduction in food waste.

---








