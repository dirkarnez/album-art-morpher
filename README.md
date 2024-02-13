[album-art-morpher](https://dirkarnez.github.io/album-art-morpher/)
===================================================================
### Notes
- in `resize`, `preserveAspectRatio` only works when only `width` or only `height` is specified.
    - https://image-js.github.io/image-js/#imageresize
        - > preserve width/height ratio if only one of them is defined
- background image and source image basically have opposite resize parameters.