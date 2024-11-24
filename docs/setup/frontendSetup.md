---
sidebar_position: 2
---

### Frontend Setup

1. **Clone & Navigate**
   ```bash
   git clone https://github.com/sreehariX/mathmateAI.git
   cd mathmate/mathmate-frontend
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Configure Environment Variables**
   Create a `.env` file in the mathmate-frontend directory and add:
   ```env
   VITE_GOOGLE_CLIENT_ID=your_google_client_id
   VITE_API_URL=http://localhost:8000
   ```
   

4. **Start Development Server**
   ```bash
   npm run dev
   ```

5. **Access the Application**
   - Open your browser and visit: `http://localhost:5173`
   - You should see the MathMate AI interface running locally!
