# iSpinner

Pure CSS spinner like UIActivityIndicatorView

## Demo

![Alt text](http://swordray.github.io/ispinner/index.png)

http://swordray.github.io/ispinner/

## Installation

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
  <div class="ispinner gray animating">
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

3. Setup style by class `gray`, `white` or `white large`.

4. Switch animation play state by toggling class `animating`.

## License

Copyright © 2015 Jianqiu Xiao <swordray@gmail.com> under The [MIT License](http://opensource.org/licenses/MIT).
