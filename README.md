# FractionPainter

FractionPainter is a jQuery plugin that draws fractions with circles. It is a useful tool to explain the meaning of *Fraction*.

## Getting started

Let's paint $\frac{10}{3}$ 🎨🖌️

1. Include Jquery

2. Download [jquery.fractionpainter.js file](./jquery.fractionpainter.js) and include in your code
   
   ```html
   <script src="jquery.fractionpainter.js"></script>
   ```

3. Add the element where you want the fraction appear: a div or a span
   
   ```html
   <div id="fraction_container1"></div>
   ```

4. Create the instance of the fractionPainter
   
   ```javascript
   jQuery(document).ready(function(){ 
    $("#fraction_container1").fractionPainter({width: 800, height: 450, numerator: 10, denominator: 3});
   });
   ```

and that's all (see [example.html](./example.html)):

![fraction_10_thirds](./readme_example.png)

## Options

FractionPainter has some options that can be set when the instance is created.

- `numerator` (default is 1)

- `denominator` (default is 2)

- `width` set the canvas width

- `height` set the canvas height

## License

See [LICENSE](./LICENSE)
