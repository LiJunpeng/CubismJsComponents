﻿# Cubism SDK For JavaScript Components

Welcome to the open components of the *Cubism SDK for JavaScript*. The **the open components are work-in-progress**.
They're not yet feature-complete and their API isn't fixed yet.
While the SDK is meant for *JavaScript*, it's written in *TypeScript*.

If you're interested in why we're releasing the SDK as early access, read on.

If you came here looking for the official *Live2D* homepage, go [Live2D official](http://www.live2d.com/products/cubism3).

If you came here looking for the sample applications of this sdk, go [JS example](https://live2d.github.io/CubismJsComponents/).


## Why Early Access?

With the *Cubism 3 SDK*s we strive to provide the SDKs you need.
We shared the *Unity* SDK from the prototype stage with multiple developers and made sure to reflect their feedback.

For the *JavaScript* SDK we take things one step further by opening the evaluation phase up for everyone,
so it would be great if you could give the SDK a try and provide any feedback through this *GitHub* project.


## Modules

### *LIVE2DCUBISMFRAMEWORK*

This module contains functionality for playing back and blending animations as well as convenience functions for the Cubism Core.
It's located in `./src/live2dcubismframework.ts`.


### *LIVE2DCUBISMPIXI*

This module contains functionality for loading and rendering *Cubism* models with the phantastic *Pixi* library.
It's located in `./src/live2dcubismpixi.ts`.


## Getting Started

No manual is available yet. The best places to start are the example(`./example/src/**/*.*`) and
the completely documented module source files.

To use the modules, you need to link against the *Cubism Core* library.
*We're currently evaluating to distribute Core and modules through npm once they're out of early-access*,
but in the meantime, either link against the [non-permanent official library online](http://live2d.github.io/#js) or
[build the library yourself](https://github.com/Live2D/CubismBindings).


## Contributing

There are many ways to contribute to the project: logging bugs, submitting pull requests on this GitHub, and reporting issues and making suggestions at Live2D Community.

While any form of contributing is greatly appreciated, *suggestions regarding design and API are especially important to us*.


## Discussion Etiquette

Please limit the discussion to English and keep it professional and things on topic.


## Todo

- Add examples?


## License

The license applying to the source code in this project allows you modify all sources without the need to submit any changes you made.
Whenever releasing a product using source code from this project, you just have to make sure that you link your product with the *Cubism Core*.
Refer to [this license](http://live2d.com/eula/live2d-open-software-license-agreement_en.html) for the gritty details.

The assets(character model, image file, sound file, etc...) in this project are licensed individually. Whenever releasing a product using the assets from this project, you just have to make sure that you have met the qualification of license.
Refer to [this license](http://www.live2d.com/eula/live2d-free-material-license-agreement_en.html) and [this guideline](http://docs.live2d.com/kr/cubism-editor-manual/sample-model/) and [detail of guideline](http://docs.live2d.com/cubism-editor-manual/character-guidelines/) for the gritty details.