# Structure Demotion (paper)

**Structure Demotion: Reclaiming the KV-Cache Budget from Repeated Separators under Extreme Compression**
Satyajeeth Suresh Kannan, Innovation Academy, Alpharetta, Georgia, USA

- Paper: [structure_demotion.pdf](structure_demotion.pdf) (LaTeX source: [structure_demotion.tex](structure_demotion.tex))
- Implementation: pull request [NVIDIA/kvpress#288](https://github.com/NVIDIA/kvpress/pull/288), branch `structure-demotion-restorekv` of this fork
- Leaderboard results: [HF Space discussion #24](https://huggingface.co/spaces/nvidia/kvpress-leaderboard/discussions/24)

Headline: on RULER-4096 with Qwen3-8B at compression ratio 0.9375, structure demotion lifts RestoreKV+ from 86.38 to 89.64
(paired 95% CI of the gain [+2.73, +3.77]). An arXiv posting is being set up; this page will link to it when it is live.

The paper discloses the AI assistance used for the implementation and drafting.
