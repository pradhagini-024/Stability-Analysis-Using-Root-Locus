# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:



## Procedure:
1. Open MATLAB software
2. Open a new script file.
3. Type the program.
4. Save and Execute the program.
5. Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
6. From the value of K, analyse the stability.

## Program: 
```
num = [1];
den = [1 15 50 0];
sys = tf(num,den)
rlocus(sys)
[k poles] = rlocfind(sys)
```

## Output:
<img width="1919" height="1138" alt="image" src="https://github.com/user-attachments/assets/8d382313-9f7e-46f2-bba6-3e54c2475358" />

## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 757.
