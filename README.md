# FlutterAppShowcase

FlutterAppShowcase is a simple tool that allows you to showcase your Flutter Android or iOS apps online, providing a glimpse of how they would look and work without the need for installation.

## Usage

To use FlutterAppShowcase, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/FlutterAppShowcase.git

   ```

2. Build the app for the web using Flutter:

```
flutter create --platforms web

flutter build web --web-renderer html
```

(the first commands enables Web platform for your project.<br>
The second command builds webApp under build/web folder.)

3. Now copy the generated build from your project `yourProjectName/build/web`
   <br>copy the `web` folder
   <br> and replace with the `web` folder in this repo.

4. Rename the title and description in the index.html file to match your app's information:

```
   <!-- add Application Title here -->
   <title>Your App Name</title>
```

(done, now when you serve this directory with any server and if everything went right, you should see a live version of your app in ```index.html```)

5. (optional) Host your application,
you can use the LiveServer Extention,
or XAMPP server for local testing.
<br>
you can use Github Pages or Firebase/Netlify any server for hosting this.

## Features-

Now, your app will be accessible online in a browser. Users can interact with it, including touch and scroll actions. It is also responsive and will adapt beautifully to both mobile and desktop screens.

## Working
The visualization is achieved by embedding your Flutter app's web build within an HTML template. The template provides a border and a device frame, giving users the impression of using a real device. The iframe within the template loads your web build, allowing users to interact with your app as if it were installed on their Android device.



This tool offers a convenient way to demonstrate your Flutter app's capabilities to potential users or clients without requiring them to install the app on their devices.

Note: This is a visualization tool and does not host the actual app. Users must have an internet connection to access the app through this showcase.

Enjoy showcasing your Flutter app online!
