<div align="center">

# Ayushman Bhatt

**Explainable AI · Medical Imaging · Agentic LLM Systems**

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3400&pause=900&color=7AA2F7&center=true&vCenter=true&width=700&height=30&lines=I+train+vision+models+%E2%80%94+then+interrogate+why+they+decided;Attribution+methods%2C+shortcut+learning%2C+model+reliability;Histopathology+pipelines+and+multi-agent+orchestration)](https://git.io/typing-svg)

<a href="https://linkedin.com/in/ayushman-bhatt-564927343"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=1a1b27" height="22" /></a>
<a href="https://github.com/ayushmanbhatt07?tab=repositories"><img src="https://img.shields.io/badge/Repositories-7AA2F7?style=flat-square&logo=github&logoColor=white&labelColor=1a1b27" height="22" /></a>
<img src="https://img.shields.io/badge/Based_in-India-94E2D5?style=flat-square&labelColor=1a1b27" height="22" />
<img src="https://img.shields.io/badge/Status-Open_to_research_%26_AI_roles-CBA6F7?style=flat-square&labelColor=1a1b27" height="22" />

</div>

```bibtex
@researcher{bhatt2026,
  author    = {Ayushman Bhatt},
  title     = {Interpretable Vision Models and Agentic LLM Systems},
  areas     = {Explainable AI, Medical Imaging, Trustworthy ML, Agentic Orchestration},
  methods   = {Grad-CAM, Guided Backpropagation, Faithfulness Benchmarking, LangGraph},
  thesis    = {Accuracy is table stakes. Interpretable and auditable is the bar.},
  available = {Research collaborations, AI engineering roles}
}
```

<br/>

## `01` &nbsp;Abstract

I work on the gap between a model being *right* and a model being *trustworthy*.

Most of my time goes to two problems. The first is **attribution**: when a CNN classifies a histopathology slide, is it reading tissue morphology or a stain artifact? Grad-CAM produces a pretty heatmap either way — so I'm interested in the quantitative side, where faithfulness and localization are measured rather than eyeballed. The second is **agentic reliability**: LLM workflows that hold state, call tools, and degrade gracefully when a step fails, instead of confidently hallucinating through it.

Both come from the same instinct. A system you can't audit is a system you can't deploy in anything that matters.

<br/>

## `02` &nbsp;Research Log

| Thread | Question I'm chasing | Status |
|:---|:---|:---|
| **Histopathology classification** | How much of CNN performance survives proper stain normalization — and how much was the stain all along? | ![](https://img.shields.io/badge/active-7AA2F7?style=flat-square&labelColor=1a1b27) |
| **Attribution faithfulness** | Grad-CAM and Guided Backprop disagree constantly. Which one is lying, and can we score that? | ![](https://img.shields.io/badge/active-7AA2F7?style=flat-square&labelColor=1a1b27) |
| **Shortcut learning** | Detecting spurious correlations *before* deployment rather than after the failure report. | ![](https://img.shields.io/badge/exploring-CBA6F7?style=flat-square&labelColor=1a1b27) |
| **ViT interpretability** | Attention maps aren't explanations. What transfers from CNN attribution to patch-based architectures? | ![](https://img.shields.io/badge/reading-94E2D5?style=flat-square&labelColor=1a1b27) |
| **Agentic orchestration** | Stateful LangGraph workflows with conditional edges and human-in-the-loop checkpoints. | ![](https://img.shields.io/badge/building-89B4FA?style=flat-square&labelColor=1a1b27) |

<br/>

## `03` &nbsp;Selected Work

<table>
<tr>
<td width="50%" valign="top">

### SmartAMR

`Python` · `scikit-learn` · `Streamlit`

AI-based antibiotic resistance treatment recommendation. Takes resistance profiles and produces ranked, explainable treatment guidance — the explanation is the product, not a footnote, because no clinician acts on an unexplained suggestion.

**[Repository →](https://github.com/ayushmanbhatt07/SmartAMR-AI-Based-Antibiotic-Resistance-Treatment-Recommendation)**

</td>
<td width="50%" valign="top">

### Agentic LLM Reference

`LangChain` · `LangGraph` · `RAG`

Working reference implementation for agent patterns: tool-augmented reasoning, memory, retrieval grounding, and stateful graph workflows. Built as a study artifact, kept as a design reference.

**[Repository →](https://github.com/ayushmanbhatt07/Langchain-Tutorial)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Applied ML Pipelines

`NumPy` · `Pandas` · `scikit-learn`

End-to-end applied machine learning — data wrangling, feature work, modelling, and evaluation discipline. The unglamorous foundation everything else rests on.

**[Repository →](https://github.com/ayushmanbhatt07/DATA-SCIENCE-AND-MACHINE-LEARNING-WITH-PYTHON-2026)**

</td>
<td width="50%" valign="top">

### Histopathology XAI

`PyTorch` · `OpenCV` · `Grad-CAM`

CNN classification over stained tissue with attribution overlays and stain normalization ablations. Current primary research effort.

<sub>◦ In development — repository pending</sub>

</td>
</tr>
</table>

<br/>

## `04` &nbsp;Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn,opencv,fastapi,django,postgres,mongodb,git,linux,cpp&perline=12" height="42" />
</div>

<br/>

|  |  |
|:--|:--|
| **Modelling** | `PyTorch` `TensorFlow` `Keras` `scikit-learn` `OpenCV` |
| **Interpretability** | `Grad-CAM` `Guided Backpropagation` `faithfulness metrics` `localization benchmarks` |
| **LLM systems** | `LangChain` `LangGraph` `Hugging Face` `RAG` `prompt evaluation` |
| **Scientific Python** | `NumPy` `Pandas` `SciPy` `Matplotlib` `Plotly` `NLTK` |
| **Services & data** | `FastAPI` `Django` `JWT` `PostgreSQL` `MongoDB` `MySQL` `SQLite` `Cassandra` |
| **Ops & delivery** | `MLflow` `Hadoop` `Anaconda` `Streamlit` `Render` `Firebase` `Git` |
| **Languages** | `Python` `C++` `C` `Java` `SQL` |

<br/>

## `05` &nbsp;How I Work

- **First principles before implementation.** I'd rather spend a day understanding why a method works than a week debugging a copied one.
- **Ablations over anecdotes.** If a change improved the metric, I want to know which change and by how much — otherwise it's superstition.
- **Explanations ship with predictions.** For anything clinical or high-stakes, an unexplained output is an unusable output.
- **Documented trade-offs.** When a decision isn't obvious, the reasoning goes in the repo, not just my head.

<br/>

## `06` &nbsp;Signals

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ayushmanbhatt07&theme=tokyonight&hide_border=true&hide_title=true&include_all_commits=true&count_private=true&show_icons=true&hide=issues&icon_color=CBA6F7&text_color=CDD6F4&bg_color=1a1b27&ring_color=7AA2F7" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ayushmanbhatt07&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&layout=compact&langs_count=6&title_color=7AA2F7&text_color=CDD6F4&bg_color=1a1b27" height="165" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ayushmanbhatt07&bg_color=1a1b27&color=CDD6F4&line=7AA2F7&point=CBA6F7&area=true&area_color=7AA2F7&hide_border=true&custom_title=Commit%20Activity&radius=4" width="96%" />

</div>

<br/>

## `07` &nbsp;Contact

Happy to talk about interpretability research, medical imaging pipelines, agentic architectures, or anything at the intersection. Fastest route is LinkedIn.

<div align="center">
<br/>

<a href="https://linkedin.com/in/ayushman-bhatt-564927343"><img src="https://img.shields.io/badge/Start_a_conversation-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1a1b27" /></a>

<br/><br/>

<sub>The measure of an AI system is not only what it predicts — but whether it can be understood, audited, and trusted.</sub>

</div>
