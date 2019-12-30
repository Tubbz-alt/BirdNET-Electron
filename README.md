<b>This repo is currently under development.</b>

# BirdNET-Electron

Electron app for sound file analysis with BirdNET.

Author: Stefan Kahl

Contact: stefan.kahl@cs.tu-chemnitz.de

Website: https://birdnet.cornell.edu/

Please cite as (PDF coming soon):

```
@phdthesis{kahl2019identifying,
  title={{Identifying Birds by Sound: Large-scale Acoustic Event Recognition for Avian Activity Monitoring}},
  author={Kahl, Stefan},
  year={2019},
  school={Chemnitz University of Technology}
}
```

## Application setup

First, clone the project and install all dependencies:

```
git clone https://github.com/kahst/BirdNET-Electron.git
cd BirdNET-Electron
npm install
```

Next, launch the app with:

```
npm start
```

## Development setup

Setting up the project requires <i>Node.js</i>, which we need to install first.

After that, we can initialize the source directory with:

```
npm init
```

Follow the prompt to setup ```package.json```.

Now, we need to install <i>electron</I> with:

```
npm install --save-dev electron
```

BirdNET requires Tensorflow.js which we install with:

```
npm install @tensorflow/tfjs
```

This app also needs some additional packages that we have to install.

```
npm i audio-loader
npm i audio-resampler
npm i array-normalize
```