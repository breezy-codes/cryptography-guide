# Maths Cheat Sheet with Latex

This is my holy grail document I store in Obsidian that I have for quick reference, either for trying to remember a symbol or if I'm needing the latex name for it. I have a lot of these symbols in my notes, so this is a great way to keep them all in one place. Feel free to download the markdown file yourself and add into your own Obsidian or notion vault.

## Relation Operators

### Less Than Relations

| Symbol         | LaTeX Command     | Comment                           | Description                           |
| ------------- | ---------------- | --------------------------------- | ------------------------------------- |
| $<$           | `<`               | is less than                      | A is smaller than B                  |
| $\nless$      | `\nless`          | is not less than                  | A is not smaller than B              |
| $\leq$        | `\leq`            | is less than or equal to          | A is smaller than or equal to B      |
| $\leqslant$   | `\leqslant`       | is less than or equal to          | Alternative form of $\leq$           |
| $\nleq$       | `\nleq`           | is neither less than nor equal to | A is not $\leq$ B                    |
| $\nleqslant$  | `\nleqslant`      | is neither less than nor equal to | A is not $\leqslant$ B               |
| $\prec$       | `\prec`           | precedes                          | A comes before B in an ordering      |
| $\nprec$      | `\nprec`          | doesn't precede                   | A does not precede B                 |
| $\preceq$     | `\preceq`         | precedes or equals                | A is before or equal to B            |
| $\npreceq$    | `\npreceq`        | neither precedes nor equals       | A is neither before nor equal to B   |
| $\ll$         | `\ll`             | much less than                    | A is significantly smaller than B    |
| $\lll$        | `\lll`            | very much less than               | Stronger version of $\ll$            |
| $\subset$     | `\subset`         | is a proper subset of             | A is a subset but not equal to B     |
| $\not\subset$ | `\not\subset`     | is not a proper subset of         | A is not a subset of B               |
| $\subseteqq$  | `\subseteqq`      | is a subset of                    | A is a subset or equal to B          |
| $\nsubseteqq$ | `\nsubseteqq`     | is not a subset of                | A is not a subset or equal to B      |
| $\sqsubset$   | `\sqsubset`       | square subset                     | A is a subset in some structure      |
| $\sqsubseteq$ | `\sqsubseteq`     | square subset or equals           | A is a subset or equal in structure  |

### Greater Than Relations

| Symbol         | LaTeX Command     | Comment                              | Description                           |
| ------------- | ---------------- | ------------------------------------ | ------------------------------------- |
| $>$           | `>`               | is greater than                      | A is larger than B                   |
| $\ngtr$       | `\ngtr`           | is not greater than                  | A is not larger than B               |
| $\geq$        | `\geq`            | is greater than or equal to          | A is larger than or equal to B       |
| $\geqslant$   | `\geqslant`       | is greater than or equal to          | Alternative form of $\geq$           |
| $\ngeq$       | `\ngeq`           | is neither greater than nor equal to | A is not $\geq$ B                    |
| $\ngeqslant$  | `\ngeqslant`      | is neither greater than nor equal to | A is not $\geqslant$ B               |
| $\succ$       | `\succ`           | succeeds                             | A comes after B in an ordering       |
| $\nsucc$      | `\nsucc`          | doesn't succeed                      | A does not succeed B                 |
| $\succeq$     | `\succeq`         | succeeds or equals                   | A is after or equal to B             |
| $\nsucceq$    | `\nsucceq`        | neither succeeds nor equals          | A is neither after nor equal to B    |
| $\gg$         | `\gg`             | much greater than                    | A is significantly larger than B     |
| $\ggg$        | `\ggg`            | very much greater than               | Stronger version of $\gg$            |
| $\supset$     | `\supset`         | is a proper superset of              | A is a superset but not equal to B   |
| $\not\supset$ | `\not\supset`     | is not a proper superset of          | A is not a superset of B             |
| $\supseteqq$  | `\supseteqq`      | is a superset of                     | A is a superset or equal to B        |
| $\nsupseteqq$ | `\nsupseteqq`     | is not a superset of                 | A is not a superset or equal to B    |
| $\sqsupset$   | `\sqsupset`       | square superset                      | A is a superset in some structure    |
| $\sqsupseteq$ | `\sqsupseteq`     | square superset or equals            | A is a superset or equal in structure|

