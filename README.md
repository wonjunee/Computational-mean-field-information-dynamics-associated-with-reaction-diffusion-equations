# MFG-reaction-diffusion

Codes from the paper "Computational mean-field information dynamics associated with reaction-diffusion equations" [[1]](#1).

Paper link an ArXiv: [link](https://arxiv.org/pdf/2107.11501.pdf)


## Installation on Mac

Type the following lines in the terminal.
```
git clone https://github.com/wonjunee/MFG-reaction-diffusion/
cd MFG-reaction-diffusion
bash setup.sh
```

## Running the code

The following code will run the numerical experiment 1 in the paper with V_1(u) = u and V_2(u) = u.
```
./MFG 32 32 16 0.05 0.1 -1e-9 2000 100
```

Once the above experiment is done, type the following codes to create figures and videos.
```
python plot-contour.py
```


## References
<a id="1">[1]</a> 
Wuchen Li, Wonjun Lee, Stanley Osher (2022). 
Computational mean-field information dynamics associated with reaction-diffusion equations
Journal of Computational Physics 466 (2022): 111409.
