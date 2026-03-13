# GUI Benchmark Analysis

## Research Goals
The objective of this repository is to investigate GUI grounding benchmarks, focusing on the **ScreenSpot** benchmark. This work supports a PhD thesis on GUI grounding, aiming to evaluate and compare the performance of advanced vision-language models on mobile UI screenshots.

## Background
### ScreenSpot Benchmark
ScreenSpot is a benchmark for evaluating the ability of vision-language models to perform GUI grounding on mobile app screenshots. Introduced in 2024, it consists of 5,000 screenshots from popular Android apps, annotated with bounding boxes for interactive UI elements such as buttons, icons, and text fields. The primary task is *spotting*, where models must predict bounding boxes for specified elements via natural language queries. Performance is measured by accuracy in localizing correct elements. Leading models like GPT‑4V achieve around **31%** accuracy, highlighting challenges in precise localization and handling diverse UI layouts. The benchmark emphasizes real‑world GUI understanding for applications in mobile automation and accessibility.

### Computer Vision Context
Computer vision is a field of artificial intelligence that enables computers to derive meaningful information from digital images, videos, and other visual inputs. It encompasses tasks such as image classification, object detection, semantic segmentation, and visual question answering. Modern approaches rely heavily on deep learning models like convolutional neural networks (CNNs) and transformers, often combined with language models to form vision‑language systems. These techniques underpin the ability of models to interpret and ground textual descriptions within graphical user interfaces, as exemplified by the ScreenSpot benchmark.

## Repository Structure
- `README.md` – Overview and research background (this file).
- `model_performance.json` – JSON file in the `benchmark-data` branch summarizing model accuracies on ScreenSpot.
- Issues – Tracking further data collection and research tasks.

## Next Steps
- Expand dataset collection to include **ScreenSpot‑Pro** and other GUI grounding benchmarks.
- Conduct experiments with additional vision‑language models.
- Document findings and refine methodology.
