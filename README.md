# **_Atividade 3_**

Trecho de codigo da classe Hamburger que estende da classe Product

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

[Mais informações](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Classes)

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1200px-Unofficial_JavaScript_logo_2.svg.png"  height="50">
