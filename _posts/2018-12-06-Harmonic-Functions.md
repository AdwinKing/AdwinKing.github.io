---
layout: post
title: Introduction to Harmonic Functions
---

<style TYPE="text/css">
code.has-jax {font: inherit; font-size: 100%; background: inherit; border: inherit;}
</style>
<script type="text/x-mathjax-config">
MathJax.Hub.Config({
    tex2jax: {
        inlineMath: [['$','$'], ['\\(','\\)']],
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'] // removed 'code' entry
    }
});
MathJax.Hub.Queue(function() {
    var all = MathJax.Hub.getAllJax(), i;
    for(i = 0; i < all.length; i += 1) {
        all[i].SourceElement().parentNode.className += ' has-jax';
    }
});
</script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-AMS_HTML-full"></script>

---

## Definition
> Harmonic functions are f:R^2->R which satisfy Laplace's equation.

## Properties
> 1. Real part and imaginary part of analytic functions are harmonic functions(Proved by Cauchy-Riemann equations or ...)
> 2. If u(x, y) is harmonic on a simply connected region A, then u is the real part of some analytic function.
> 3. If u(x, y) is harmonic, then u has the mean value property.
> 4. If u(x, y) is harmonic, then u follows the maximum principle.(3 && 4 are similar to holomorphic functions)
> 5. Gradients of real part and imaginary part of analytic functions are orthogonal.
