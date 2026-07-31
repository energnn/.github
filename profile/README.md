![EnerGNN Logo](../images/energnn-horizontal-color.png#gh-dark-mode-only)
![EnerGNN Logo](../images/energnn-horizontal-color.png#gh-light-mode-only)

## 🙋‍♀️ A short introduction

**EnerGNN** (**Ener**gy **G**raph **N**eural **N**etwork) is a GNN framework designed for real
life energy networks.

The core package [*energnn*](https://github.com/energnn/energnn) includes:
- A complex graph data representation (in the form of Hyper Heterogeneous Multi Graphs),
- A library of compatible GNN models,
- A clear interface to apply them to your own real-life problems.

Companion packages are here to help you get started:
- [*pypowsybl-to-energnn*](https://github.com/energnn/pypowsybl-to-energnn) helps you convert power systems files into the energnn data format,
- [*energnn-storage*](https://github.com/energnn/energnn-storage) implements a feature store and a model registry, all displayed in a web interface,

## 🚀 Getting started

1. Install the core package: `pip install energnn`.
2. Follow the tutorials in our [documentation](https://energnn.readthedocs.io/en/latest/).
3. Convert your own power system files with [*pypowsybl-to-energnn*](https://github.com/energnn/pypowsybl-to-energnn) and start experimenting.

## 👩‍💻 Useful resources

Our documentation is available at https://energnn.readthedocs.io/en/latest/.

## 🌈 Contribution guidelines

Contributions of all kinds are welcome — code, documentation, issues, and reviews. To get involved:

- Read our [Governance](../tsc/GOVERNANCE.md) to understand how the project is organized and how decisions are made.
- Follow our [Code of Conduct](../tsc/CODE_OF_CONDUCT.md) in all project spaces.
- Check the current [committers](../tsc/COMMITTERS.csv) and the process to become one, described in the governance document.

## 📅 Meetings

The Technical Steering Committee meets on the **first Wednesday of each month at 10am CET**. Meetings are open to everyone, published on the [LFX calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings), and [meeting notes](../tsc/meeting-notes/) are posted publicly.

## 🧭 Technical Steering Committee (TSC) members

- Balthazar Donon (Chair), RTE
- Hugo Kulesza, RTE
- Geoffroy Jamgotchian, RTE
- Steve Nouatin, RTE & DataStorm
- Louis Wehenkel, ULiège

## 🏛️​ Supporting Institutions

| RTE | Université de Liège  | INRIA     |
|-----|----------------------|-----------|
| <img src="../images/rte_white.png#gh-dark-mode-only" height="100px"/> <img src="../images/rte_black.png#gh-light-mode-only" height="100px"/> | <img src="../images/ulg_white.png#gh-dark-mode-only" height="100px"/> <img src="../images/ulg_black.png#gh-light-mode-only" height="100px"/> | <img src="../images/inria_white.png#gh-dark-mode-only" width="160px"/> <img src="../images/inria_black.png#gh-light-mode-only" width="160px"/> |

## 🎓 Cite Us

```bibtex
@software{energnn,
  author = {{Committers of EnerGNN}},
  title = {{EnerGNN: A Graph Neural Network library for real-life Energy networks.}},
  url = {https://github.com/energnn},
}
```
