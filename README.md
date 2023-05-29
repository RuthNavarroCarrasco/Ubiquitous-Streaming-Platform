
### Ruth Navarro Carrasco, Alicia Benítez Rogero y Ángel José Mancha Núñez

# Movie Box

This project consists of a video playback application that can be controlled through gestures using a mobile device. It is specially designed to be used in an educational environment, where the teacher will use the control part of the app from their mobile device to interact with the video being displayed on another device, such as a projector.

### Main Features
The application will be divided into two parts: a control part that will run on the teacher's mobile device, and a viewer part that will be hosted on another device to view the content. The main features of the application are as follows:

### Gesture Control
The application will allow the video to be controlled through gestures performed on the teacher's mobile device screen. This way, the teacher will be able to interact with the video from any point in the classroom, providing additional dynamism to the classes.

### Real-time Annotations
In addition to the gesture control functionality, the application will also allow the teacher to make real-time annotations on the video by performing a simple gesture with the controller. These annotations will be saved at the exact minute and second when they were made on the viewer's screen, facilitating the review of doubts and questions that arise during the class.

### Touch Mode
For the teacher's convenience, a button has also been included to deactivate gesture recognition and switch to touch mode to control the video. This function will prevent the teacher from having to pay attention to unintentional gestures while performing another task with the mobile device.

## Using the Application
**1.** Go to the root folder and launch the server
- *cd src*
- *node index.js*

**2.** Connect to *localhost 3000*

**3.**  Select how you want the current device to behave (controller or viewer) appropriately.

![visualizador](src/www/media/inicio_index.png)

**4.** In the viewer, select a video.

![visualizador](src/www/media/inicio_viz.png)

**5**.  Once the video has been selected, the controller will display a thumbnail of the same video.
By default, the controller is in touch mode to control the video, so press the indicated button to switch to gesture mode.

![visualizador](src/www/media/viz1.png) 
You can see how a section appears on the right where annotations will be displayed.

![Controlador](src/www/media/tactil_img.png) 

**6.** Within gesture mode
- To 'play/pause' the video: Hang the mobile device around your neck, tilt the device upwards and let it drop again.
- To 'fast forward' the video: Shake the mobile device to the right.
- To 'rewind' the video: Shake the mobile device to the left.



**7.** To switch back to touch mode, simply press the indicated button, and the gestures will be deactivated.

![Controlador](src/www/media/gestos_img.png)

**8.** To take notes on students' questions at the exact minute and second: Swipe down with three fingers on the controller's screen.

![notas](src/www/media/nota_img.png)

**9.** To change the video, simply swipe down the viewer window and select another video. It will be updated on the controller.

![visualizador](src/www/media/viz2.png)


## Technologies Used
The application has been developed using the following technologies

- Programming languages: JavaScript, HTML, CSS
- Runtime environment: Node.js
- API: Sensor API, Touch API
- Gesture recognition framework: AbsoluteOrientationSensor
