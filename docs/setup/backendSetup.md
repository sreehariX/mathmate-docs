### Backend Setup


1. **Clone & Navigate**
   ```bash
   git clone https://github.com/sreehariX/mathmateAI.git
   cd mathmate/mathmate-backend
   ```


2. **Navigate to Backend Directory**
   ```bash
   cd mathmate/mathmate-backend
   ```

2. **Create & Activate Virtual Environment**
   ```bash
   # Windows
   python -m venv venv
   .\venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Environment Variables**
   Create a `.env` file in the backend root directory:
   ```env
   GOOGLE_CLIENT_ID=your_google_client_id
   GEMINI_API_KEY=your_gemini_api_key
   ```

5. **Start Development Server**
   ```bash
   uvicorn main:app --reload
   ```

6. **Verify Installation**
   - API will be running at: `http://localhost:8000`
   - Access API documentation: `http://localhost:8000/docs`


7. **Pro Tip**
   - I Will recommend using virtual environment for python otherwise you might face issues with the dependencies (basicaly dependencies conflicts).
