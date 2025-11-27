# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![94f87b28-e918-4ea7-aaf9-59aa834ab43c](https://github.com/user-attachments/assets/aaef2cc2-1357-4988-8a31-fb7899afc3fd)
![4f677a3b-460e-4508-bd69-20b520e6aa2c](https://github.com/user-attachments/assets/95514f02-4ccc-4f26-a6f2-c1a7bf684382)
![bb07ae8b-b614-492a-9baa-0eb50a4075ad](https://github.com/user-attachments/assets/94b8e280-f4a0-4bd7-a258-f85386ac415e)
![0aaf6cd4-dda7-4e61-a708-af76aaf2083c](https://github.com/user-attachments/assets/50e31cc8-9e70-4865-a72e-2cb8281bc649)



## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 

```
num=[1]
den=[1 15 50 0]
sys=tf(num,den)
rlocus(sys)
[k poles]=rlocfind(sys)
```

## Output:

<img width="699" height="626" alt="image" src="https://github.com/user-attachments/assets/efb210b9-801d-4a1a-b603-66c56093cb8b" />

## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 744.551 .
