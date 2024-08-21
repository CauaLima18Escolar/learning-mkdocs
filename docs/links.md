# Links em Markdown
Links em markdown é uma tarefa direta e flexível. Segue abaixo um resumo das declarações utilizadas.

---

## Declaração de Links Inline
Uma forma direta e simples de adicionar um link. O texto é adicionado entre '[]' e o link vem em seguida entre '()'.

**Exemplo:**

```markdown
    [O texto fica aqui](O link fica aqui)
```

**Resultado:**

Se quiser voltar para home, [clique aqui](index.md).

---

## Declaração de Links de Referência
Uma forma útil para poupar tempo é utilizar essa sintaxe para reutilizar a mesma URL em vários lugares.

**Exemplo:**
```markdown
    [Texto]: O link fica aqui

    OBS: Agora a palavra 'Texto' carrega a URL e você pode  
    fazer referência ao link em qualquer lugar desde que
    adicione a palavra Texto entre []. [Texto]
```

**Resultado:**
```markdown
    [CauaLima18]: https://github.com/CauaLima18Escolar
```

[CauaLima18Escolar]: https://github.com/CauaLima18Escolar

Acesse meu GitHub Escolar: [CauaLima18Escolar]

---

## Declaração Links Automáticos
Útil e rápido para adicionar URLs. Basta colocar o link diretamente entre colchetes retangulares '<>'

**Exemplo:**
```markdown
<Adicione seu link aqui>
```

**Resultado:**

Link para um site bacana de imagens: <https://unsplash.com>

---

# Declaração de Links para Imagens
É possível criar links que envolvem imagens. A sintaxe é um pouco diferente da dos links comuns. Utiliza-se uma combinação de colchetes e parênteses para combinar uma imagem com um link.

**Exemplo:**
```markdown
[![Descrição da imagem](URL da imagem)](URL do link)

[![Markdown - Logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS2V52XlO-ocN7a93rArEP3Dv1D65r90lisig&s)](https://www.markdownguide.org/cheat-sheet/)
```

**Resultado:**

[![Markdown - Logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS2V52XlO-ocN7a93rArEP3Dv1D65r90lisig&s)](https://www.markdownguide.org/cheat-sheet/)