# AF-Product-Card

Estees un paquete de pruebas de despliegue en NPM

### AFG

##Ejemplo 

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} form '';
```

```
    <ProductCard 
        product={product1} 
        initialValues={{
            count: 4,
            maxCount: 10,
        }}>
        {
            ({reset, count,isMaxCounterReached, increaseBy, maxCount}) =>(
                <>                    
                    <ProductCard.Image  />
                    <ProductCard.Title />
                    <ProductCard.Buttons  />
                </>
            )
        }

    </ProductCard>

```