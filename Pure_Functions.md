<h1>Question: What is a 'pure function' in JavaScript?</h1>
<a href="https://youtu.be/fb3cOMFkEzs">Question inspired by this talk about React Recoil at React Europe 2020</a>

<h1>Answer</h1>
<p>A <b>pure function</b>:</p>
<ol>
  <li>Always returns the same result if the same arguments are passed in. It does not depend on any state, or data, change during a program’s execution. It must only depend on its input arguments.
  <li>The function does not produce any observable side effects such as network requests, input and output devices, or data mutation.
</ol>

<h2>Example</h2>

```javascript
function priceAfterTax(productPrice) {
 return (productPrice * 0.20) + productPrice;
}
```

