# Helmet detection with YOLOV5 and Flask

## Development Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/supunsathsara/HelmetDetect.git
   ```

2. Navigate to the project directory:
   ```bash
   cd HelmetDetect
   ```

3.Switch to the web branch where the web code resides:
    ```bash
    git checkout web
    ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Run the Flask app using the development server:
   ```bash
   python main.py
   ```

6. Access the application in your web browser at `http://localhost:5000`.

## Production Deployment

For deploying the Flask app in production, we recommend using Gunicorn, a WSGI HTTP server for Python web applications.

1. Install Gunicorn:
   ```bash
   pip install gunicorn
   ```

2. Run the app using Gunicorn:
   ```bash
   gunicorn -w 4 -b 0.0.0.0:8000 main:app
   ```

   - `-w 4` specifies the number of worker processes.
   - `-b 0.0.0.0:8000` binds the server to all network interfaces on port 8000.

3. You may need to adjust the configuration according to your production environment.

4. Access the application using the specified server IP and port.

## Contributors
- [@supunsathsara](https://github.com/supunsathsara)
- [@madubashinigamage](https://github.com/madubashinigamage)
- [@MumthazDeen](https://github.com/MumthazDeen)
- [@YuwaniN](https://github.com/YuwaniN)
- [@sasini02](https://github.com/sasini02)
  <br>
  <br>
[![HelmetDetect's Contributors](https://stats.deeptrain.net/contributor/supunsathsara/HelmetDetect?theme=dark)](https://github.com/supunsathsara/HelmetDetect)

<hr>

Please feel free to contribute to the project and provide any feedback or suggestions.
