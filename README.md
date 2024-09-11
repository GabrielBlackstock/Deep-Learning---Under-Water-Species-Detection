YOLOv10 Underwater Species Detection

This repository contains a YOLOv10 deep learning model developed for my MSc dissertation on underwater species detection. The model aims to accurately identify and classify marine species from underwater images.

Model Summary:
- Layers: 285
- Parameters: 2,697,926
- GFLOPs: 8.2

Detection Performance:
- Overall Performance:
  - Precision: 72.5%
  - Recall: 73.8%
  - mAP50: 75.4%
  - mAP50-95: 49.5%

Species-Specific Results:

| Species               | Precision | Recall | mAP50 | mAP50-95 |
|-----------------------|-----------|--------|-------|----------|
| Acanthurus-Nigrofuscus | 89.9%     | 100%   | 98.6% | 78.6%    |
| Balkan-Wrasse          | 77.4%     | 73.3%  | 81.1% | 55.3%    |
| Brill                  | 51.1%     | 70.6%  | 64.1% | 30.3%    |
| Brown Crab             | 86.2%     | 100%   | 96.3% | 63.7%    |
| Jellyfish              | 56.5%     | 57.1%  | 72.3% | 43.1%    |
| Pollock                | 82.5%     | 82.5%  | 86.5% | 63.6%    |
| Shrimp                 | 64.1%     | 33.3%  | 28.8% | 12.1%    |

The model is trained on a custom dataset, utilizing YOLOv10’s efficient architecture for high performance on real-world underwater imagery.
