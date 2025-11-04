secure-polling-system-project

Secure Polling System - ECI Compliant

🏛️ Project Information

Institution: Gokaraju Rangaraju Institute of Engineering and Technology (GRIET)

Department: Computer Science and Engineering (CSM)

Group: Elite Stars Group

👥 Team Members

Mani Vignesh

Anjaneya Reddy

Preetham Kumar

Prakash

Dilip Kumar

📋 Project Summary

This project is a fully functional, secure electronic polling system designed in compliance with Election Commission of India (ECI) guidelines. The system implements robust security measures to ensure:

✅ One vote per citizen - Prevents duplicate voting using Voter ID and Aadhaar verification

✅ Database integrity - Persistent storage with protection against tampering

✅ Admin controls - Secure admin panel with authentication for database management

✅ Real-time statistics - Live vote counting and party-wise result tracking

✅ Voter assistance - Interactive chatbot providing ECI-compliant voting guidance

🎯 Key Features

1. Voter Verification System
Validates 10-character alphanumeric Voter ID (EPIC)
Verifies 12-digit Aadhaar number
Implements strict duplicate detection
Ensures at least 3 letters and at most 7 digits in Voter ID

3. Electronic Voting Machine (EVM) Interface
Visual representation of 10 major Indian political parties
Party symbols for accessibility
Clear selection feedback
Vote confirmation with unique confirmation ID

5. Secure Database Management
Persistent storage using browser's storage API
Tracks all voter IDs and Aadhaar numbers
Records valid votes, invalid attempts, and party-wise counts
Protection against data loss

7. Admin Control Panel
****Username: ECIpolling
****Password: ECI2025

9. View comprehensive voting statistics
Database reset capability (with double confirmation)
Real-time monitoring of all voting activities

11. Real-Time Vote Statistics
Valid votes counter
Invalid attempts tracker
Total attempts monitor
Party-wise vote distribution
Auto-redirect countdown after vote casting

13. Interactive Poll Assistant Chatbot
Answers questions about voting procedures
Explains ECI rules and guidelines
Provides information on eligibility criteria
Describes party symbols and ballot process
Ensures voter awareness and transparency
🚀 How to Use
For Voters:
Open the Application

Launch secure_voting_system.html in a modern web browser
Voter Verification

Enter your 10-character Voter ID (EPIC)
Enter your 12-digit Aadhaar number
Click "Verify Voter"
Cast Your Vote

Review the ballot with party symbols
Click on your chosen party
Click "Cast Vote" to confirm
Note your unique confirmation ID
View Results

Statistics page displays automatically after voting
Shows vote counts and party-wise distribution
For Administrators:
Access Admin Panel

Click "Admin Panel" button (top-right corner)
Username: ECIpolling
Password: ECI2025
View Statistics

Total votes cast
Valid and invalid votes
Registered voter IDs and Aadhaar numbers
Reset Database (if needed)

Click "Reset Database" button
Confirm twice (irreversible action)
All voting records will be cleared
🔒 Security Features
Duplicate Prevention

Database checks before verification
Double-check before vote confirmation
Prevents same ID/Aadhaar from voting twice
Data Validation

Regex pattern matching for Voter ID and Aadhaar
Format enforcement (alphanumeric, digit-only)
Length validation
Admin Authentication

Password-protected admin panel
Secure access to sensitive operations
Voter Anonymity

Votes cannot be traced back to individuals
Aadhaar displayed partially (last 4 digits only)
Secure confirmation ID generation
🗳️ Voting Logic
Verification Process:
1. User enters Voter ID and Aadhaar
   
3. System validates format:
   - Voter ID: 10 chars, min 3 letters, max 7 digits
   - Aadhaar: exactly 12 digits
   - 
4. System checks database for duplicates
5. If valid → proceed to ballot
6. If invalid → display error message
Vote Casting Process:
1. Voter selects party on EVM ballot
2. System verifies selection
3. Final duplicate check performed
4. Vote recorded with:
   - Voter ID
   - Aadhaar number
   - Selected party
   - Unique confirmation ID
   - Timestamp
5. Database updated:
   - Add to used Voter IDs
   - Add to used Aadhaar numbers
   - Increment valid votes
   - Increment party vote count
6. Display confirmation and statistics
Database Structure:
Storage Keys:
- votingdb:voterids → Array of used Voter IDs
- votingdb:aadhaar → Array of used Aadhaar numbers
- votingdb:votes → Array of vote records
- votingdb:valid → Count of valid votes
- votingdb:invalid → Count of invalid attempts
- votingdb:total → Total attempts
- votingdb:parties → Object with party-wise counts
🎨 Supported Political Parties
The system includes 10 major Indian political parties:

BJP - Bharatiya Janata Party (🪷 Lotus)
INC - Indian National Congress (✋ Hand)
AAP - Aam Aadmi Party (🧹 Broom)
CPM - Communist Party Marxist (⚒️ Hammer & Sickle)
CPI - Communist Party of India (🌾 Ears of Corn)
TMC - Trinamool Congress (🌸 Flower)
BSP - Bahujan Samaj Party (🐘 Elephant)
NCP - Nationalist Congress Party (⏰ Clock)
SS - Shiv Sena (🐯 Tiger)
SP - Samajwadi Party (🚲 Bicycle)
📁 File Structure
secure-polling-system-griet/
│
├── README.md                          # Project documentation
└── secure_voting_system.html          # Main application file
🛠️ Technologies Used
HTML5 - Structure and markup
CSS3 - Styling with gradients and animations
JavaScript (ES6+) - Application logic and interactivity
Browser Storage API - Persistent data storage
Responsive Design - Mobile and desktop compatibility
📖 ECI Compliance
This system adheres to Election Commission of India guidelines:

✅ Universal adult suffrage
✅ Secret ballot principle
✅ One person, one vote
✅ Accessible voting with party symbols
✅ Voter education and assistance
✅ Prevention of duplicate voting
✅ Transparent result tabulation
🔧 Installation
Clone the Repository

git clone https://github.com/dilipkumarmamidi02-star/Secure-Vote-Cast-Polling.git
cd secure-vote-cast-polling
Open the Application

Simply open secure_voting_system.html in any modern web browser
No server or additional dependencies required
Start Voting

The system is ready to use immediately

Database initializes automatically on first run

****For Admin Panel Accessing

Username: ECI@polling

Password: ECI@2025

📝 Usage Notes
Browser Compatibility: Works best on Chrome, Firefox, Edge, Safari
Storage: Uses browser's local storage - data persists across sessions
Testing: Use admin panel to reset database between test runs
Security: Change admin credentials in production environment
🤝 Contributing
This project was developed as an academic demonstration. For improvements or issues:

Fork the repository
Create a feature branch
Submit a pull request with detailed description
📞 Contact
For questions or feedback, please contact the E Group team at:

Gokaraju Rangaraju Institute of Engineering and Technology
Department of Computer Science and Engineering (CSM)
📄 License
This project is developed for educational purposes.

🙏 Acknowledgments
Election Commission of India for voting guidelines
GRIET CSM Department for project guidance
E Group Team for collaborative development
Developed with 💙 by Elite Stars Group - GRIET CSM Department

Empowering Democracy Through Technology
