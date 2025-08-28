# ✈️ Flight Booking Agent API

A simple **FastAPI-based Agentic API** that lets users:
- Create flight bookings
- Add multiple passengers
- Get passenger count
- Suggest the best possible flight (mocked)

---

## 🚀 How to Run

step 1: first install fast api and uvicorn from the requiremnts.txt file.

step 2: run and save the flight_agent.py (use any platform i have used Google colab to run the code and saved as .py file) file in desktop.

step 3: now run the file using api server by using the below command:
cd "C:\Users\Username\OneDrive\Desktop"
uvicorn flight_agent:app --reload

NOTE: change the address according to where you are storing the flight_agent.py file i have stored it in the desktop, so i have used that address.

step 4: In command prompt you will find something like this
 "Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)"
ctrl+click on the server link/address iit will redirect you to some page then in the web address add "/docs" at last you will find the flight booking Agent API page.

Clone the repo and then execute in your profile:
   ```bash
   git clone https://github.com/YOUR-USERNAME/FlightBookingAgent.git
   cd FlightBookingAgent
