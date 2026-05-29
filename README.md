# Siyanda POE2
## Overview

CyberBuddy is a WPF-based Cybersecurity Awareness Chatbot developed in C# using Visual Studio.

The purpose of the chatbot is to educate users about cybersecurity topics such as:

- Password Safety
- Phishing Attacks
- Safe Browsing
- Privacy Protection
- Two-Factor Authentication (2FA)
- General Cybersecurity Awareness

The chatbot provides an interactive conversation experience by using keyword recognition, sentiment detection, memory recall, random responses, and user interest tracking.


## Features

### User-Friendly GUI
- WPF graphical user interface
- Multiple screens (Home, Username, Chat)
- Custom CyberBuddy logo
- Rounded buttons and textboxes
- User-friendly design

### Username Validation
- User cannot proceed without entering a username
- Error messages displayed when username field is empty

### Cybersecurity Knowledge Base
The chatbot can answer questions related to:

- Password Safety
- Phishing
- Safe Browsing
- Privacy
- Cybersecurity
- Two-Factor Authentication

### Keyword Recognition
The chatbot recognizes keywords and related phrases such as:

### Random Responses
The chatbot provides random responses for:
- Greetings
- Cybersecurity topics
- Fallback messages
- Follow-up questions

This prevents repetitive conversations.

### Conversation Flow
The chatbot maintains context by remembering the last topic discussed.

Examples:

User:
```
Tell me about phishing
```

Bot:
```
Phishing is a cyberattack that attempts to steal personal information.
```

User:
```
Tell me more
```

Bot:
```
Here is another tip about phishing...
```

### Memory and Recall
CyberBuddy remembers user interests.

Example:

User:
```
I am interested in phishing and passwords
```

The chatbot stores these interests and periodically reminds the user about them.

### Interest Reminders
After every three messages, CyberBuddy checks saved interests and reminds the user.

Example:

```
Reminder: You are interested in phishing and passwords.
Would you like another tip?
```

### Sentiment Detection
CyberBuddy can detect user emotions and respond appropriately.

Supported emotions:
- Worried
- Scared
- Frustrated
- Confused

Example:

User:
```
I am worried about hackers
```

Bot:
```
It is understandable to feel worried. Cyber threats are common, but safe habits help protect you.
```

### Voice Greeting
A voice greeting is played when the application starts.

---

## Technologies Used

- C#
- WPF (Windows Presentation Foundation)
- .NET Framework
- Visual Studio
- GitHub

---


## How to Use

1. Launch CyberBuddy.
2. Click the Start button.
3. Enter your username.
4. Begin chatting with CyberBuddy.
5. Ask cybersecurity-related questions.
6. Type follow-up questions such as:
   - Tell me more
   - Explain
   - Continue


## Example Questions

- What is phishing?
- How do I create a strong password?
- What is safe browsing?
- Explain privacy protection.
- What is 2FA?
- I am interested in phishing.
- I am worried about cybercrime.

---

## GitHub Releases

### Version 1.0
Initial chatbot implementation:
- Basic GUI
- Username validation
- Keyword recognition

### Version 1.1
Feature enhancements:
- Memory recall
- Sentiment detection
- Follow-up responses

### Version 2.0
Final submission:
- Improved GUI
- Interest tracking
- Random responses
- README documentation
- Final testing and debugging

---

## Author

**Siyanda Ndlovu**

PROG6221 – Programming 2A

IIE Roswbank International

---

## Declaration

This project was developed as part of the PROG6221 Programming 2A Portfolio of Evidence (POE) and demonstrates the application of object-oriented programming principles, GUI development, cybersecurity awareness concepts, memory recall, sentiment analysis, and user interaction design.
