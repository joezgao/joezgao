### Joe Gao — Stanford CS & AI

Small models and research ideas, built from scratch and made visible in 3D, mostly in the browser.

**learns**

- [**micrograd 3D**](https://github.com/joezgao/micrograd-3d) · [play](https://joezgao.github.io/micrograd-3d/): Karpathy's micrograd, rewritten in TypeScript and visualised in 3D.

**thinks**

- [**Attention, in space**](https://github.com/joezgao/attention-in-space) · [play](https://joezgao.github.io/attention-in-space/attention.html): a 0.81M-parameter character-level GPT (nanoGPT's design, written in NumPy), trained on tiny-shakespeare. Its attention is drawn as arcs in 3D, and it runs in the browser.
- [**How a model reads**](https://github.com/joezgao/how-a-model-reads) · [play](https://joezgao.github.io/how-a-model-reads/how-a-model-reads.html): a byte-pair encoding tokenizer learned from scratch on tiny-shakespeare, shown merge by merge.
- [**Where words live**](https://github.com/joezgao/where-words-live) · [play](https://joezgao.github.io/where-words-live/): skip-gram word2vec trained from scratch in NumPy on tiny-shakespeare; pick a word and see its nearest neighbours in 3D.

**creates**

- [**Noise, undone**](https://github.com/joezgao/noise-undone) · [play](https://joezgao.github.io/noise-undone/noise-undone.html): a tiny diffusion model moves 4,000 points of Gaussian noise onto a trefoil knot, step by step, in 3D.
- [**Heptapod**](https://github.com/joezgao/heptapod) · [play](https://joezgao.github.io/heptapod/): can a language model write a whole passage at once? A tiny diffusion model fills in 255 letters everywhere over a few passes, drawn as brush strokes around a circle, beside a GPT of exactly the same size writing one letter at a time. Both trained from scratch on tiny-shakespeare; both run in the browser.

**acts?**

- [**First steps**](https://github.com/joezgao/first-steps) · [play](https://joezgao.github.io/first-steps/first-steps.html): an agent learns with REINFORCE to go round a pit and reach a light. A slider steps through its 10,240 episodes of training.

**3D & research**

- [**All the way down**](https://github.com/joezgao/all-the-way-down) · [play](https://joezgao.github.io/all-the-way-down/all-the-way-down.html): WonderZoom's scale-aware opacity (Cao, Yu & Wu, arXiv 2512.09164) in a browser viewer that zooms 10,000× down a procedural maple leaf to a single stoma.
- [**Seen from twelve sides**](https://github.com/joezgao/seen-from-twelve-sides) · [play](https://joezgao.github.io/seen-from-twelve-sides/seen-from-twelve-sides.html): 3D Gaussian Splatting (Kerbl, Kopanas, Leimkühler & Drettakis, 2023) written from scratch in NumPy. 4,000 Gaussians are fitted to twelve rendered photographs of a stone.
- **Before the run**: *Hinted Scaling Laws* (van Adrichem … Hashimoto, 2026), made playable. Fit a law on small models, press Run, and check its forecast against the largest model's measured 25.9% on GSM8K. *Private until data permission.*
- [**Karesansui 枯山水**](https://github.com/joezgao/karesansui) · [play](https://joezgao.github.io/karesansui/karesansui.html): a dry Zen garden whose rake lines follow a field that flows around each stone. After every change, an unseen monk re-rakes it in about 20–25 strokes.

**stories**

- [**Almost Ripe**](https://github.com/joezgao/almost-ripe) · [play](https://joezgao.github.io/almost-ripe/almost-ripe.html): an interactive story inspired by Harlan Ellison's *I Have No Mouth, and I Must Scream*. Five people are left, and something keeps them. Made in three.js and Web Audio, with every surface, light and sound generated in code.

Built with Claude.

[X](https://x.com/josephzgao) · [Hugging Face](https://huggingface.co/joezgao)
