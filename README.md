# video-angular
Aplicación Angular utilizando la librería VideoJS-Record para grabar y reproducir video de una webcam

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.0.4.

## Install dependencies

Run `npm install`

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Testing on Linux without a webcam:

```
sudo apt install v4l2loopback-dkms
sudo modprobe v4l2loopback
ffmpeg -re -i video.mp4 -map 0:v -f v4l2 /dev/video0
```

## Testing on Windows without a webcam:

Try this: <https://manycam.com/>