# Fuciones Anualidades Anticipadas

```
source("https://raw.githubusercontent.com/AngelReyesF/Fuciones-Anualidades-Anticipadas/refs/heads/main/FuncionesAnualidadesAnticipadas.R")
```

**FV: Valor Futuro (VF)
PV: Valor Actual (VA)
A: Anualidad o Pago periódico (A)
r: Tasa de interés del periodo (r)
n: Número de pagos o plazo (n)**

# Valor Futuro (VF)
```
Vfuturo = round(VF(A = 500, r = 0.05706, n = 10))
```

# Anualidad (A)
 ```
Anualidad = round(A(VF = 6500, r = 0.05706, n = 10))
```

# Número de Pagos (n)
 ```
NPagos = round(n(VF = 6500, r = 0.05706, A = 500))
```

# tasa de interes (r) VF
```
tasa = round(r(VF = 6500, A = 500, n = 10),4)
```







# Valor Actual (VA)
```
V_actual = round(VA(A = 400, r = 0.02504, n = 10))
```

# Anualidad (A)
 ```
Anualidad2 = round(A_(VA = 3500, r =  0.02504, n = 10))
```

# Número de Pagos (n)
 ```
NPagos2 = round(n_(VA = 3500, r =  0.02504, A = 400))
```

# tasa de interes VA
```
tasa2 = round(r_(VA = 3500, A = 400, n = 10),4)
```
