# Chino-AR
Marker based AR.js test project  
This is just for hobby.

## Requirements
- ngrok
    - To make https site instantly.
- python(3)
    - To make http server instantly.
- magical-chino.gltf
    - Model file. Place into this project directory.
    - [You can make with using blender.](https://www.blender.org/)
- marker.patt
    - Marker file. Place into this project directory.
    - [You can make with using AR.js marker training.](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html)

## How to run
### 1 Open ngrok tunnel
```ngrok http 8000```
- I recommend to [register account](https://ngrok.com/docs#getting-started-authtoken) before doing this.
### 2 Open webserver
```python -m http.server 8000```
- You need to run this in this project directory.
### 3 Open ngrok page from smartphone
Just access the page.
### 4 Show your marker to camera
Maybe your model appears!  
If not, probably your model scale or filesize is too big.

## Useful Links
[AR.js Documentation](https://ar-js-org.github.io/AR.js-Docs/)  
[AR.js studio](https://ar-js-org.github.io/studio/)