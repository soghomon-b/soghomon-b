## Hi there 👋
I’m Soghomon. I build NLP models that are accessible, high-quality, and impactful.
Explore the SOGHOMONNET Neural Network below to learn more about me.

```python

# ┌─────────────────────────────────────────────────────────────┐
# │                    S O G H O M O N N E T                    │
# └─────────────────────────────────────────────────────────────┘
# Mission: Research, build, and ship AI that makes a difference.
# Focus: Healthcare AI × NLP × Agentic Systems × ML Research

import torch
import torch.nn as nn

# NOTE: Some modules are fictional.
# The research, projects, and experience are real. ✨

class SoghomonNet(nn.Module):
    def __init__(self):
        super().__init__()

        # Hyperparameters (personality-as-code)
        self.hparams = dict(
            curiosity=1.0,
            research_drive=0.95,
            shipping_bias=0.9,
            kindness_dropout=0.0,
            languages=[
                "Armenian", "Arabic", "English",
                "French", "German", "Spanish"
            ],
            location="Vancouver, BC, Canada",
            education="UBC Computer Science + Linguistics (2026)",
        )

        self.layers = nn.Parallel(
            Intro(
                tagline="Computer Science × Linguistics × Healthcare AI",
                status="ML Research Engineer • NeurIPS 2026 Author • BojAI Developer",
                mission="Building reliable, accessible, and clinically useful AI systems.",
            ),

            Research(
                interests=[
                    "Clinical LLMs, RAG, and AI safety",
                    "Agentic AI and multi-agent orchestration",
                    "Multilingual embeddings and representation learning",
                    "Healthcare ML and computational oncology",
                    "Supervised and unsupervised machine learning",
                    "Efficient ML evaluation and deployment",
                ],
                current=[
                    "Universal multilingual embedding spaces",
                    "Clinical AI workflows with safety-first agent architectures",
                    "Multimodal representation learning for oncology",
                ],
            ),

            nn.Sequential(
                Project(
                    name="BojAI",
                    brief=(
                        "Full-stack platform featuring visual AI agent "
                        "orchestration, modular RAG workflows, and safety "
                        "evaluation for clinical AI applications. "
                        "Reduced chatbot development time by 80%."
                    ),
                    stack=[
                        "Python", "FastAPI", "React", "TypeScript",
                        "PostgreSQL", "Supabase", "LLMs"
                    ],
                    link="https://bojai.org",
                ),

                Project(
                    name="Clinical AI Chatbots",
                    brief=(
                        "Clinical LLM applications for mental-health support "
                        "using RAG, semantic retrieval, reranking, "
                        "and multi-layer safety guardrails."
                    ),
                    stack=[
                        "Python", "AWS Bedrock", "FastAPI",
                        "FAISS", "RAG", "Safety Evaluation"
                    ],
                ),

                Project(
                    name="Universal Multilingual Embeddings",
                    brief=(
                        "Investigated cross-lingual alignment across "
                        "multilingual embedding models and geometric "
                        "representation-learning methods."
                    ),
                    stack=[
                        "PyTorch", "Transformers", "SVD",
                        "Contrastive Learning", "Statistical Analysis"
                    ],
                ),

                Project(
                    name="UltiQuest / Quesal AI",
                    brief=(
                        "LLM-powered hierarchical concept tagging "
                        "and educational content generation, "
                        "achieving 80% generation accuracy."
                    ),
                    stack=["Python", "FastAPI", "LLMs", "RAG"],
                ),

                Project(
                    name="Low-Resource Machine Translation",
                    brief=(
                        "Evaluated transfer learning for neural machine "
                        "translation across five low-resource languages."
                    ),
                    stack=["Python", "Transformers", "SLURM", "sacreBLEU"],
                ),
            ),

            Skills(
                core=[
                    "Python", "PyTorch", "scikit-learn",
                    "TypeScript", "React", "FastAPI",
                    "PostgreSQL", "Docker", "Git"
                ],
                ai=[
                    "LLMs", "RAG", "Agentic AI",
                    "Transformers", "Embeddings",
                    "FAISS", "Model Evaluation",
                    "AI Safety"
                ],
                cloud=[
                    "AWS Bedrock", "Supabase",
                    "REST APIs", "Data Pipelines"
                ],
                research=[
                    "Representation Learning",
                    "Statistical Analysis",
                    "Supervised / Unsupervised ML",
                    "Multilingual NLP"
                ],
            ),

            Experience([
                Role(
                    "UBC Psychiatry",
                    "ML Research Engineer • Clinical LLMs, RAG & Safety"
                ),
                Role(
                    "UBC Quesal AI",
                    "Academic Assistant • Agentic AI & Research Leadership"
                ),
                Role(
                    "Samsung R&D Canada",
                    "AI Automation • Production ML Workflows"
                ),
                Role(
                    "TU Darmstadt",
                    "Research Assistant • Neural Machine Translation"
                ),
                Role(
                    "UBC CPSC 210",
                    "Teaching Assistant • Software Construction"
                ),
                Role(
                    "UBC CEDaR",
                    "Language Reclamation Engineer • Kwak'wala OCR"
                ),
            ]),

            PapersAndTalks([
                Item(
                    "Revisiting Cross-Lingual Alignment in the Era "
                    "of Multilingual LLM Embeddings",
                    venue="NeurIPS 2026 NeurReps Proceedings",
                    status="Accepted",
                ),
                Item(
                    "Cross-Linguistic Examination of "
                    "Machine Translation Transfer Learning",
                    venue="arXiv",
                    link="https://arxiv.org/abs/2501.00045",
                ),
            ]),

            Contact(
                email="soghmon5 [at] gmail [dot] com",
                github="https://github.com/soghomon-b",
                web="https://bojai.org",
                linkedin=(
                    "https://www.linkedin.com/in/"
                    "saughmon-boujkian-65a1b11b2/"
                ),
            ),
        )

    def forward(self, _):
        for layer in self.layers:
            if hasattr(layer, "render"):
                layer.render()
        return "Building AI for better science and better care."


if __name__ == "__main__":
    torch.manual_seed(2026)
    model = SoghomonNet()

    # Training never really stops.
    model.fit()

    # Current objective:
        # Minimize clinical risk.
        # Maximize scientific impact.
        # Keep learning.
```

