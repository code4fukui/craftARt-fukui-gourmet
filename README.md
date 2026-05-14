# craftARt-fukui-gourmet

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

An AR web application that brings Fukui's local culinary specialties to life using 3D models. This project uses the craftARt framework to create an immersive experience on both mobile devices and VR/XR headsets.

## Demo

**[https://code4fukui.github.io/craftARt-fukui-gourmet/](https://code4fukui.github.io/craftARt-fukui-gourmet/)**

The application automatically detects your device to provide the best experience:
*   **Mobile/Desktop:** A streamlined AR view using Google's `<model-viewer>`.
*   **VR/XR Headsets:** A fully immersive scene built with Three.js and WebXR.

## Features

- **Realistic 3D Models:** View high-quality 3D scans of famous Fukui dishes, including:
    - Yoroppaken's Katsudon (カツ丼)
    - Amidasoba's Oroshi Soba (おろしそば)
    - Hachiban Ramen's Yasai Mararamen (野菜麻辣らーめん)
- **Interactive AR Experience:** Place dishes on any flat surface in your environment. Rotate, scale, and move them with intuitive gestures.
- **Dish Information:** Access descriptions and links to official restaurant pages for each item.
- **Cross-Device Compatibility:** Automatically routes users to a mobile-optimized or a headset-optimized version.

## How to Use

1.  Open the [demo link](https://code4fukui.github.io/craftARt-fukui-gourmet/) in a compatible browser.
2.  Select a dish from the dropdown menu.
3.  **On a mobile device:**
    *   Tap the "ARスタート" (AR Start) button.
    *   Point your camera at a flat, well-lit surface (like a table or floor) until the 3D model appears.
    *   Use touch gestures (pinch to scale, drag to rotate) to interact with the model.
4.  **In a VR/XR headset:**
    *   The immersive experience will load directly.
    *   Use your controllers to interact with the scene.

## Requirements

This application requires a WebXR-enabled device and browser.
- **iOS:** Safari
- **Android:** Chrome
- **VR/XR Headsets:** A WebXR-compatible browser.

## Technology Stack

This application is built with web technologies and does not require any installation.
- **Data:** Model metadata is managed in [`models.csv`](./models.csv).
- **Mobile AR:** Powered by [Google `<model-viewer>`](https://modelviewer.dev/).
- **Headset VR/XR:** Powered by [Three.js](https://threejs.org/), [egxr.js](https://github.com/code4fukui/egxr.js), and the WebXR API.
- **Framework:** Based on the [craftARt-kit](https://github.com/echizencity/craftARt-kit) project.

## License

This project is available under the [MIT License](LICENSE).