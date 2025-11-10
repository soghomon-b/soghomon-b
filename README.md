## Hi there 👋
I’m Soghomon. I build NLP models that are accessible, high-quality, and impactful.
Explore the SOGHOMONNET Neural Network below to learn more about me.

```python
# ┌─────────────────────────────────────────────────────────────┐
# │                    S O G H O M O N N E T                   │
# └─────────────────────────────────────────────────────────────┘
# Task: Research & learn & ship useful ML systems for language + education.

import torch
# NOTE: this NN uses Modules that do not exist for ✨ aesthetic ✨ reasons.
class SoghomonNet(nn.Module):
    def __init__(self):
        super().__init__()

        # Hyperparameters (personality-as-code)
        self.hparams = dict(
            curiosity=1.0,
            shipping_bias=0.9,     # strong bias toward building & releasing
            kindness_dropout=0.1,
            languages=["English","French","Arabic","Armenian","German","Spanish"],
            location="Vancouver, BC, Canada",
        )

        # Layers
        self.layers = Parallel(
            Intro(
                tagline="CS × Linguistics @ UBC → building accessible ML",
                status="Founder of BojAI • TA • ML R&D"
            ),
            Research(
                interests=[
                    "Low-resource NLP",
                    "Efficient training & deployment",
                    "Educational AI (tagging, assessment, tooling)",
                    "Unsupervised representations & clustering",
                ],
                current=[
                    "SVD-based geometric methods for creating universal linguistic embeddings",
                    "↳ Investigating how different embedding styles capture semantic meaning",
                ],
            ),
            nn.Sequential(  # series of projects
                Project(
                    name="BojAI",
                    brief="Open-source framework to process/train/evaluate/deploy ML pipelines (CLI + PyQt UI).",
                    stack=["Python","PyTorch","PyQt5","HF Transformers"],
                    link="https://bojai.org",
                ),
                Project(
                    name="UltiQuest",
                    brief="Ontology + LLM pipelines to tag past-exam questions with hierarchical concepts.",
                    stack=["Python","LLMs","Evaluation harness"],
                ),
                Project(
                    name="MT for Under-Resourced Languages",
                    brief="Fine-tuned transformers across 5 language families with reproducible HPC pipelines.",
                    stack=["Python","Transformers","SLURM","sacreBLEU"],
                ),
            ),
            Skills(
                core=["Python","PyTorch","Transformers","TypeScript","React","C/C++","Docker","Ollama"],
                patterns=["Design patterns","Data pipelines","Caching","Neural networks","Unit/CI"],
                tools=["HF","W&B","PyQt","GitHub Actions","VS Code","Linux"],
            ),
            Experience([
                Role("Samsung R&D Canada","Technical Writer Co-op • ML tools for the content team"),
                Role("TU Darmstadt","MT research • low-resource pipelines & eval"),
                Role("UBC CPSC 210","TA • Software Construction"),
                Role("UBC CEDaR","Language Reclamation Engineer • ORC + ASR for Kwak’wala (Indigenous language)"),
            ]),
            PapersAndTalks([
                Item("Improving Low-Resource Machine Translation via Cross-Linguistic Transfer from Typologically Similar High-Resource Languages",
                     link="https://past.the-iyrc.org/uploads/1/2/9/7/129787256/iyrc2021_23_final.pdf"),
                Item("How does a computer understand Modern Standard Arabic's morphological scales?",
                     link="https://arxiv.org/abs/2501.00045"),
            ]),
            Contact(
                email="soghmon5 [at] gmail [dot] com",
                web="https://bojai.org",
                linkedin="https://www.linkedin.com/in/saughmon-boujkian"
            ),
        )

    def forward(self, _):
        # Render sections in a nice order :)
        for layer in self.layers:
            if hasattr(layer, "render"):
                layer.render()
        return "👋 Thanks for visiting!"

if __name__ == "__main__":
    torch.manual_seed(2025)
    model = SoghomonNet()
    model.fit()
    # Training in progress: making ML accessible, high-quality, and impactful.
    # SoghomonNet requires more data — applying to grad school to get it!
```

