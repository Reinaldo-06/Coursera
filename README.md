### 1. **Gráfico de Barras (`sns.barplot`)**
   Visualiza la relación entre una variable categórica y una continua, mostrando barras con alturas proporcionales a la media de la variable continua.

   **Código:**
   ```python
   sns.barplot(x='categoria', y='valor', data=df)
   ```

   **Argumentos importantes:**
   - `x`: Variable categórica (columna del DataFrame).
   - `y`: Variable numérica (columna del DataFrame).
   - `data`: El DataFrame que contiene las variables.
   - `hue`: (Opcional) Agrupa los datos según una categoría.
   - `ci`: Intervalo de confianza para la media (por defecto, 95%).

### 2. **Gráfico de Dispersión (`sns.scatterplot`)**
   Muestra la relación entre dos variables numéricas, útil para detectar patrones o correlaciones.

   **Código:**
   ```python
   sns.scatterplot(x='variable_x', y='variable_y', data=df)
   ```

   **Argumentos importantes:**
   - `x`: Variable en el eje X.
   - `y`: Variable en el eje Y.
   - `data`: El DataFrame que contiene las variables.
   - `hue`: (Opcional) Agrupa los puntos de datos por color según una variable categórica.
   - `size`: (Opcional) Ajusta el tamaño de los puntos según una variable numérica.
   - `style`: (Opcional) Diferencia puntos usando diferentes estilos (e.g., círculos, cruces).

### 3. **Gráfico de Líneas (`sns.lineplot`)**
   Muestra la relación entre dos variables continuas a lo largo del tiempo o de una secuencia.

   **Código:**
   ```python
   sns.lineplot(x='tiempo', y='valor', data=df)
   ```

   **Argumentos importantes:**
   - `x`: Variable del eje X (usualmente tiempo o secuencia).
   - `y`: Variable del eje Y.
   - `data`: El DataFrame con las variables.
   - `hue`: (Opcional) Diferencia las líneas por colores basados en una variable categórica.

### 4. **Gráfico de Caja (Boxplot) (`sns.boxplot`)**
   Muestra la distribución de una variable numérica y destaca los outliers (valores atípicos).

   **Código:**
   ```python
   sns.boxplot(x='categoria', y='valor', data=df)
   ```

   **Argumentos importantes:**
   - `x`: Variable categórica (opcional).
   - `y`: Variable numérica.
   - `data`: El DataFrame que contiene los datos.
   - `hue`: (Opcional) Agrupa los datos por color.

### 5. **Matriz de Dispersión (`sns.pairplot`)**
   Muestra gráficos de dispersión y distribuciones para varias variables a la vez.

   **Código:**
   ```python
   sns.pairplot(data=df)
   ```

   **Argumentos importantes:**
   - `data`: El DataFrame que contiene las variables.
   - `hue`: (Opcional) Diferencia puntos por color según una variable categórica.
   - `kind`: Tipo de gráfico para las variables continuas (por ejemplo, `'reg'` para incluir una regresión).

### 6. **Mapa de Calor (`sns.heatmap`)**
   Muestra una tabla con colores que representan los valores de una matriz o DataFrame.

   **Código:**
   ```python
   sns.heatmap(data=matriz, annot=True)
   ```

   **Argumentos importantes:**
   - `data`: La matriz o DataFrame a visualizar.
   - `annot`: Muestra los valores dentro de las celdas.
   - `cmap`: El esquema de colores (por ejemplo, `'coolwarm'`, `'viridis'`).

### 7. **Histograma (`sns.histplot`)**
   Muestra la distribución de una variable numérica agrupando los valores en intervalos (bins).

   **Código:**
   ```python
   sns.histplot(data=df, x='valor', bins=30)
   ```

   **Argumentos importantes:**
   - `x`: Variable numérica a visualizar.
   - `data`: El DataFrame que contiene los datos.
   - `bins`: Número de intervalos.
   - `hue`: (Opcional) Agrupa los datos en función de una variable categórica.

### 8. **Gráfico de Densidad (`sns.kdeplot`)**
   Muestra una estimación de la distribución de una variable continua, suavizada.

   **Código:**
   ```python
   sns.kdeplot(x='valor', data=df)
   ```

   **Argumentos importantes:**
   - `x`: Variable numérica.
   - `data`: El DataFrame con los datos.
   - `shade`: (Opcional) Rellena el área bajo la curva.

### 9. **Gráfico de violín (`sns.violinplot`)**
   Combina el boxplot y el gráfico de densidad para mostrar la distribución de una variable.

   **Código:**
   ```python
   sns.violinplot(x='categoria', y='valor', data=df)
   ```

   **Argumentos importantes:**
   - `x`: Variable categórica.
   - `y`: Variable numérica.
   - `data`: El DataFrame.
   - `hue`: (Opcional) Agrupa los datos en función de una variable categórica.

### 10. **Gráfico de Regresión (`sns.regplot`)**
   Muestra una regresión lineal entre dos variables continuas, incluyendo la línea de mejor ajuste.

   **Código:**
   ```python
   sns.regplot(x='variable_x', y='variable_y', data=df)
   ```

   **Argumentos importantes:**
   - `x`: Variable en el eje X.
   - `y`: Variable en el eje Y.
   - `data`: El DataFrame que contiene las variables.
   - `ci`: (Opcional) Intervalo de confianza para la regresión.
   - `order`: (Opcional) Ajusta un polinomio en lugar de una línea recta.

### 11. **Gráfico de Enjambre (`sns.swarmplot`)**
   Muestra la distribución de una variable categórica y continua sin superponer puntos.

   **Código:**
   ```python
   sns.swarmplot(x='categoria', y='valor', data=df)
   ```

   **Argumentos importantes:**
   - `x`: Variable categórica.
   - `y`: Variable numérica.
   - `data`: El DataFrame.
   - `hue`: (Opcional) Agrupa los datos por color.

### Resumen:
Los gráficos en Seaborn son altamente personalizables y la mayoría de ellos utilizan los mismos argumentos clave: `x`, `y`, `data`, `hue`, entre otros, para organizar los datos. Cada gráfico puede tener propiedades adicionales específicas para personalizar aún más la visualización.
