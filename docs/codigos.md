# Códigos em Markdown
Segue abaixo as principais maneiras de destacar códigos em Markdown

---

## Bloco de código com identação
Esse tipo de sintaxe pode ser feita utilizando apenas identação.

**Exemplo:**
```markdown
    function somaNum(a: number, b:number): number {
        return a + b;
    }

    console.log(somaNum(5, 4));
```

**Resultado:**

    function somaNum(a: number, b:number): number {
        return a + b;
    }

    console.log(somaNum(5, 4));

--------

## Bloco de código com três crases
Esse tipo de sintaxe é mais utilizado do que o anterior, visto que oferece maior controle sobre a linguagem do código escrito.

**Exemplo:**
```markdown
    ```typescript
    function apresentacao(nome: string): string {
        return `Olá! Meu nome é ${nome}.`;
    }

    console.log(apresentacao('Cauã'));
    ```
```

**Resultado:**

```typescript
function apresentacao(nome: string): string {
    return `Olá! Meu nome é ${nome}.`;
}

console.log(apresentacao('Cauã'));
```
--------

## Bloco de código em linha
Essa sintaxe é utilizada para exibir um pequeno trecho de código de forma destacada dentro de um texto. Comumente usado para destacar comandos simples.

**Exemplo:**
```markdown
Este é um exemplo de código em linha: `echo 'Olá, Mundo!'`
```

**Resultado:**

Este é um exemplo de código em linha: `echo 'Olá, Mundo!'`