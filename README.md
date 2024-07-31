# StreamCast: HTTP-Based Screen and Audio Casting

StreamCast is an open-source project that enables screen and audio casting to local devices using HTTP protocols. It's designed specifically for scenarios where traditional casting methods are unavailable, such as smart TVs without built-in casting support.

## Features

- Screen capture and streaming via HTTP
- System audio capture and streaming
- Web-based receiver interface for easy viewing on any device with a web browser
- Low-latency transmission for near real-time experience
- Cross-platform compatibility (Windows, macOS, Linux)

## Tech Stack

- Backend: Python (Flask, SocketIO)
- Frontend: HTML, JavaScript
- Screen Capture: mss library
- Audio Capture: sounddevice library (planned)

## Getting Started

### Prerequisites

- Python 3.7+
- pip

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/prathameshks/StreamCast-HTTP-Screen-and-Audio-Casting.git
   ```
2. Navigate to the project directory:
3. Install required dependencies:
   ```
   pip install -r requirements.txt
   ```

   ### Usage

1. Run the server:
   ```
   python server.py
   ```
   2. Open a web browser on your TV or target device and navigate to:
      ```
      http://<your-computer-ip>:5000
      ```

      ## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the need for universal casting solutions
- Thanks to all contributors and users of this project

## Roadmap

- [ ] Implement audio streaming functionality
- [ ] Improve streaming quality and reduce latency
- [ ] Add support for multiple receiver devices
- [ ] Create a user-friendly GUI for the sender application
