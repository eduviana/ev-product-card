# EV-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Eduardo Viana

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons } from 'ev-product-card';
```

```
 <ProductCard
        product={product}
        initialValues={{
          count: 6,
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
