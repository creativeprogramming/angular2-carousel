# Angular2-Carousel

[![npm version](https://badge.fury.io/js/angular2-carousel.svg)](https://badge.fury.io/js/angular2-carousel) [![npm](https://img.shields.io/badge/build-passed-brightgreen.svg?style=flat)](https://www.npmjs.com/package/angular2-carousel) ![Angular2+](https://img.shields.io/badge/Angular_2+-passing-brightgreen.svg?style=flat) ![Angular2+](https://img.shields.io/badge/Angular_5-success-brightgreen.svg?style=flat) ![licence](https://img.shields.io/badge/licence-MIT-blue.svg?style=flat)

> this is a smart library to create a carousel for angular 2+

## Demo
> demos available [here](https://kappys1.github.io/angular2-carousel)

## Install
You can install the package from our npm package
```
 npm install --save angular2-carousel
```

*check if not install all peer dependencies:*
```
npm install @types/hammerjs
npm install hammerjs
```

## Usage
First tou need to provide the CarouselModule to your desired Module 



```
import {CarouselModule} from "angular2-carousel";

// In your App's module or Custom Module:
@NgModule({
    imports: [
       CarouselModule
    ] 
})
```

*note : if you install library from github, you should import from ``angular2-carousel/dist``*

Now, you can use CarouselModule as follow:

```
<carousel-component >
    <div class="item-carousel">a</div>
    <div class="item-carousel">
        <div class="b">
            <img/>
            .
            .
            .
        </div>
    </div>
    <div class="item-carousel">c</div>
    <div class="item-carousel">d</div>
</carousel-component>
```

**All slides of carousel must have** ``.item-carousel``


#### [Preview](https://embed.plnkr.co/CPWvmndIgpsglCvLChhc/)

## API Documentation
#### you can see [here](https://github.com/kappys1/angular2-carousel/wiki/API-Documentation) or in [web](https://kappys1.github.io/angular2-carousel)

### Author
Alex Marcos Gutierrez
TMTFactory
### License
MIT
