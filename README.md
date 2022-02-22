<h1 align="center">
  <b>Optimization</b><br> 
  <b>Jax - Julia</b><br> 
</h1>

<p align="center">
      <a href="https://www.python.org/">
        <img src="https://img.shields.io/badge/Python-3.8-ff69b4.svg" /></a>
       <a href= "https://fluxml.ai/">
        <img src="https://img.shields.io/badge/Flux-v0.12.8-red" /></a>
       <a href= "https://github.com/google/jax">
        <img src="https://img.shields.io/badge/Jax-v0.1.75-yellow" /></a>
       <a href= "https://github.com/BeeGass/Optimization/blob/main/LICENSE">
        <img src="https://img.shields.io/badge/license-Apache2.0-blue.svg" /></a>
         <a href= "http://twitter.com/intent/tweet?text=Optimization:%20A%20Collection%20Of%20Optimization%20Techniques%20Written%20In%20Julia%20And%20Jax%3A&url=https://github.com/BeeGass/Optimization">
        <img src="https://img.shields.io/twitter/url/https/shields.io.svg?style=social" /></a>

</p>

A collection of optimization techniques I have implemented in [jax](https://github.com/google/jax) and [flux](https://fluxml.ai/) with particular effort put into readability and reproducibility. 

## Python 
### Requirements For Jax
- Python >= 3.8
- jax

#### Installation
```
$ git clone https://github.com/BeeGass/Readable-Optimization.git
```

#### Usage
```
$ cd Readable-Optimization/vae-jax
$ python main.py 
```

## Julia
### Requirements For Flux
- TODO
- TODO

#### Usage
```
$ cd Readable-Optimization/vae-flux
$ # TBA 
```
--- 

**Config File Template**
```yaml
TBA
```

----
<h2 align="center">
  <b>First Order Results</b><br>
</h2>


| Model                                   | PyTorch | Jax/Flax |  Flux   | Config  | Paper    | Animations | Samples |
|:--------------------------------------- |:-------:|:--------:|:-------:|:-------:|:-------- |:----------:|:-------:|
| Gradient Descent                        | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Stochastic Gradient Descent             | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Batch Gradient Descent                  | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Mini-Batch Gradient Descent             | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| SGD w/ Momentum                         | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Nesterov's Gradient Acceleration        | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| AdaGrad(Adaptive Gradient Descent)      | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| AdaDelta                                | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| RMS-Prop (Root Mean Square Propagation) | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Adam(Adaptive Moment Estimation)        | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Adamw                                   | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |

----
<h2 align="center">
  <b>Second Order Results</b><br>
</h2>


| Model                                   | PyTorch | Jax/Flax |  Flux   | Config  | Paper    | Animations | Samples |
|:--------------------------------------- |:-------:|:--------:|:-------:|:-------:|:-------- |:----------:|:-------:|
| Newton's Method                         | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Secant Method                           | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Davidson-Fletcher-Powell (DFP)          | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Broyden-Fletcher-Goldfarb-Shanno (BFGS) | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Limited-memory BFGS (L-BFGS)            | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Newton-Raphson                          | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Levenberg-Marquardt                     | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Powell's method                         | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Steepest Descent                        | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Truncated Newton                        | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |
| Fletcher-Reeves                         | &#9744; | &#9744;  | &#9744; | &#9744; | [Link]() |  **TBA**   | **TBA** |

---
### Citation
```bib
@software{B_Gass_Optimization_2022,
author = {B Gass, B Gass},
doi = {10.5281/zenodo.1234},
month = {1},
title = {{Readable-Optimization}},
url = {https://github.com/BeeGass/Optimization},
version = {1.0.0},
year = {2022}
}
```
