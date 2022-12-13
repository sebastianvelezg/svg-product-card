# SVG-Product-Card

este es un paquete de pruebas de despliegue en NPM

### Sebastian Velez Galeano

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'svg-product-card'

```

```
<ProductCard
    product={product}
    className="bg-dark text-white"
    initialValues={{
        count: 0,
        maxCount: 10,
    }}
    >
    {({ reset, isMaxCountReached, maxCount, count, increaseBy }) => (
        <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
        </>
    )}
</ProductCard>

```
