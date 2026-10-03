# ETH 273-0003-00L — Data Science & Machine Learning

Coursework notebooks for the ETH Zürich course *Data Science & Machine Learning* (273-0003-00L), organised by teaching weekend plus the course projects.

## Contents

### Weekend 1
| Notebook | Topic |
| --- | --- |
| `weekend_1/tool_router.ipynb` | LLM tool routing |

### Weekend 2 — Generative models & vision
| Notebook | Topic |
| --- | --- |
| `cnn_fashion_mnist/` | CNN classifier on Fashion-MNIST |
| `autoencoders_basic/`, `Autoencoders CX/` | Autoencoders |
| `UNet Exercise/` | U-Net architecture |
| `diffusion_theory/`, `Diffusion CX/`, `Flag Diffusion CX/` | Diffusion models |

### Weekend 3 — Language models, RAG & agents
| Notebook | Topic |
| --- | --- |
| `language_models/` | Language models |
| `rag_new/`, `RAG TA CX/` | Retrieval-augmented generation |
| `fridge_chef/` | LLM application exercise |
| `agentic_ai_spy/` | Agentic AI mission |
| `interpretability_unsolved.ipynb` | Model interpretability |

### Weekend 4 — Advanced generative models & robustness
| Notebook | Topic |
| --- | --- |
| `adv-attack/` | Adversarial attacks |
| `cond-diff/` | Conditional diffusion models |
| `CVAE CX/` | Conditional VAE on CelebA |

### Projects
| Folder | Notebooks |
| --- | --- |
| `Project_1/` | Task meeting |
| `Project_2/` | Fashion magazine, recycling warehouse |
| `Project_3/` | Agentic tax filler (AgenTekki) |
| `Project_4/` | Deepfake generation & discrimination |

## Running the notebooks

Most notebooks are written for [Google Colab](https://colab.research.google.com/) (GPU runtime recommended for weekends 2 and 4 and project 4). To run locally, use Python 3.10+ with Jupyter and install the packages imported at the top of each notebook, e.g.:

```bash
pip install jupyter numpy matplotlib torch torchvision
```

Notebooks that call LLM APIs expect the relevant API key to be set as an environment variable (or Colab secret) — never commit keys to the repository.
