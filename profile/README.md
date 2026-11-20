<p align="center">
  <a href="https://splotlabs.io"><img src="https://raw.githubusercontent.com/splotlabs/splot/main/docs/assets/hero.svg" alt="splot — AV2. Encode it. Decode it. Trust it." width="100%"></a>
</p>

<p align="center">
  <b>The complete AV2 toolkit.</b><br>
  An encoder, a decoder and a validator for the next-generation video codec.<br>
  One binary. Safe Rust. Built from the spec.
</p>

<p align="center">
  <a href="https://splotlabs.io">Website</a> ·
  <a href="https://github.com/splotlabs/splot">Source</a> ·
  <a href="https://github.com/splotlabs/splot#install-from-source">Install</a> ·
  <a href="https://github.com/splotlabs/splot/issues">Issues</a>
</p>

---

## Three commands. Your first AV2 video.

```bash
splot encode clip.y4m -o clip.ivf      # make it
splot validate clip.ivf                # prove it
splot decode clip.ivf -o - | ffplay -  # watch it
```

That is the whole loop: from raw video to a conformant AV2 stream and back to
your screen.

## Where it stands.

Pre-alpha. It moves fast. Source-available under
[PolyForm Noncommercial 1.0.0](https://github.com/splotlabs/splot/blob/main/LICENSE.md).
Commercial use requires a
[separate written license](https://github.com/splotlabs/splot#license).
