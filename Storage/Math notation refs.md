## General notation

---

Using one dollar sign `$` on each side will give you inline math $e^{i*\pi}+1 = 0$

Using two dollar signs will center the math on its own line
$$e^{i*\pi}+1 = 0$$
TeX math will not work in code blocks, you can call a code block with back-ticks (the ones that appear when you don't press shift and press the grave (~) key)

Some notations are different and can become compressed when changing between inline and centered such as sum $\sum_{n=1}^{\infty} 2^{-n} = 1$ vs:
$$\sum_{n=1}^{\infty} 2^{-n} = 1$$

For groupings such as super and subscript you have to use curly braces (These { }) otherwise this happens $e^i*\pi$ (input: `e^i*\pi`), where the desired output is $e^{i*\pi}$ (input: `e^{i*\pi}`)

Side note: using the backslash as a break works so it appears in TeX equations:
- With break slash: $\{a\}$ (input: `\{a\}`)
- Without: ${a}$ (input: `{a}`)

Errored math turns red and yellow and break display like this $e^$ for inline, and this for centered: $$e^$$
Command characters/ arguments use the ***backslash*** ( \\ ), forward slash will do nothing
- Wrong: $/frac{1}{2}$ (input: `/frac{1}{2}`)
- Right: $\frac{1}{2}$ (input: `\frac{1}{2}`)

Common notations:
$x^2 + y^2 = z^2$ as `$x^2 + y^2 = z^2$
$a \cdot b$ as `$a \cdot b$`
$a \times b$ as `$a \times b$`
$\frac{a}{b}$ as `$\frac{a}{b}$`
$x^2$ as `$x^2$`
$x_2$ as `$x_2$`
$a \propto b$ as `$a \propto b$`
$a \equiv b$ as `$a \equiv b$`
$a \approx b$ as `$a \approx b$`
$a \neq b$ as `$a \neq$`
$\pm$ as `$\pm$`
$\bar{x}$ as `$\bar{x}$`
$\bar{ab}$ as `$\bar{ab}$`
$\leq$ as `$\leq$`
$\geq$ as `$\geq$`
$\int_{a}^{b} x^2 \,dx$ as `$\int_{a}^{b} x^2 \,dx$`
$\lim_{x\to\infty} f(x)$ as `$\lim_{x\to\infty} f(x)$`
$\{a \dots a_n \}$ as `$\{a \dots a_n \}$`
$a \implies b$ as `$a \implies b`
^common-notation

Common characters:
![[Greek Symbols TeX.png]]
Note uppercase Greek letters use an uppercase character
^common-characters