### Equality and Other Relations

| Symbol          | LaTeX Command      | Comment                | Description                           |
| -------------- | ----------------- | ---------------------- | ------------------------------------- |
| $=$            | `=`               | is equal to            | A and B are identical                |
| $\doteq$       | `\doteq`          | approximately equal to | A is equal to B in some sense        |
| $\equiv$       | `\equiv`          | is equivalent to       | A and B are equivalent in logic      |
| $\approx$      | `\approx`         | is approximately       | A is close to B                      |
| $\cong$        | `\cong`           | is congruent to        | A is congruent to B (geometry)       |
| $\simeq$       | `\simeq`          | is similar or equal to | A is roughly equal or similar to B   |
| $\sim$         | `\sim`            | is similar to          | A is related to B                    |
| $\propto$      | `\propto`         | is proportional to     | A varies proportionally to B         |
| $\neq$ or $\ne$ | `\neq` or `\ne`  | is not equal to        | A and B are not the same             |

### Additional Operators

| Symbol       | LaTeX Command | Comment               | Description                      |
| ------------ | ------------- | --------------------- | -------------------------------- |
| $\parallel$  | `\parallel`   | is parallel with      | A and B are parallel             |
| $\nparallel$ | `\nparallel`  | is not parallel with  | A and B are not parallel         |
| $\asymp$     | `\asymp`      | is asymptotic to      | A behaves like B at large scales |
| $\bowtie$    | `\bowtie`     | bowtie relation       | Special relation in algebra      |
| $\vdash$     | `\vdash`      | yields or proves      | A proves B in logic              |
| $\dashv$     | `\dashv`      | is reverse yields     | Dual of $\vdash$                 |
| $\in$        | `\in`         | is member of          | A belongs to set B               |
| $\ni$        | `\ni`         | owns, has member      | B contains A                     |
| $\smile$     | `\smile`      | smile relation        | Used in geometry                 |
| $\frown$     | `\frown`      | frown relation        | Used in geometry                 |
| $\models$    | `\models`     | models                | A models B (logic and sets)      |
| $\notin$     | `\notin`      | is not member of      | A is not in set B                |
| $\perp$      | `\perp`       | is perpendicular with | A is perpendicular to B          |
| $\mid$       | `\mid`        | divides               | A divides B in number theory     |

## Binary Operators

### Binary Operators

