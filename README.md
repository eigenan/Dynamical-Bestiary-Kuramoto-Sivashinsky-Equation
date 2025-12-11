# Dynamical-Bestiary-Kuramoto-Sivashinsky-Equation
Python notebooks for the 2-dimensional Kuramoto Sivashinsky equation

$$
\partial_t u = -\nabla^2 u - \epsilon \nabla^4 u - \frac{\lambda}{2} |\nabla u|^2
$$

on a periodic square domain.

## 1. Baby continuation Scheme

<img width="1189" height="726" alt="ks_cont" src="https://github.com/user-attachments/assets/6699cf45-2dac-40e6-909e-b7d8d874b5fa" />

<img width="790" height="490" alt="ks_b" src="https://github.com/user-attachments/assets/b39f7872-be78-4a08-8162-31bac868f72a" />

## 2. Direct simulation with implicit Euler

https://github.com/user-attachments/assets/cc22a16d-bce0-4e37-ad52-1274ab9cb691

## 3. 0-mean version

Different versions of the above two numerical scheme that enforces the zero mean on the solution to resolve the drifting amplitude.
