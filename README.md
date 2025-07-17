# SpeakSpace

**SpeakSpace** is a Django-based web platform that connects users with mentors for **mock interview sessions**, and provides **real-time topic-based chatrooms** to foster collaborative learning and peer interaction.

---

## 🔑 Roles

### 👤 User

- Requests mock interviews by selecting a time slot.
- Participates in live chatrooms focused on specific topics.

### 🧑‍🏫 Mentor

- Approves or declines mock interview requests based on availability.
- Conducts the interview using the integrated Jitsi Meet video call.

### 🧑‍💼 Moderator

- Oversees interview coordination between users and mentors.
- Manages the scheduling process to ensure smooth interactions.

---

## 💡 Features

- 📅 **Mock Interview Scheduling**:  
  Users can request a session; moderators facilitate it, and mentors confirm based on availability.

- 🎥 **Video Integration**:  
  Jitsi Meet API is used to host the interview video calls securely and seamlessly.

- 💬 **Live Topic Chatrooms**:  
  Users can join real-time discussion rooms to talk about specific technical topics with peers.

---

## 🛠️ Tech Stack

| Layer       | Technology                                                                       |
| ----------- | -------------------------------------------------------------------------------- |
| Backend     | Python, Django                                                                   |
| Frontend    | HTML, CSS                                                                        |
| Video Calls | [Jitsi Meet API](https://jitsi.github.io/handbook/docs/dev-guide/dev-guide-web/) |
| Database    | SQLite / PostgreSQL (as configured)                                              |

---

## ⚙️ Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/SpeakSpace.git
   cd SpeakSpace
   ```
