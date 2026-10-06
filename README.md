IRL-Dex is a browser-based web app that identifies animals through your device's camera in real time. When it spots one, it draws a colored box around the animal, labels it with its name and confidence score, and, once it is more than 50% sure, opens a closable pop-up with a short Wikipedia description.

Features

Live camera detection of animals
Bounding box and name label on each animal
Wikipedia pop-up with a photo, summary, and link when confidence is above 50%
Front and rear camera switching
Runs on-device with TensorFlow.js and COCO-SSD, so no video leaves your phone
Single index.html file with no build step

Use it
Host the file over https (GitHub Pages works), open it in Safari on your iPhone, and tap Start camera. To install it like an app, tap Share, then Add to Home Screen.

Built with HTML, JavaScript, TensorFlow.js, COCO-SSD, and the Wikipedia REST API.
