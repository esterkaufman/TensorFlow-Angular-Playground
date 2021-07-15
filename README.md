# tensor-flow-angular

## When Google & JS & AI Meet
The process of machine learning consists of:
Training - which is the training of a particular model,
Loading - which is the implementation of the model.

The training is commonly implemented with the TensorFlow library written in c.
Just using TensorFlow in js was quite heavy and complicated so Google released TensorFlow.js

Which is actually a complete rewrite of TensorFlow to js.

TensorFlow.js relies on WebGl technology that runs all the calculations on the GPU instead of on the browser and thus the capability of a regular computer is obtained.

### Trained models for image classifiers in js: 
https://teachablemachine.withgoogle.com/train/image
https://microsoft.github.io/onnxjs-demo/#/squeezenet

### Training model in JS: TensorFlow.js

[Link] https://www.youtube.com/watch?v=pbCExciEbrc

### Collection of TensorFlow.js projects, tutorials, videos, and more.
Can reach out to this repo's owner to put this project on the list.

https://github.com/tensorflow/tfjs/blob/master/GALLERY.md

### More models as MobileNet, pre-trained TensorFlow.js models that can be used in any project out of the box.
https://www.tensorflow.org/js/models

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.2.

## Deployment (GitHub Pages)

View the website in: `https://esterkaufman.github.io/TensorFlow.js-Angular-Playground/`
To deploy your changes, run this locally: `ng deploy --base-href=https://esterkaufman.github.io/TensorFlow.js-Angular-Playground/`. 
Or `npm run deploy`
Or run the following commands: 
`ng build --prod --base-href=https://esterkaufman.github.io/TensorFlow.js-Angular-Playground/ --output-path docs`
`git config --global http.sslVerify false`
`ngh`
`git config --global http.sslVerify true`
This will deploy the app automatically as a github page.


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

