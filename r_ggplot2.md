# Color

## Manual discrete scale

Create your new  scale using ```scale_shape_manual(), scale_linetype_manual(),scale_colour_manual()```.

```{r}
plot +
     scale_colour_manual(
          values = c("red", "orange", "green","blue")
          na.value - "grey50"
     )

my_colours <- c(           #Map discrete vars to colours
     label_0 = "red",
     label_1 = "orange",
     label_2 = "green"
     )

plot + scale_colour_manual(values = my_colours)

```
