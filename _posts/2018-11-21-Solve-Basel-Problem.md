---
layout: post
title: Solve Basel problum
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

## Description of Basel problem
>evaluate $\sum_{n=1}^{\infty} \frac{1}{n^2}$

### Solution by Fourier series


>By Fourier series, we have $\| x \| =\frac{\pi}{2}+\sum_{n=odd}\frac{-2 e^{inx}}{\pi n^2}$.

>Let $x = 0$, then $\sum_{n=odd\geq 1}^{\infty} \frac{1}{n^2}=\frac{\pi^2}{2}$.

>Again by Fourier series, we have $x^2=\frac{\pi^2}{3}+\sum_{n\neq0} \frac{2(-1)^ne^{inx}}{n^2}$.

>Let $x=0$, then $0=\frac{\pi^2}{3}+\sum_{odd} \frac{-2}{n^2} + \sum_{even-\\{0\\}} \frac{2}{n^2}$.

>Finally, $\sum_{n=1}^{\infty}\frac{1}{n^2}=\sum_{n=odd\geq 1} \frac{1}{n^2}+\sum_{n=even \geq 1}\frac{1}{n^2}=\frac{\pi^2}{6}$.

>This method can be generalized to evaluate $\sum_{n=1}^{\infty} \frac{1}{n^k}~by~ choosing~f(x)=x^k,~where~ k \in N,~and~k \geq 3$.
