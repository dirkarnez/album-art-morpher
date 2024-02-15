[album-art-morpher](https://dirkarnez.github.io/album-art-morpher/)
===================================================================
Converting image of different width x height to standard iTunes 600x600 album image
### Demostration
From: 
- ![](images/original.jpg)   
To:
- ![](images/result.jpg)
### Notes
- in `resize`, `preserveAspectRatio` only works when only `width` or only `height` is specified.
    - https://image-js.github.io/image-js/#imageresize
        - > preserve width/height ratio if only one of them is defined
- background image and source image basically have opposite resize parameters.
