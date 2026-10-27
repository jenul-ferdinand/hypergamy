<h1 align="center">Hypergamy Is Solved</h1>

<p align="center">
  <i>A deadpan paper that models the marriage market as an optimal transport problem.</i>
</p>

<h3 align="center">
  <a href="./hypergamy.pdf">Read the paper</a>
  <span> · </span>
  <a href="./hypergamy.tex">LaTeX source</a>
  <span> · </span>
  <a href="#building">Build</a>
</h3>

<p align="center">
  <a href="https://open.spotify.com/track/1OhrPb6EiqogGjtP1t1uUF"><img src=".github/nuts.png" alt="nuts (feat. Rainy Bear) by Lil Peep and rainy bear on Spotify" width="456"></a>
</p>
<br/>

## What is this?

*Hypergamy Is Solved* treats "marrying up" as a coupling problem between two status distributions. Whether everyone can marry up becomes a question of stochastic dominance, the shortfall when they can't has a closed form, and the equilibrium pairs people by rank. The tone is deadpan, but every theorem, number and citation is meant to be correct.

Height figures come from NHANES 2015–2018; every source is listed in the paper's references.

## What's inside

<table>
  <tr>
    <td width="50%"><b>Feasibility and the Deficit</b><br>When everyone can marry up, and how many are left unmatched when they can't</td>
    <td width="50%"><b>The Six-Foot Rule</b><br>US height data, a closed-form deficit for required height gaps, and the Six-Foot Theorem</td>
  </tr>
  <tr>
    <td width="50%"><b>The Blackpill Theorems</b><br>Why no dating strategy changes aggregate outcomes, and why status gains are zero-sum in rank</td>
    <td width="50%"><b>Equilibrium</b><br>Gale–Shapley stable matching, transferable utility as optimal transport, and Choo–Siow taste shocks</td>
  </tr>
  <tr>
    <td width="50%"><b>Multidimensional Status</b><br>Checklists versus trade-offs across several traits, and hypergamy measured in quantiles</td>
    <td width="50%"><b>Partner History</b><br>What the research finds, and a comparison model that applies to both sexes</td>
  </tr>
</table>

## Building

Requires a TeX distribution with `latexmk`, `pgfplots`, `tcolorbox` and `hyperref`; a full TeX Live install has them all.

```sh
latexmk -pdf hypergamy.tex
```

The source is formatted with [tex-fmt](https://github.com/WGUNDERWOOD/tex-fmt) using `tex-fmt.toml`. Run `tex-fmt --check hypergamy.tex` before committing; VS Code with LaTeX Workshop formats on save.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
