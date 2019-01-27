# Usando VueJS para interagir com a DOM

- O `VueJS` é interpolador (interpretador) que manipula o `DOM` para por fim renderizar e exibir no seu navegador.
- Tudo o que estiver dentro das estruturas: `data` e `methods` podem ser acessiveis dentro da tag `<template>`.
- `ATENÇÃO:` nunca crie em `methods` um método que tenha o mesmo nome que um atributo/variável que foi definida em `data`, pois caso isso ocorra o `Vue` emitirá um conflito e nenhum dos dois dados será interpretado e renderizado no navegador.
- Usando o `v-bind:nome-da-tag` conseguimos fazer uma ligação da instancia do `VueJS` com a sua `TAG` do HTML.
- Com o `v-once` o valor na TAG é atualizado com base na instancia `Vue` apenas uma vez.