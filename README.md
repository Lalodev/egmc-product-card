# EGMC-Product-Card

Este es un paquete de pruebas de despliegue en npm

### Lalo Dev

## Ejemplo

```
import {
  ProductCard,
  ProductImage,
  ProductTitle,
  ProductButtons,
} from 'egmc-product-card'
```

```
<ProductCard
        product={product}
        initialValues={{
          count: 4,
          maxCount: 10,
        }}
      >
        {({ reset, count, isMaxCountReached, maxCount, increaseBy }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
</ProductCard>

```
