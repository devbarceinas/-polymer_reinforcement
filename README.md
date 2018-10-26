# -polymer_reinforcement
En este repositorio almacenare mis avances y ejercicios de Polymer


# Mixins

deline: p { color: var(--color-for-p, red) }

deline: p { @apply --mixin-name }

use: .objects { --color-for-p: blue; }

use: .objects { --mixin-name: { }}

# Example with Mixins

```html
  <style>
    .user-age {
      color: var(--user-age-p-color. red);
    }
    p {
      @apply --mixim-name;
    }
  </style>
  <p></p>
```

diferencia entres :host y slot