| Symbol        | LaTeX Command     | Comment                  | Description                            |
|--------------|-----------------|--------------------------|----------------------------------------|
| $\pm$        | `\pm`            | plus or minus            | Indicates two possible values, ± A    |
| $\mp$        | `\mp`            | minus or plus            | Opposite of $\pm$                     |
| $\times$     | `\times`         | multiplied by            | A × B                                 |
| $\div$       | `\div`           | divided by               | A ÷ B                                 |
| $\ast$       | `\ast`           | asterisk                 | Multiplication operator               |
| $\star$      | `\star`          | star                     | Alternative multiplication notation   |
| $\dagger$    | `\dagger`        | dagger                   | Used in mathematical proofs           |
| $\ddagger$   | `\ddagger`       | double dagger            | Used in mathematical contexts         |
| $\cap$       | `\cap`           | set intersection         | Common elements of sets A ∩ B         |
| $\cup$       | `\cup`           | set union                | All elements in A or B (A ∪ B)        |
| $\uplus$     | `\uplus`         | multiset addition        | Union with multiplicity               |
| $\sqcap$     | `\sqcap`         | square cap               | Similar to set intersection           |
| $\sqcup$     | `\sqcup`         | square cup               | Similar to set union                  |
| $\vee$       | `\vee`           | logical OR               | A OR B                                |
| $\wedge$     | `\wedge`         | logical AND              | A AND B                               |
| $\cdot$      | `\cdot`          | dot product              | A · B (multiplication or dot product) |
| $\diamond$   | `\diamond`       | diamond                  | Used in algebra and logic             |
| $\bigtriangleup$ | `\bigtriangleup` | big triangle up        | Large upright triangle symbol         |
| $\bigtriangledown$ | `\bigtriangledown` | big triangle down  | Large inverted triangle symbol        |
| $\triangleleft$ | `\triangleleft` | left triangle          | Triangle pointing left                |
| $\triangleright$ | `\triangleright` | right triangle       | Triangle pointing right               |
| $\bigcirc$    | `\bigcirc`       | big circle               | Large circular operator               |
| $\bullet$     | `\bullet`        | bullet                   | Used in set notation and logic        |
| $\wr$         | `\wr`            | wreath product           | Used in group theory                  |
| $\oplus$      | `\oplus`         | direct sum               | A ⊕ B (sum of two mathematical structures) |
| $\ominus$     | `\ominus`        | minus with circle        | Alternative subtraction notation      |
| $\otimes$     | `\otimes`        | tensor product           | Used in linear algebra                |
| $\oslash$     | `\oslash`        | slash in circle          | Used in set theory and logic          |
| $\odot$       | `\odot`          | dot in circle            | Used in geometry and algebra          |
| $\circ$       | `\circ`          | small circle             | Function composition operator         |
| $\setminus$   | `\setminus`      | set difference           | Elements in A but not in B (A \ B)   |
| $\amalg$      | `\amalg`         | amalgamation             | Used in algebraic topology            |

## Greek Letters

### Greek Letters

| Symbol     | LaTeX Command                                  | Description                             |
|-----------|----------------------------------------------|-----------------------------------------|
| A and α   | `\Alpha` and `\alpha`                        | Capital and lowercase alpha             |
| B and β   | `\Beta` and `\beta`                          | Capital and lowercase beta              |
| Γ and γ   | `\Gamma` and `\gamma`                        | Capital and lowercase gamma             |
| Δ and δ   | `\Delta` and `\delta`                        | Capital and lowercase delta             |
| Ε, ε, ϵ   | `\Epsilon`, `\epsilon`, and `\varepsilon`    | Standard and variant epsilon            |
| Ζ and ζ   | `\Zeta` and `\zeta`                          | Capital and lowercase zeta              |
| Η and η   | `\Eta` and `\eta`                            | Capital and lowercase eta               |
| Θ, θ, ϑ   | `\Theta`, `\theta`, and `\vartheta`          | Standard and variant theta              |
| Ι and ι   | `\Iota` and `\iota`                          | Capital and lowercase iota              |
| Κ, κ, ϰ   | `\Kappa`, `\kappa`, and `\varkappa`         | Standard and variant kappa              |
| Λ and λ   | `\Lambda` and `\lambda`                      | Capital and lowercase lambda            |
| Μ and μ   | `\Mu` and `\mu`                              | Capital and lowercase mu                |
| Ν and ν   | `\Nu` and `\nu`                          | Capital and lowercase nu                |
| Ξ and ξ   | `\Xi` and `\xi`                          | Capital and lowercase xi                |
| Ο and ο   | `\Omicron` and `\omicron`                | Capital and lowercase omicron           |
| Π, π, ϖ   | `\Pi`, `\pi`, and `\varpi`               | Standard and variant pi                 |
| Ρ, ρ, ϱ   | `\Rho`, `\rho`, and `\varrho`           | Standard and variant rho                |
| Σ, σ, ς   | `\Sigma`, `\sigma`, and `\varsigma`     | Standard and final sigma                |
| Τ and τ   | `\Tau` and `\tau`                        | Capital and lowercase tau               |
| Υ and υ   | `\Upsilon` and `\upsilon`                | Capital and lowercase upsilon           |
| Φ, φ, ϕ   | `\Phi`, `\phi`, and `\varphi`           | Standard and variant phi                |
| Χ and χ   | `\Chi` and `\chi`                        | Capital and lowercase chi               |
| Ψ and ψ   | `\Psi` and `\psi`                        | Capital and lowercase psi               |
| Ω and ω   | `\Omega` and `\omega`                    | Capital and lowercase omega             |

