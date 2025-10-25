# AI-4-Science Reading List (Molecular Biology + Molecular Dynamics + Generative Models)

## Fundemental MD

[Understanding Molecular Simulation](https://www.eng.uc.edu/~beaucag/Classes/AdvancedMaterialsThermodynamics/Books/[Computational science (San Diego, Calif.)] Daan Frenkel_ Berend Smit - Understanding molecular simulation _ from algorithms to applications (2002, Academic Press ) - libgen.lc.pdf)

## Stat Mech Lectures

[Eastman's Stat Mech Lecture](https://web.stanford.edu/~peastman/statmech/)

## Core Diffusion
Diffusion Models are deep generative models which work through inversing a noising process. While taking data and making noise is easy, taking noise and making data is generative modeling:
- [Song's Original Diffusion Paper](https://arxiv.org/abs/2011.13456)
  
If we start at some density, and noise forward, there are deterministic equations for how the probability measure evolves in time according to the Forward-Kolmogorov equations. We can then solve the PDE to determine what process matches those marginals in reverse time:
- [Blog Post on Reverse SDEs](https://jiha-kim.github.io/posts/deriving-reverse-time-stochastic-differential-equations-sdes/)

### SDEs
Easy SDE Book:
[Applied SDEs](https://users.aalto.fi/~asolin/sde-book/sde-book.pdf)

Quintessential books about SDEs covering in depth Ito's Lemma, Girsanovs, Path Measure, Feynman Kac, Stopping Times, Control, Filtering
[Stochastic Differential Equations - Oksendale](https://www.google.com/search?q=stochastic+differential+equations+oksendal&sca_esv=64c7c2e5e44b8d39&sxsrf=AE3TifO1f6cBfRWmKPW6Nx1NvYl8bXZLfA%3A1761366373773&source=hp&ei=ZVH8aIaCLM-i0PEPiKL8QA&iflsig=AOw8s4IAAAAAaPxfddEAa7sQyQTYhJBra_SDxJaRRMhF&gs_ssp=eJzj4tVP1zc0TMsqriwxjS8wYPTSKi7JT85ILC7JTFZIyUxLSy1KzSvJTMxRSC0sTSzJzM8rVsjPLk7NS0nMAQBuHBXE&oq=stochastic+differential&gs_lp=Egdnd3Mtd2l6IhdzdG9jaGFzdGljIGRpZmZlcmVudGlhbCoCCAIyChAjGIAEGCcYigUyBBAjGCcyChAuGIAEGCcYigUyBBAjGCcyCxAAGIAEGJECGIoFMgsQLhiABBiRAhiKBTIFEAAYgAQyBRAAGIAEMgUQLhiABDIFEAAYgARI1h5QAFi5EXAAeACQAQGYAeUBoAHHF6oBBjMuMTkuMbgBAcgBAPgBAZgCFqACsRfCAhEQLhiABBixAxjRAxiDARjHAcICCxAuGIAEGNEDGMcBwgILEAAYgAQYsQMYgwHCAg0QIxjwBRiABBgnGIoFwgIKEAAYgAQYQxiKBcICEBAAGIAEGLEDGEMYgwEYigXCAgsQLhiABBixAxiDAcICDhAuGIAEGLEDGNEDGMcBwgIQEC4YgAQYQxjHARiKBRivAcICExAuGIAEGLEDGNEDGEMYxwEYigXCAg4QABiABBiRAhixAxiKBcICCBAAGIAEGLEDwgINEAAYgAQYsQMYQxiKBcICDhAuGIAEGJECGNQCGIoFmAMAkgcGMS4yMC4xoAfZ4AKyBwYxLjIwLjG4B7EXwgcIMC4xLjIwLjHIB1o&sclient=gws-wiz)
[Shreve Stochastic Calculus](https://cms.dm.uba.ar/academico/materias/2docuat2016/analisis_cuantitativo_en_finanzas/Steve_ShreveStochastic_Calculus_for_Finance_II.pdf)

Deeper resources primarily geared towards stochastic control theory (basically RL but suited for SDE dynamics):
Deterministic Dynamics: [Dynamic Programming](https://www.dl.behinehyab.com/Ebooks/DP/D001_814807_www.behinehyab.com.pdf)
Stochastic Dynamics: [Continuous Time Stochastic Control Theory](https://www.maths.dur.ac.uk/users/andrew.l.allan/projects_2024/Stochastic_Optimization.pdf)
