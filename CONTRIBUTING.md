## Contributing to `morethemes`

This document focuses on adding themes to `morethemes`, but other kind of contributions are possible. Feel free to [open an issue](https://github.com/JosephBARBIERDARNAL/morethemes/issues) to discuss it.

<br>

### Add a theme

In this tutorial, I'll assume your theme is named `sunglasses`, as for the example. Remember to change it with the actual name of your theme.

Here are the steps to follow to get started:

- Fork the repository to your own GitHub account.

- Clone your forked repository to your local machine (ensure you have [Git installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)):

```bash
git clone https://github.com/YOURUSERNAME/morethemes.git
```

- Create a new branch for your theme:

```bash
git checkout -b sunglasses
```

- Set up your Python environment (ensure you have [uv installed](https://docs.astral.sh/uv/getting-started/installation/)):

```bash
uv init
uv pip install -e .
uv sync --all-extras --dev
```

- In `morethemes/morethemes/themes/`, create a new python file named `sunglasses.py`. It should looks like this:

```python
sunglasses_theme = {
    "name": "sunglasses", # the name of your theme
    "author": "Your Name", # your name or the name of the author
    "theme": { # all arguments passed to plt.rcParams
        "axes.facecolor": "#232323",
        "figure.facecolor": "#282828",
    },
}
```

- In `morethemes/morethemes/__init__.py`, add this at the top of the file:

```python
from .sunglasses import sunglasses_theme
```

- Then add this in the `ALL_THEMES` dictionnary:

```python
"sunglasses": sunglasses_theme
```

- Test that everything works correctly by running:

```bash
uv run pytest
```

- Commit and push your changes:

```bash
git add -A
git commit -m "add sunglasses theme"
git push
```

- Go to your fork and click on the "Open a PR" popup

Congrats! Once your PR is merged, it will be part of `morethemes` and accessible via `mt.set_theme("sunglasses")`.

It'll be available in the published version once a new released is published on PyPI.