### Archaic Greek Letters

| Symbol  | LaTeX Command    | Description               |
|---------|----------------|---------------------------|
| 𝔉      | `\Digamma`      | Archaic Greek letter Digamma |
| 𝔉      | `\digamma`      | Lowercase Digamma          |

## Unary Operators

### Unary Operators

| Symbol  | LaTeX Command | Comment    | Description                 |
|---------|-------------|-----------|-----------------------------|
| +       | `+`         | plus      | Positive sign               |
| -       | `-`         | negation  | Negative sign               |
| $\neg$  | `\neg`      | not       | Logical NOT                 |
| !       | `!`         | factorial | Computes factorial (n!)     |
| $\#$    | `\#`        | hash      | Used in number theory       |
| $\#$    | `\#`        | primorial | Product of prime numbers    |

## Negated Binary Operators

### Not Equal Relations

| Symbol        | LaTeX Command       | Comment                         | Description                              |
|--------------|--------------------|---------------------------------|------------------------------------------|
| $\neq$ or $\ne$  | `\neq` or `\ne` | is not equal to                | A is different from B                   |
| $\ncong$     | `\ncong`            | is not congruent to            | A is not congruent to B                  |
| $\nsim$      | `\nsim`             | is not similar to              | A is not related to B                   |
| $\nshortmid$ | `\nshortmid`        | negated short division         | A does not divide B                     |
| $\nmid$      | `\nmid`             | does not divide                | A does not divide B                     |
| $\notin$     | `\notin`            | is not a member of             | A does not belong to set B              |

### Not Less Than Relations

| Symbol        | LaTeX Command       | Comment                         | Description                              |
|--------------|--------------------|---------------------------------|------------------------------------------|
| $\nless$     | `\nless`            | is not less than               | A is not smaller than B                 |
| $\nleq$      | `\nleq`             | is not less than or equal to   | A is neither less than nor equal to B   |
| $\nleqslant$ | `\nleqslant`        | negated less than or equal     | Alternative version of $\nleq$          |
| $\nleqq$     | `\nleqq`            | negated less than or equal     | Alternative notation                    |
| $\lneq$      | `\lneq`             | less than but not equal        | A < B but not A = B                     |
| $\lvertneqq$ | `\lvertneqq`        | strict less than not equal     | Stronger version of $\lneq$             |
| $\lnsim$     | `\lnsim`            | not similar                    | A is not similar to B                   |
| $\lnapprox$  | `\lnapprox`         | not approximately similar      | A is not approximately similar to B     |
| $\nprec$     | `\nprec`            | does not precede               | A does not come before B in order       |
| $\npreceq$   | `\npreceq`          | neither precedes nor equals    | A is neither before nor equal to B      |
| $\npreceqq$  | `\npreceqq`         | not precedes or equals         | Alternative notation                    |
| $\nprecsim$  | `\nprecsim`         | not precedes similar           | A does not precede B in similarity      |
| $\nprecnapprox$ | `\nprecnapprox` | not precedes approximately     | A does not precede B approximately      |
| $\ntriangleleft$ | `\ntriangleleft` | not left triangle subset       | A is not a left-subset of B             |
| $\ntrianglelefteq$ | `\ntrianglelefteq` | not left subset equal | A is neither left-subset nor equal      |
| $\nsubseteq$ | `\nsubseteq`        | is not a subset of             | A is not contained within B             |
| $\nsubseteqq$ | `\nsubseteqq`      | is not a subset of (variant)   | Alternative notation                    |
| $\subsetneq$ | `\subsetneq`        | is a subset but not equal      | A ⊆ B but A ≠ B                         |
| $\varsupsetneq$ | `\varsupsetneq`  | is a superset but not equal   | A ⊇ B but A ≠ B                         |

### Not Greater Than Relations

