---
id: 5900f4dd1000cf542c50ffef
title: '问题368：类似肯珀纳的系列'
challengeType: 1
forumTopicId: 302029
dashedName: problem-368-a-kempner-like-series
---

# --description--

The harmonic series $1 + \dfrac{1}{2} + \dfrac{1}{3} + \dfrac{1}{4} + \ldots$ is well known to be divergent.

然而，如果我们在这个系列中省略了分母中有9个的每个项，则该系列显着地收敛到大约22.9206766193。 这种改进的谐波系列称为肯普纳系列。

现在让我们通过省略分母具有3个或更多相等连续数字的每个项的谐波系列来考虑另一个修正的谐波系列。 可以验证在谐波系列的前1200个项中，仅省略20个项。

These 20 omitted terms are:

$$\dfrac{1}{111}, \dfrac{1}{222}, \dfrac{1}{333}, \dfrac{1}{444}, \dfrac{1}{555}, \dfrac{1}{666}, \dfrac{1}{777}, \dfrac{1}{888}, \dfrac{1}{999}, \dfrac{1}{1000}, \dfrac{1}{1110}, \\\\
\dfrac{1}{1111}, \dfrac{1}{1112}, \dfrac{1}{1113}, \dfrac{1}{1114}, \dfrac{1}{1115}, \dfrac{1}{1116}, \dfrac{1}{1117}, \dfrac{1}{1118}, \dfrac{1}{1119}$$

This series converges as well.

Find the value the series converges to. Give your answer rounded to 10 digits behind the decimal point.

# --hints--

`kempnerLikeSeries()` should return `253.6135092068`.

```js
assert.strictEqual(kempnerLikeSeries(), 253.6135092068);
```

# --seed--

## --seed-contents--

```js
function kempnerLikeSeries() {

  return true;
}

kempnerLikeSeries();
```

# --solutions--

```js
// solution required
```
