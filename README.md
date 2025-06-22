# Secure Voting System with OTP Verification

This project is a GUI-based voting system built using Python and Tkinter, enhanced with email OTP authentication and text-to-speech prompts. It ensures that users authenticate via a one-time password (OTP) sent to their Gmail before casting their vote.

---

## 🚀 Features

-  OTP-based login using Gmail
-  Text-to-speech prompts via `pyttsx3`
-  Simple and intuitive Tkinter GUI
-  Sends OTP via SMTP using Gmail
-  Voting interface with multiple candidates
-  Invalid OTP handling with alerts

---


## 🖥️ How It Works

1. User enters name and Gmail ID.
2. A 6-digit OTP is generated and sent to the user’s Gmail.
3. User enters the received OTP.
4. If OTP is valid → access is granted to vote.
5. User selects a candidate and casts their vote.

---

