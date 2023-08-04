# Flask Keep-Alive Script

This is a simple Flask script that creates a basic web server to keep your application alive. It responds to requests with a "I'm alive!" message.

## Usage

1. Install Flask:

   ```bash
   pip install Flask
   ```

2. Copy the provided script to your project directory.

3. Import and use the `keep_alive` function in your application:

   ```python
   from your_script_name import keep_alive

   # Your application code here

   if __name__ == '__main__':
       keep_alive()
   ```

4. Run your script:

   ```bash
   python your_script_name.py
   ```

5. Your Flask server will now be running and responding to requests, helping to keep your application alive.

## Configuration

You can modify the `run` function inside the script to configure the server's host and port. By default, the server runs on `0.0.0.0` (all available network interfaces) and port `8080`.

## Note

This script is intended for simple applications that require a basic keep-alive mechanism. For more complex applications, consider deploying on a production server with proper hosting and monitoring.

## License

This project is licensed under the [MIT License](LICENSE).
