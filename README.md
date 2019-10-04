# iSpinner

Pure CSS spinner like iOS UIActivityIndicatorView.

## Preview

http://swordray.github.io/ispinner/

## Installation

* Yarn

  ```bash
  yarn add ispinner.css
  ```

* NPM

  ```bash
  npm install -g ispinner.css
  ```

* Bower

  ```bash
  bower install ispinner
  ```

## Usage

1. Include the stylesheet in the document `<head>`.

  ```html
  <link rel="stylesheet" media="all" href="ispinner.prefixed.css">
  ```

2. Add a ispinner element to the document body.

  ```html
  <!-- style: medium -->
  <div class="ispinner">
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
  </div>

  <!-- style: large -->
  <div class="ispinner ispinner-large">
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
    <div class="ispinner-blade"></div>
  </div>
  ```

## License

Copyright © 2019 Jianqiu Xiao <swordray@gmail.com> under The [MIT License](http://opensource.org/licenses/MIT).