| Symbol        | LaTeX Command       | Comment                         | Description                              |
|--------------|--------------------|---------------------------------|------------------------------------------|
| $\ngtr$      | `\ngtr`             | is not greater than            | A is not larger than B                  |
| $\ngeq$      | `\ngeq`             | is not greater than or equal to | A is neither greater than nor equal to B |
| $\ngeqslant$ | `\ngeqslant`        | negated greater than or equal  | Alternative notation                     |
| $\ngeqq$     | `\ngeqq`            | negated greater than or equal  | Alternative notation                     |
| $\gneq$      | `\gneq`             | greater than but not equal     | A > B but not A = B                      |
| $\gvertneqq$ | `\gvertneqq`        | strict greater than not equal | Stronger version of $\gneq$              |
| $\gnsim$     | `\gnsim`            | not similar                    | A is not similar to B                    |
| $\gnapprox$  | `\gnapprox`         | not approximately similar      | A is not approximately similar to B      |
| $\nsucc$     | `\nsucc`            | does not succeed               | A does not come after B in order         |
| $\nsucceq$   | `\nsucceq`          | neither succeeds nor equals    | A is neither after nor equal to B        |
| $\nsucceqq$  | `\nsucceqq`         | not succeeds or equals         | Alternative notation                      |
| $\nsuccsim$  | `\nsuccsim`         | not succeeds similar           | A does not succeed B in similarity       |
| $\nsuccnapprox$ | `\nsuccnapprox` | not succeeds approximately     | A does not succeed B approximately       |
| $\ntriangleright$ | `\ntriangleright` | not right triangle subset  | A is not a right-subset of B             |
| $\ntrianglerighteq$ | `\ntrianglerighteq` | not right subset equal | A is neither right-subset nor equal      |
| $\nsupseteq$ | `\nsupseteq`        | is not a superset of           | A is not containing B                    |
| $\nsupseteqq$ | `\nsupseteqq`      | is not a superset of (variant) | Alternative notation                     |
| $\supsetneq$ | `\supsetneq`        | is a superset but not equal    | A ⊇ B but A ≠ B                         |
| $\supsetneqq$ | `\supsetneqq`      | strict superset not equal      | Stronger version of $\supsetneq$        |
| $\varsupsetneqq$ | `\varsupsetneqq` | strict superset not equal      | Strongest version of $\supsetneq$       |

### Other Negated Relations

| Symbol        | LaTeX Command       | Comment                         | Description                              |
|--------------|--------------------|---------------------------------|------------------------------------------|
| $\nvdash$    | `\nvdash`           | does not yield                 | A does not entail B in logic            |
| $\nvDash$    | `\nvDash`           | does not satisfy               | A does not model B                      |
| $\nVDash$    | `\nVDash`           | does not strongly satisfy      | Stronger version of $\nvDash$           |
| $\nshortparallel$ | `\nshortparallel` | not short parallel           | A is not parallel to B (short version)  |
| $\nparallel$ | `\nparallel`        | is not parallel with          | A is not parallel to B                   |

## LaTeX Arrows Reference

### Basic Arrows

| Symbol            | LaTeX Command     | Description             |
| ----------------- | ----------------- | ----------------------- |
| $\leftarrow$      | `\leftarrow`      | Left arrow              |
| $\rightarrow$     | `\rightarrow`     | Right arrow             |
| $\leftrightarrow$ | `\leftrightarrow` | Left-right arrow        |
| $\Leftarrow$      | `\Leftarrow`      | Double left arrow       |
| $\Rightarrow$     | `\Rightarrow`     | Double right arrow      |
| $\Leftrightarrow$ | `\Leftrightarrow` | Double left-right arrow |

### Long Arrows

| Symbol  | LaTeX Command | Description |
|---------|--------------|-------------|
| $\longleftarrow$ | `\longleftarrow` | Long left arrow |
| $\longrightarrow$ | `\longrightarrow` | Long right arrow |
| $\longleftrightarrow$ | `\longleftrightarrow` | Long left-right arrow |
| $\Longleftarrow$ | `\Longleftarrow` | Long double left arrow |
| $\Longrightarrow$ | `\Longrightarrow` | Long double right arrow |
| $\Longleftrightarrow$ | `\Longleftrightarrow` | Long double left-right arrow |

