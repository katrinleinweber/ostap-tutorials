# sPlot

Using [sPlot](https://doi.org/10.1016/j.nima.2005.08.106) is   rather  trivial in ostap:
```python
dataset = ...
model   = Fit1D ( signal = ... , backgrund = ... ) 
model.fitTo ( dataset )
print datatset   
model.sPlot ( dataset )  ## <--- HERE 
print datatset           ## <--- note appearence of new variables 
```
