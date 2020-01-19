# Shrimp data miners
Al menos la mitad del alimentos marinos que consumimos provienen de la acuicultura. Se pronostica un crecimiento del 1.5% al año para los próximos 5 años. En Ecuador, el camarón representa el principal producto de exportación no petrolero. Solamente en 2017, se produjeron 400000 toneladas de camarón lo cual representó un ingreso de aproximadamente 3 mil millones de dólares ( 3% del PIB).

El principal rubro de producción del camarón es la alimentación que representa hasta el 60% de los costos directos. La cantidad diaria de alimento que debe entregarse a una piscina se calcula en función del porcentaje de supervivencia y tamaño de los animales (biomasa) durante el engorde. Para calcular estos factores, los productores camaroneros siguen un procedimiento artesanal que consiste en pescar camarones en diferentes puntos de la piscina para luego pesarlos, contarlos y medirlos. Finalmente, los animales capturados son devueltos a la piscina. Esta operación se realiza semanalmente y representa el 15% del costo de producción.

Si se sobre-estima la cantidad de comida hay un desperdicio de recursos y se desmejora la calidad del agua. Si se subestima la cantidad de comida ocurre una reducción de la tasa de crecimiento de los camarones lo cual aumenta el número de días de engorde. Además las tasas de supervivencia/crecimiento del animal determina el día de cosecha. Seleccionar una fecha que coincida con la muda, una baja de peso o supervivencia ocasiona toda una serie de problemas financieros y logísticos debido a que el precio se negocia con pocos días de antelación.

## Problema
Predecir la cantidad de alimento que se debe proporcionar a una piscina camaronera en base a los datos de supervivencia, crecimiento y calidad de agua registrados en semanas previas.

## Dataset
Se cuenta con un dataset con los registros diarios (1000) de operación de piscinas que incluye:

- Fecha (date)
- Tasa de supervivencia o porcentaje de supervivencia (shrimp_survival_proportion), indica la proporción de animales que se estima que se mantienen con vida en un día.
- Número de camarones (shrimp_population), indica la población estimada de camarones que se mantienen con vida en un día.
- Crecimiento (shrimp_grown), es el peso promedio individual en gramos de un camarón en un día.
- Biomasa (shrimp_biomass), peso en kilogramos de camarones que existen en la piscina en un día, se obtiene multiplicando el número de camarones por el peso individual de un camarón.

## Miners
- Paulette Vázquez
- Karen Bermúdez
- Xavier Figueroa
