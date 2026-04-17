# NEXUS - Holographic News Interface

NEXUS is a futuristic dual-hand holographic news interface built using HTML, CSS, JavaScript, and MediaPipe Hands. It allows users to control news feeds, articles, journals, and a virtual keyboard using real-time hand gestures such as pinch, swipe, point, and open palm.

## Features

* Dual-hand gesture recognition
* Real-time hand tracking with MediaPipe Hands
* Gesture-based navigation
* Interactive news feed and article viewer
* Virtual holographic keyboard
* Bookmark and journal system
* Sci-fi HUD-inspired interface
* Smooth animations and transitions

## Technologies Used

* HTML5
* CSS3
* JavaScript
* MediaPipe Hands
* Webcam API

## Project Structure

```text
NEXUS/
│── index.html
│── style.css
│── script.js
│── assets/
│   ├── images/
│   ├── icons/
│   └── sounds/
```

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/nexus.git
cd nexus
```

### 2. Open the Project

You can open the project directly in your browser, but using a local server is recommended.

#### Using VS Code Live Server

1. Open the project folder in VS Code.
2. Install the "Live Server" extension.
3. Right-click `index.html`.
4. Click "Open with Live Server".

#### Using Python

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Permissions Required

The browser will ask for webcam access. Allow the permission so MediaPipe can track your hand gestures.

## Supported Gestures

| Gesture            | Action               |
| ------------------ | -------------------- |
| Pinch              | Select / Click       |
| Swipe Left / Right | Switch News Category |
| Open Palm          | Open Main Menu       |
| Point              | Hover / Navigate     |
| Scroll Gesture     | Scroll Articles      |

## How to Use

1. Launch the application.
2. Allow webcam access.
3. Place your hands in front of the camera.
4. Use gestures to interact with the holographic interface.
5. Browse articles, switch categories, and bookmark content.

## Future Improvements

* Voice command support
* AI-based personalized news recommendations
* Multi-language support
* Better gesture accuracy
* Dark and light theme switching

## License

This project is open-source and available under the MIT License.
