# We learn slovene HUGO website

## Local deployment

To deploy the Website locally one first has to pull the repository by setting of the command:

```bash
git clone git@github.com:MagnusOffermanns/We-learn-slovene.git
```

Then the theme has to be initialized into the folder `themes` using the following command executed in the same folder as the `git clone`:

```bash
git submodule add https://github.com/McShelby/hugo-theme-relearn.git themes/relearn
```

## Custom shortcodes
I have created some custom shortcodes that are not part of relearn.
The files can be found in:

- `assets/css/custom.css`
- `layout/_shortcodes/inline-spoiler.html`

### Spoiler shortcode

The Spoiler shortcode is used to hide words for Cloze riddles. 

The syntax is:

```markdown
Spoiler Shortcode {{< inline-spoiler >}} Dont look at me :){{< /inline-spoiler >}} Visible again.
```

source: [http://oostens.me/posts/hugo-inline-spoiler-shortcode/](Nelis Oostens)


