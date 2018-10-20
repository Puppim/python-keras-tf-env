README
======

This provides a `requirements.txt` for [pip](https://pip.pypa.io/en/stable/) to install an environment for [Keras](https://keras.io) with a [TensorFlow](https://www.tensorflow.org) backend.

It's recommended to use [virtualenv](https://virtualenv.pypa.io/en/stable/) and Python 3 (tested with 3.6.5).

# Setup

```bash
$ python3 -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```

verify that in `~/.keras/keras.json` the `backend` is set to `tensorflow` and `image_data_format` is set to `channels_last`.
