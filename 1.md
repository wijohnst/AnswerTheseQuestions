<h1>Question: What is a 'pure function' in JavaScript?</h1>

<h2>Question Context</h2>
<a href="https://youtu.be/fb3cOMFkEzs">Question inspired by this talk about React Recoil at React Europe 2020</a>

<h1>Answer</h1>
<p>A <b>pure function</b>:</p>
<ol>
  <li>Always returns the same result if the same arguments are passed in. It does not depend on any state, or data, change during a program’s execution. It must only depend on its input arguments.
  <li>[D]oes not produce any observable side effects such as network requests, input and output devices, or data mutation.
</ol>
<a href="https://medium.com/@jamesjefferyuk/javascript-what-are-pure-functions-4d4d5392d49c">Source</a>

<h2>Example</h2>

```javascript
function priceAfterTax(productPrice) {
 return (productPrice * 0.20) + productPrice;
}
```

