# AI-Generated Fall Data: Assessing LLMs and Diffusion Model for Wearable Fall Detection

Training fall detection systems is challenging due to the scarcity of real-world fall data, particularly from elderly individuals. To address this, we explore the potential of Large Language Models (LLMs) for generating synthetic fall data. This study evaluates text-to-motion (T2M, SATO, ParCo) and text-to-text models (GPT4o, GPT4, Gemini) in simulating realistic fall scenarios. We generate synthetic datasets and integrate them with four real-world baseline datasets to assess their impact on fall detection performance using a Long Short-Term Memory (LSTM) model. Additionally, we compare LLM-generated synthetic data with a diffusion-based method to evaluate their alignment with real accelerometer distributions. Results indicate that dataset characteristics significantly influence the effectiveness of synthetic data, with LLM-generated data performing best in low-frequency settings (e.g., 20Hz) while showing instability in high-frequency datasets (e.g., 200Hz). While text-to-motion models produce more realistic biomechanical data than text-to-text models, their impact on fall detection varies. Diffusion-based synthetic data demonstrates the closest alignment to real data but does not consistently enhance model performance. An ablation study further confirms that the effectiveness of synthetic data depends on sensor placement and fall representation. These findings provide insights into optimizing synthetic data generation for fall detection models.

## Paper (preprint) can be found [HERE](https://arxiv.org/abs/2505.04660).

# Citations
Please cite this paper if you use synthetic data generated as part of this experimental study:
> Alamgeer, S., Souissi, Y., & Ngu, A. H. H. (2025). AI-Generated Fall Data: Assessing LLMs and Diffusion Model for Wearable Fall Detection. arXiv. https://arxiv.org/abs/2505.04660

```text
@misc{alamgeer2025syntheticfalldata,
      title={AI-Generated Fall Data: Assessing LLMs and Diffusion Model for Wearable Fall Detection}, 
      author={Sana Alamgeer and Yasine Souissi and Anne H. H. Ngu},
      year={2025},
      eprint={2505.04660},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2505.04660}, 
}
```
