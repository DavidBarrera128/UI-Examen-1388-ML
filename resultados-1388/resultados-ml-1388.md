# Reporte de Análisis de Datos - Pandas

`David Barrera Machine Learning pandas, NC 1388`

## 1. DataFrame Convertido
```text
         Proveedor  Productos  Calificacion
0  Distribuidora X        150           4.5
1      Mayorista Y        230           4.2
2    Importadora Z         80           4.8
3          Local A         45           3.9
4       Nacional B        120           4.6
5         Global C        300           4.7
```

## 2.1 Primeras Filas (head)
```text
         Proveedor  Productos  Calificacion
0  Distribuidora X        150           4.5
1      Mayorista Y        230           4.2
```

## 2.2 Últimas Filas (tail)
```text
    Proveedor  Productos  Calificacion
4  Nacional B        120           4.6
5    Global C        300           4.7
```

## 2.3 Dimensiones (Filas, Columnas)
```text
(6, 3)
```

## 2.4 Tipos de Datos por Columna
```text
Proveedor           str
Productos         int64
Calificacion    float64
dtype: object
```

## 2.5 Información General (info)
```text
<class 'pandas.DataFrame'>
RangeIndex: 6 entries, 0 to 5
Data columns (total 3 columns):
 #   Column        Non-Null Count  Dtype  
---  ------        --------------  -----  
 0   Proveedor     6 non-null      str    
 1   Productos     6 non-null      int64  
 2   Calificacion  6 non-null      float64
dtypes: float64(1), int64(1), str(1)
memory usage: 276.0 bytes

```

## 3. Estadísticas Generales de la Columna 'Productos'
```text
count      6.000000
mean     154.166667
std       95.520504
min       45.000000
25%       90.000000
50%      135.000000
75%      210.000000
max      300.000000
Name: Productos, dtype: float64
```

## 4. Ordenar Ascendente por Productos
```text
         Proveedor  Productos  Calificacion
3          Local A         45           3.9
2    Importadora Z         80           4.8
4       Nacional B        120           4.6
0  Distribuidora X        150           4.5
1      Mayorista Y        230           4.2
5         Global C        300           4.7
```

## 5. Ordenar Descendente por Calificación
```text
         Proveedor  Productos  Calificacion
2    Importadora Z         80           4.8
5         Global C        300           4.7
4       Nacional B        120           4.6
0  Distribuidora X        150           4.5
1      Mayorista Y        230           4.2
3          Local A         45           3.9
```

`David Barrera Machine Learning pandas, NC 1388`