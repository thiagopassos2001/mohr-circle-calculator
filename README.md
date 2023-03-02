# Calculadora - Círculo de Mohr

(Mohr Circle Calculator)

Representação gráfica e esquemática das tensões e direções de ensaios no Círculo de Mohr

* Entrada
```
M = MohrCircle(100,0,30,10)
M.Describe()
```

* Saída
```
---------------Descrição----------------
Tensão (eixo)		Valor	Unidade

--------Dados de Entrada (10 °)---------

Tensão Axial (x)	100	MPa
Tensão Axial (y)	0	MPa
Tensão Cisalhante (x)	30	MPa
        
---------Dados Ajustados (0 °)----------

Tensão Axial (x)	86.72	MPa
Tensão Axial (y)	13.28	MPa
Tensão Cisalhante (x)	45.29	MPa
        
-----------Tensões Principais-----------

Tensão Axial 1 (x)	108.31	MPa
Tensão Axial 2 (y)	-8.31	MPa
Tensão Cisalhante (x)	58.31	MPa
        
------Geometria (Círculo de Mohr)-------
Centro		50.0	MPa
Raio		58.31	MPa
```

* Entrada

```
M.PlotCircle()
```

* Saída

![image](https://user-images.githubusercontent.com/71474825/213896388-0050b56c-b720-4e27-a9b4-2e3d5de7843e.png)

Baseado nas aulas do Prof. Luiz A. C. M. de Aragão Filho na disciplina de Resistência dos Materiais II em Engenharia Civil na Universidade Federal do Ceará (UFC) e no R. C. Hibbeler - 5a edição
