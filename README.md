# Vosk Listener <a href="https://www.ohioiot.com"><img src="https://www.ohioiot.com/logo_150.jpg" width="40" ></a>
#### [(back to the Voice Controls organization page)](https://github.com/OhioIoT-Voice-Controls)

```
python -m venv venv
source venv/Scripts/activate
pip install -r requirements.txt
./+run
```

This code was generated in the linked YouTube video about making a speech-to-text listener on a Raspberry Pi with a USB mic.  See more at:  [Offline Voice Control](https://youtu.be/oKQ9xvL7ptM)

When I made the video, I manually downloaded the Vosk library and then used it.  It turns out that if you change `model = Model("vosk-model-small-en-us-0.15")` to `model = Model(model_name="vosk-model-small-en-us-0.15")`, it will download the library for you automatically.



For the same version of this code, but with scripts to build it in a Docker container image, check out out [Vosk Listener w/Docker](https://github.com/OhioIoT-Voice-Controls/Vosk-Listener-With-Docker).

## About
<a href="https://www.ohioiot.com"><img src="https://www.ohioiot.com/logo_150.jpg" width="40" ></a>

*OhioIoT is an IoT platform designed for small-scale IoT projects.  For more, check out our website at [www.OhioIoT.com](https://www.ohioiot.com).*
