# Floats in Cycobol 

## FLOAT-POINT NUMBERS 

### Default FP: 
**Cycobol uses IBM-370 FP standards <u>by default</u>**

- 32 Bit Float (keyword: `float`) -: COMP-1,
- 64 Bit Float (keyword: `double`) -: COMP-2

-------

### Special FP: 
**Cycobol can also use IEEE-FLOAT standards**
`CALL <IEEE_FLOAT> FROM <STD>` - this import changes what the keywords `float` and `double` mean
under IEEE-FLOAT rules: 
`float` -: 32 Bit Float, 
`double` -: 64 Bit Float

*note: You would have to rebuild the project in order to switch back to the default*
-------
