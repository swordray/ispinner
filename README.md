# iSpinner

Pure CSS spinner like iOS UIActivityIndicatorView

## Demo

![Alt text](http://swordray.github.io/ispinner/index.png)

http://swordray.github.io/ispinner/

## Installation

* NPM

  ```bash
  npm install -g ispinner.css
  ```

* Bower

  ```bash
  bower install ispinner
  ```

## Usage

1. Include the stylesheet on your document's `<head>`

  ```html
  <link rel="stylesheet" media="all" href="ispinner.css" />
  ```

2. Add ispinner element to your document's body

  ```html
  <div class="ispinner ispinner--gray ispinner--animating">
    <div class="ispinner__blade"></div>
    <div class="ispinner__blade"></div>
    <div class="ispinner__blade"></div>
    <div class="ispinner__blade"></div>
    <div class="ispinner__blade"></div>
    <div class="ispinner__blade"></div>
    <div class="ispinner__blade"></div>
    <div class="ispinner__blade"></div>
    <div class="ispinner__blade"></div>
    <div class="ispinner__blade"></div>
    <div class="ispinner__blade"></div>
    <div class="ispinner__blade"></div>
  </div>
  ```

3. Setup style by class `ispinner--gray`, `ispinner--white` or `ispinner--white ispinner--large`.

4. Switch animation play state by toggling class `ispinner--animating`.

## License

Copyright © 2016 Jianqiu Xiao <swordray@gmail.com> under The [MIT License](http://opensource.org/licenses/MIT).
