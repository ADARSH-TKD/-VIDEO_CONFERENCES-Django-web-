# Multi-User Video Conferencing Application

This repository contains a robust, real-time, multi-user video conferencing application built using **Django**, **HTML**, **CSS**, **JavaScript**, and the **ZegoCloud** API. The application provides seamless video conferencing capabilities for users, including features like participant management and real-time communication.

---

## Features

- **Real-Time Video Conferencing**: High-quality audio and video communication between multiple participants.
- **User Management**: Register, login, and manage users for secure access.
- **Responsive UI**: Built with HTML and CSS to ensure compatibility across devices.
- **Customizable Rooms**: Create and join virtual meeting rooms.
- **Seamless Integration**: Powered by the ZegoCloud API for real-time video and audio streaming.

---

## Tech Stack

### Frontend:
- **HTML**: For structuring the UI.
- **CSS**: For styling and responsiveness.
- **JavaScript**: For client-side interactions and API integration.

### Backend:
- **Django**: For user authentication, room management, and backend logic.

### Third-Party Service:
- **ZegoCloud API**: For real-time audio and video functionalities.

---

## Prerequisites

Before running this project, ensure you have the following installed:

- **Python** (>= 3.8)
- **Django** (>= 4.0)
- **Node.js** (for managing frontend dependencies, if needed)

---

## Installation

Follow these steps to set up the project locally:

### 1. Clone the Repository
```bash
$ git clone https://github.com/your-username/your-repo-name.git
$ cd your-repo-name
```

### 2. Set Up a Virtual Environment
```bash
$ python -m venv venv
$ source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
$ pip install -r requirements.txt
```

### 4. Set Up ZegoCloud
1. Create an account on [ZegoCloud](https://www.zegocloud.com/).
2. Obtain your **App ID** and **App Secret**.
3. Add these credentials to your project settings.

### 5. Apply Migrations
```bash
$ python manage.py migrate
```

### 6. Run the Development Server
```bash
$ python manage.py runserver
```

Open your browser and navigate to `http://127.0.0.1:8000/`.

---

## Usage

1. **Register/Login**:
   - Create a new account or log in to an existing one.

2. **Create/Join Rooms**:
   - Create a new video conference room or join an existing one using the room ID.

3. **Real-Time Video Call**:
   - Start a video call with participants in the room.

---

## File Structure
```
project/
|— videocall/
|   |— templates/
|   |   |— index.html  # Landing page
|   |   |— room.html   # Video conference room page
|   |— static/
|       |— css/
|       |— js/
|       |— images/
|— manage.py
|— requirements.txt
```

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   $ git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   $ git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   $ git push origin feature-name
   ```
5. Create a Pull Request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For any inquiries or feedback, please reach out to:
- **Name**: Adarsh Nayak
- **Email**: your-email@example.com
- **GitHub**: [ADARSH-TKD](https://github.com/ADARSH-TKD)

---

## Acknowledgments

- [ZegoCloud](https://www.zegocloud.com/) for their amazing real-time API.
- Django community for robust documentation and support.

