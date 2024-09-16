# 1. Gráfico de Barras (sns.barplot)

Visualiza la relación entre una variable categórica y una continua, mostrando barras con alturas proporcionales a la media de la variable continua.

"sns.barplot(x='categoria', y='valor', data=df)"

% Argumentos importantes:

x: Variable categórica (columna del DataFrame).
y: Variable numérica (columna del DataFrame).
data: El DataFrame que contiene las variables.
hue: (Opcional) Agrupa los datos según una categoría.
ci: Intervalo de confianza para la media (por defecto, 95%).
