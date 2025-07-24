# Cross Weather Expert Network for Adaptive Image Restoration

## (Work in Progress / Under Review)

This repository contains supporting figures and preliminary results for our ongoing research paper, "Cross Weather Expert Network for Adaptive Image Restoration."

**Paper Status:** This work is currently **[e.g., under review for AAAI 2026 / undergoing revisions / submitted to Journal X]**. We plan to make the full code, pre-trained models, and comprehensive instructions publicly available upon acceptance and publication.

## Project Overview

This research introduces the Cross Weather Expert Network (CWEN), a novel approach for robust and adaptive image restoration under diverse weather conditions (e.g., rain, snow, haze). Our method leverages specialized expert modules and a cross-weather attention mechanism to effectively integrate their outputs, leading to superior performance compared to existing methods.

## Available Content

Currently, this repository provides:

* **Qualitative Results:** Visual comparisons showcasing the effectiveness of our CWEN model against various state-of-the-art methods across different weather degradations.
* **Quantitative Summaries:** Key performance metrics (e.g., PSNR, SSIM) demonstrating the superior restoration quality achieved by CWEN.
* **Architectural Diagrams:** Visual representations of our proposed network architecture.

Please explore the `figures/` and `results_summary/` directories.

## Future Plans (Coming Soon!)

Upon the official publication of our paper, this repository will be updated to include:

* **Full PyTorch (or TensorFlow, etc.) Implementation:** Complete source code for training and evaluation.
* **Pre-trained Models:** Checkpoints for easy inference and reproducibility.
* **Detailed Setup and Usage Instructions:** Comprehensive guides for environment setup, data preparation, training, testing, and result generation.
* **Dataset Links:** Pointers to all datasets used for training and evaluation.

## Figures & Results Highlights

*(Optional: You can embed a few of your most compelling figures directly here to give visitors a quick visual summary.)*

**Example Qualitative Comparison (Rain Removal):**
![Rain Removal Example](figures/qualitative_rain_example.png)
*Comparison of input, degraded (rainy), restored by SOTA, and restored by CWEN.*

**Example Quantitative Table:**
*(You could link to a CSV or just embed a small table directly from your paper's results.)*
| Method       | PSNR (Avg) | SSIM (Avg) |
| :----------- | :--------- | :--------- |
| SOTA Method 1 | 28.5       | 0.85       |
| Our CWEN     | **31.2** | **0.91** |

## Contact

For any inquiries regarding this research, please feel free to contact [Your Name] at [your.email@example.com].

## License

*(Optional for now. If you want to specify how others can use your figures, you can add a Creative Commons license here, e.g., [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Otherwise, you can leave it out until the code is released and a software license is more relevant.)*
