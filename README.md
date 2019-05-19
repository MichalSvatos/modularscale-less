# modularscale-less
Simple typography LESS mixin with modularscale

<a href=“#usage”></a>
## Usage
**Input** (with default `@major-third` and `16px`)

    h1 {
      .fontSize(6);
    }
    
    h2 {
      .fontSize(5);
    }
    
**Output**

    h1 {
      font-size: 61.03515625px;
    }
    
    h2 {
      font-size: 48.828125px;
    }

<a href=“#thanks”></a>
## Thanks to ...
[Changing Modular Scale Ratio at Different Breakpoints](https://zellwk.com/blog/changing-modular-scale/) for the formula :) And the [type-scale.com](https://type-scale.com/) and [modularscale.com](https://www.modularscale.com) for the scale.

<a href=“#license”></a>
## License
The code is available under the [MIT license](LICENSE).