### Curved & Hooked Arrows

| Symbol  | LaTeX Command | Description |
|---------|--------------|-------------|
| $\curvearrowleft$ | `\curvearrowleft` | Curved left arrow |
| $\curvearrowright$ | `\curvearrowright` | Curved right arrow |
| $\hookleftarrow$ | `\hookleftarrow` | Hooked left arrow |
| $\hookrightarrow$ | `\hookrightarrow` | Hooked right arrow |

### Harpoon Arrows

| Symbol  | LaTeX Command | Description |
|---------|--------------|-------------|
| $\leftharpoonup$ | `\leftharpoonup` | Left harpoon up |
| $\leftharpoondown$ | `\leftharpoondown` | Left harpoon down |
| $\rightharpoonup$ | `\rightharpoonup` | Right harpoon up |
| $\rightharpoondown$ | `\rightharpoondown` | Right harpoon down |
| $\upharpoonleft$ | `\upharpoonleft` | Up harpoon left |
| $\upharpoonright$ | `\upharpoonright` | Up harpoon right |
| $\downharpoonleft$ | `\downharpoonleft` | Down harpoon left |
| $\downharpoonright$ | `\downharpoonright` | Down harpoon right |

### Dotted & Dashed Arrows

| Symbol  | LaTeX Command | Description |
|---------|--------------|-------------|
| $\dashleftarrow$ | `\dashleftarrow` | Dashed left arrow |
| $\dashrightarrow$ | `\dashrightarrow` | Dashed right arrow |
| $\dotsleftarrow$ | `\dotsleftarrow` | Dotted left arrow |
| $\dotsrightarrow$ | `\dotsrightarrow` | Dotted right arrow |

### Arrows with Lines & Additional Elements

| Symbol  | LaTeX Command | Description |
|---------|--------------|-------------|
| $\twoheadleftarrow$ | `\twoheadleftarrow` | Two-headed left arrow |
| $\twoheadrightarrow$ | `\twoheadrightarrow` | Two-headed right arrow |
| $\rightsquigarrow$ | `\rightsquigarrow` | Right squiggly arrow |
| $\leftrightsquigarrow$ | `\leftrightsquigarrow` | Left-right squiggly arrow |
| $\multimap$ | `\multimap` | Multi-map arrow |
| $\rightleftharpoons$ | `\rightleftharpoons` | Right-left harpoons |
| $\rightrightarrows$ | `\rightrightarrows` | Two right arrows |
| $\leftleftarrows$ | `\leftleftarrows` | Two left arrows |
| $\upuparrows$ | `\upuparrows` | Two up arrows |
| $\downdownarrows$ | `\downdownarrows` | Two down arrows |
| $\nwarrow$ | `\nwarrow` | North-west diagonal arrow |
| $\nearrow$ | `\nearrow` | North-east diagonal arrow |
| $\swarrow$ | `\swarrow` | South-west diagonal arrow |
| $\searrow$ | `\searrow` | South-east diagonal arrow |

### Vertical & Horizontal Arrows

| Symbol  | LaTeX Command | Description |
|---------|--------------|-------------|
| $\uparrow$ | `\uparrow` | Up arrow |
| $\downarrow$ | `\downarrow` | Down arrow |
| $\updownarrow$ | `\updownarrow` | Up-down arrow |
| $\Uparrow$ | `\Uparrow` | Double up arrow |
| $\Downarrow$ | `\Downarrow` | Double down arrow |
| $\Updownarrow$ | `\Updownarrow` | Double up-down arrow |

### Miscellaneous Arrows

| Symbol  | LaTeX Command | Description |
|---------|--------------|-------------|
| $\leadsto$ | `\leadsto` | Leads to |
| $\mapsto$ | `\mapsto` | Maps to |
| $\longmapsto$ | `\longmapsto` | Long maps to |
| $\rightarrowtail$ | `\rightarrowtail` | Right tail arrow |
| $\leftarrowtail$ | `\leftarrowtail` | Left tail arrow |
