# Story Grid

Turn your camera roll into 9:16 Instagram story collages.

- Groups photos by what's in them (food, scenery, nights out...), their colors and light, and when they were taken.
- Crops every photo around its subject.
- Everything runs in your browser. Photos are never uploaded; they're kept in your browser's storage on your device.

Open the site on your phone and choose **Share > Add to Home Screen** to use it like an app.

Photo recognition uses Apple's MobileCLIP-S0 image model (via Xenova's ONNX export), run with ONNX Runtime Web (MIT). The model weights were re-stored at half precision; see ml/LICENSE-MobileCLIP.txt. Photo dates are read with exifr (MIT).
