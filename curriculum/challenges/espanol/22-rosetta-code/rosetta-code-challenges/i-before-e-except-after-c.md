---
id: 5a23c84252665b21eecc7eb0
title: I antes de E excepto después de C
challengeType: 1
forumTopicId: 302288
dashedName: i-before-e-except-after-c
---

# --description--

**<a href="http://www.rosettacode.org/wiki/I_before_E_except_after_C" target="_blank" rel="noopener noreferrer nofollow">"I before E, except after C"</a>** is a general rule for English language spelling. If one is unsure whether a word is spelled with the digraph `ei` or `ie`, the rhyme suggests that the correct order is `ie` unless the preceding letter is `c`, in which case it may be `ei`.

Utilizando las palabras proporcionadas, verifica si las dos subcláusulas de la frase son plausibles individualmente:

<ol>
  <li>
    <i>"I before E when not preceded by C".</i>
  </li>
  <li>
    <i>"E antes que I cuando esté precedido por C".</i>
  </li>
</ol>

Si ambas subfrases son plausibles, entonces se puede decir que la frase original es plausible.

# --instructions--

Escribe una función que acepte una palabra y comprueba si la palabra sigue esta regla. La función debería devolver verdadero si la palabra sigue la regla y falso si no lo hace.

# --hints--

`IBeforeExceptC` debería ser una función.

```js
assert(typeof IBeforeExceptC == 'function');
```

`IBeforeExceptC("receive")` debería devolver un booleano.

```js
assert(typeof IBeforeExceptC('receive') == 'boolean');
```

`IBeforeExceptC("receive")` debería devolver `true`.

```js
assert.equal(IBeforeExceptC('receive'), true);
```

`IBeforeExceptC("science")` debería devolver `false`.

```js
assert.equal(IBeforeExceptC('science'), false);
```

`IBeforeExceptC("imperceivable")` debería devolver `true`.

```js
assert.equal(IBeforeExceptC('imperceivable'), true);
```

`IBeforeExceptC("inconceivable")` debería devolver `true`.

```js
assert.equal(IBeforeExceptC('inconceivable'), true);
```

`IBeforeExceptC("insufficient")` debería devolver `false`.

```js
assert.equal(IBeforeExceptC('insufficient'), false);
```

`IBeforeExceptC("omniscient")` debería devolver `false`.

```js
assert.equal(IBeforeExceptC('omniscient'), false);
```

# --seed--

## --seed-contents--

```js
function IBeforeExceptC(word) {

}
```

# --solutions--

```js
function IBeforeExceptC(word)
{
    if(word.indexOf("c")==-1 && word.indexOf("ie")!=-1)
        return true;
    else if(word.indexOf("cei")!=-1)
        return true;
    return false;
}
```
