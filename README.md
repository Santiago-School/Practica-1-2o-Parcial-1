# Practica-1-2o-Parcial-1

# se crea una lista con los precios
precios = [43, 57, 92, 20, 37, 5, 9]

# se verifica si la lista no está vacia
if precios:
    # se obtiene el menor precio usando la funcion min
    menorprecio = min(precios)

    # se obtiene el mayor precio usando la funcion max
    mayorprecio = max(precios)
    
    # se muestran los resultados en pantalla
    print("el menor precio es:", menorprecio)
    print("el mayor precio es:", mayorprecio)
else:
    print("la lista de precios esta vacia")
