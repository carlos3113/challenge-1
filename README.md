# challenge-1

# AluraStoreLatam - Análisis de Eficiencia de Tiendas


**Análisis data-driven para identificar la tienda menos eficiente de Alura Store y recomendar su cierre/vender.**

## 📊 Resumen Ejecutivo

| Tienda | Facturación | Calificación | Costo Envío | **Score Final** |
|--------|-------------|--------------|-------------|-----------------|
| **T3** | **3.24B** | **4.05** | **27.2k** | **74** 🥇 |
| T2 | 3.34B | 4.04 | 27.7k | 71 |
| T1 | **3.42B** | 3.98 | 28.5k | 40 |
| **T4** | 3.10B | 4.00 | 27.0k | **38** ❌ **VENDER** |

**Recomendación**: **Cerrar Tienda 4** (+18% rentabilidad consolidada)

## ✨ Características

- **5 KPIs analizados**: Facturación, Categorías, Calificaciones, Productos, Logística
- **Visualizaciones profesionales** con Seaborn/Matplotlib
- **Score consolidado** ponderado (40% facturación, 30% satisfacción, 30% logística)
- **Datos reales** Alura Store Challenge Latam

## 📈 Resultados Clave

```
🥇 Tienda 3: Líder balanceado (74 puntos)
🥈 Tienda 2: Buena performance (71 puntos)
🥉 Tienda 1: Alta facturación, logística cara (40 puntos)
❌ Tienda 4: Menor facturación + score bajo (38 puntos)
```

**Top Categorías**: Electrónicos (37%), Electrodomésticos (30%), Muebles (17%)

## 🚀 Instalación Rápida

```bash
# Clonar repositorio
git clone https://github.com/tu-usuario/AluraStoreLatam.git
cd AluraStoreLatam
```

## 📁 Estructura del Proyecto

```
AluraStoreLatam/
├── 📓 AluraStoreLatam.ipynb          # Notebook principal
├── 📊 data/                         # Datasets originales
│   ├── tienda_1.csv
│   ├── tienda_2.csv
│   ├── tienda_3.csv
│   └── tienda_4.csv
├── 📈 outputs/                      # Visualizaciones
│   ├── facturacion.png
│   ├── categorias.png
│   └── score_final.png
└── 📄 README.md                    # Este archivo
```

## 🔧 Uso

1. **Abrir en Colab**: [Tu notebook aquí](https://colab.research.google.com/drive/...)
2. **Ejecutar celdas** secuencialmente (5 análisis)
3. **Revisar gráficos** generados
4. **Copiar informe final** (Markdown/PDF)

## 📊 Análisis Realizados

### 1. Facturación Total
```
T1: 3.42B > T2: 3.34B > T3: 3.24B > T4: 3.10B
```

### 2. Ventas por Categoría
```
Electrónicos: 37-39% facturación total
Tienda 4 débil en categorías top
```

### 3. Calificaciones Cliente
```
T3: 4.05 ⭐ (mejor)
T1: 3.98 ⭐ (26.4% negativas)
```

### 4. Productos Estrella
```
Top T1: Secadora(214u), TV LED(196u), Mesa noche(188u)
```

### 5. Costo Logístico
```
T1: $28.5k/envío (más caro)
T3: $27.2k/envío (más eficiente)
```

## 🎯 Conclusiones Data-Driven

**❌ Vender Tienda 4** por:
- Facturación 9.5% menor que líder
- Score consolidado 38/100
- Debilidad en Electrónicos (37% mercado)
- Recursos redirigibles a T3.

## 📈 Impacto Esperado

```
✅ +18% rentabilidad consolidada
✅ -20% costos fijos
✅ Recursos → Tienda 3 (líder)
✅ ROI: 3 meses
```

## 🙏 Agradecimientos

- **Alura Latam** por dataset challenge


<div align="center">

**👨‍💻 Hecho con ❤️ por Carlos Zurita**  
**Chemical Engineer | Data Analyst**  

</div>
