# 🪐 Solar System WebAR

A browser-based augmented reality solar system built with **A-Frame** and **WebXR**.

Experience the Sun, all eight planets, and the Moon orbiting in an animated 3D scene directly from your browser—no app installation required.

👉 **[Live Demo](https://ddhd3s.csb.app/)**
*For the AR experience, open the demo in Chrome on a WebXR-compatible Android device.*

## 💫 Features

* **Animated 3D Solar System:** Includes the Sun, eight planets, Earth's Moon, and Saturn's rings.
* **Textured Planet Models:** Each celestial object uses an individual surface texture.
* **Orbital Animation:** Planets rotate independently and orbit the Sun at different speeds.
* **Browser-Based AR:** Access the experience through a supported mobile browser using WebXR.
* **No Build Step:** The project runs using standard HTML, CSS, and A-Frame without package installation.

## 🛠 Technologies

* HTML5
* CSS
* [A-Frame 1.0.4](https://aframe.io/)
* WebXR API

## 🚀 Getting Started

Opening the project as a local file may cause texture-loading or cross-origin issues. Running it through a local web server is recommended.

```bash
# Clone the repository
git clone https://github.com/eun346/solar-system-webar.git

# Enter the project directory
cd solar-system-webar

# Start a local server using Python
python -m http.server 8000
```

Open the following address in your browser:

```text
http://localhost:8000
```

Alternatively, you can use the **Live Server** extension in Visual Studio Code.

## 📱 Running in AR

1. Open the [Live Demo](https://ddhd3s.csb.app/) on a WebXR-compatible Android device.
2. Use a supported browser such as Chrome.
3. Tap the **AR button** displayed on the screen.
4. Allow camera access when prompted.
5. Move your device to view the solar system positioned in front of the camera.

> AR support depends on the device, browser, and WebXR availability.

## ⚠️ Current Limitations

* Planet sizes and distances are adjusted for visibility rather than scientific accuracy.
* Orbit and rotation speeds are accelerated.
* The solar system appears at a predefined position.
* Surface detection and tap-to-place controls are not currently implemented.
* Users cannot yet manually rotate or resize the scene.

## 🗺 Roadmap

Future improvements may include:

* **Interactive AR Controls:** Surface hit testing, tap-to-place positioning, scaling, and rotation.
* **Enhanced UI:** Planet information panels and clearer mobile controls.
* **Animation Controls:** Pause, resume, and adjustable orbit speeds.
* **Display Modes:** Educational and more realistic scale options.
* **Visual Improvements:** Enhanced lighting, materials, and planet effects.

## 🎯 Project Purpose

This project was created as a simple educational demonstration of browser-based augmented reality.

It explores:

* WebXR-based AR development
* A-Frame scene construction
* 3D object positioning
* Texture mapping
* Parent-child transformations
* Orbital and rotational animation

GitHub: [@eun346](https://github.com/eun346)
