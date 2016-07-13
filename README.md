# stuff

## resolution doubling

- x_o:  object position giving rise to the highest probability to detect a photon at x_d
- x_d: detected photon position
- s: width of excitation and emission psf = 1 
- x=0: beam position

```
excitation_amplitude * emission_psf = 
exp(-(0-x_o)^2) * exp(-(x_o-x_d)^2)
```

for which x_o becomes above expression maximal:

```
exp(-(0-x_o)^2) * exp(-(x_o-x_d)^2) =
exp(-x_o^2-x_o^2+2*x_o*x_d-x_d^2) =
exp(-2*x_o^2+2*x_o*x_d-x_d^2)
```
```
-2*x_o^2+2*x_o*x_d-x_d^2 = maximal <=>
-4*x_o + 2*x_d = 0 <=>
x_o = x_d/2 q.e.d.
```
