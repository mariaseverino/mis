# **_Atividade 3_**

Trecho de codigo da classe Hamburger que extende da classe Product

```javascript
import { Product } from "./Product";

export class Hamburger extends Product {
    public ingredients: string;
    public sauce: string;

    constructor(
        name: string,
        price: number,
        ingredients: string,
        sauce: string,
        id?: string
    ) {
        super(name, price, id);
        this.ingredients = ingredients;
        this.sauce = sauce;
    }
}
```

### Classes

-   Constructor
-   Extensões de classes
-   Acesso a variaveis
