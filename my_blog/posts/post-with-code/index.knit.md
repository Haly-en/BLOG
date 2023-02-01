---
title: "Para presentaciones con Quarto"
author: "Haly-en"
date: "2023-01-23"
categories: [code, presentaciones]
image: "image.jpg"
---

Comandos y tips para hacer presentaciones con Quarto

# Para texto al centro
``` {{markdown}}
##  {background-image="https://images.unsplash.com/4/madebyvadim.jpg?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1469&q=80" style="margin: auto;"}

. . .

This is a post with executable code.
<h1 style="color:black;background-color: rgba(255,255,255,0.85);padding:5px;line-height:2em; text-align: center; position: absolute; top: 40%; width: 100%;">

Ease of Use VS Full Details

</h1>

```

Para poner un timer en la diapositiva 

``` {{markdown}}

::: {.cell}

:::

Y Para llamarlo dentro de las diapositivas

```{{markdown}}
::: {.cell}
::: {.cell-output-display}
```{=html}
<div class="countdown" id="timer_ac996738" data-update-every="1" data-play-sound="true" tabindex="0" style="right:0;bottom:0;font-size:2em;">
<div class="countdown-controls"><button class="countdown-bump-down">&minus;</button><button class="countdown-bump-up">&plus;</button></div>
<code class="countdown-time"><span class="countdown-digits minutes">01</span><span class="countdown-digits colon">:</span><span class="countdown-digits seconds">00</span></code>
</div>
```
:::
:::
```
