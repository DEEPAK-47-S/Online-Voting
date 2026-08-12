# NIET Online Student Election System

Features:
- NIET official header/logo on every page
- Animated CSS blue/gold design
- Maximum 11 candidates
- Candidate photo upload from computer
- Candidate photo shown in voter cards, admin candidate table and results
- Voter registration
- One Voter ID = One Vote
- Duplicate vote prevention
- Live admin results refresh every 3 seconds
- Current leader and vote percentage bars
- CSV export
- Testing-only vote reset

Run:
```bash
pip install -r requirements.txt
python app.py
```

Open: http://127.0.0.1:5000

Admin: http://127.0.0.1:5000/admin/login

Default:
Username: admin
Password: admin123

Change the password and Flask secret key before deployment.

Candidate photos are stored in static/uploads/.

For a real high-stakes election, add HTTPS, stronger authentication, CSRF protection, secure secret management, rate limiting, audit logging, backups and an independent audit process.
