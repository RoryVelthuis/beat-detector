# Beat Detector 

This project demonstrates a web application that uses WebSockets to process audio tracks and visualize beats in realtime.

## Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- [Python](https://www.python.org/) (v3.6 or higher)
- [Git](https://git-scm.com/)

## Installation

### Clone the repository

```sh
git clone https://github.com/RoryVelthuis/beat-detector.git
cd web-socket-test
```

### Server 

#### Navigate to the server directory:
```sh
cd server
```

#### Create a virtual environment:
```sh
python -m venv venv
```

#### Activate the virtual environment:
On Windows
```sh
venv\Scripts\activate
```

On macOS and Linux:
```sh
source venv/bin/activate
```

#### Install the required Node.js packages:
```sh
npm install
```

#### Install the required Python packages:
```sh
pip install -r requirements.txt
```

#### Start the server
```sh
npm run dev
```

### Web client

#### Navigate to the web-client directory:
```sh
cd web-client
```

#### Install the required Node.js packages:
```sh
npm install
```

#### Start the web-client
```sh
npm run dev
```



