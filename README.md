
<!-- Automatically generated, do not change by hand. Use docs/script/make.py instead. -->

# `morethemes`: more themes for matplotlib

`morethemes` provides themes for [matplotlib](https://matplotlib.org/). More themes, better plots, one line of code.

[Documentation site](https://josephbarbierdarnal.github.io/morethemes/)



<br>

## Installation

```bash
pip install morethemes
```

Don't want to add `morethemes` as a dependency? You can use the `mt.get_rcparams(...)` function to retrieve the rcParams for a given theme. Use it once to obtain the rcParams, then apply them using `plt.rcParams.update(mt.get_rcparams("theme_name"))`. You can also browse the [source code](https://github.com/JosephBARBIERDARNAL/morethemes/blob/main/morethemes/themes.py) to access the rcParams directly.

    
<br>

## Themes

`morethemes` offers 10 themes at the moment:
    
### Darker

```python
import morethemes as mt
mt.set_theme("darker")
```

[![](https://raw.githubusercontent.com/JosephBARBIERDARNAL/morethemes/refs/heads/main/docs/img/darker.png)](https://josephbarbierdarnal.github.io/morethemes/)

    
### Yellowish

```python
import morethemes as mt
mt.set_theme("yellowish")
```

[![](https://raw.githubusercontent.com/JosephBARBIERDARNAL/morethemes/refs/heads/main/docs/img/yellowish.png)](https://josephbarbierdarnal.github.io/morethemes/)

    
### Urban

```python
import morethemes as mt
mt.set_theme("urban")
```

[![](https://raw.githubusercontent.com/JosephBARBIERDARNAL/morethemes/refs/heads/main/docs/img/urban.png)](https://josephbarbierdarnal.github.io/morethemes/)

    
### WSJ

```python
import morethemes as mt
mt.set_theme("wsj")
```

[![](https://raw.githubusercontent.com/JosephBARBIERDARNAL/morethemes/refs/heads/main/docs/img/wsj.png)](https://josephbarbierdarnal.github.io/morethemes/)

    
### Economist

```python
import morethemes as mt
mt.set_theme("economist")
```

[![](https://raw.githubusercontent.com/JosephBARBIERDARNAL/morethemes/refs/heads/main/docs/img/economist.png)](https://josephbarbierdarnal.github.io/morethemes/)

    
### Minimal

```python
import morethemes as mt
mt.set_theme("minimal")
```

[![](https://raw.githubusercontent.com/JosephBARBIERDARNAL/morethemes/refs/heads/main/docs/img/minimal.png)](https://josephbarbierdarnal.github.io/morethemes/)

    
### Lex

```python
import morethemes as mt
mt.set_theme("lex")
```

[![](https://raw.githubusercontent.com/JosephBARBIERDARNAL/morethemes/refs/heads/main/docs/img/lex.png)](https://josephbarbierdarnal.github.io/morethemes/)

    
### Retro

```python
import morethemes as mt
mt.set_theme("retro")
```

[![](https://raw.githubusercontent.com/JosephBARBIERDARNAL/morethemes/refs/heads/main/docs/img/retro.png)](https://josephbarbierdarnal.github.io/morethemes/)

    
### Nature

```python
import morethemes as mt
mt.set_theme("nature")
```

[![](https://raw.githubusercontent.com/JosephBARBIERDARNAL/morethemes/refs/heads/main/docs/img/nature.png)](https://josephbarbierdarnal.github.io/morethemes/)

    
### Monoblue

```python
import morethemes as mt
mt.set_theme("monoblue")
```

[![](https://raw.githubusercontent.com/JosephBARBIERDARNAL/morethemes/refs/heads/main/docs/img/monoblue.png)](https://josephbarbierdarnal.github.io/morethemes/)

    

<br>

## Learn matplotlib

This project is sponsored by [Matplotlib Journey](https://www.matplotlib-journey.com/), an online course designed to make you a matplotlib expert. If you're interested in learning matplotlib, have a look!

<center>

[**Join the course**](https://www.matplotlib-journey.com/)

</center>

<br>
    