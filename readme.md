# Expertise-Aware Federated Learning with Asymmetric Knowledge Distillation

**Short Name:** FL-KD-Expertise  
**Status:** Research Prototype

---

## Abstract

This repository implements an expertise-aware federated learning framework that leverages asymmetric knowledge distillation to enhance model performance across heterogeneous client devices. The approach addresses the challenge of knowledge transfer in federated settings where clients possess varying levels of computational resources and data expertise.

---

## Authors

- **Shashwat Kumar**
- **Shourya Tiwari**
- **Shilpa Bade-Gite**

---

## Features

- **Expertise-Aware Client Selection**: Intelligent selection of clients based on their expertise levels
- **Asymmetric Knowledge Distillation**: Efficient knowledge transfer between models of varying capacities
- **Federated Learning Framework**: Built on Flower (FLwr) for scalable federated training
- **Heterogeneous Client Support**: Accommodates clients with diverse computational capabilities

---

## Installation

### Prerequisites

- Python 3.8 or higher
- CUDA-capable GPU (recommended)

### Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd expertise-aware-federated-learning
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Project Structure

```
expertise-aware-federated-learning/
├── data/
│   ├── raw/           # Raw datasets
│   ├── interim/       # Intermediate processed data
│   └── processed/     # Final processed datasets
├── src/
│   ├── data/          # Data loading and preprocessing utilities
│   ├── models/        # Model architectures
│   ├── fl/            # Federated learning components
│   ├── distillation/  # Knowledge distillation modules
│   └── utils/         # Utility functions
├── experiments/       # Experiment scripts and configurations
├── notebooks/         # Jupyter notebooks for analysis
├── tests/             # Unit and integration tests
└── docs/              # Documentation
```

---

## Usage

### Basic Example

```python
# Example usage will be added here
# Refer to experiments/ directory for detailed examples
```

### Running Experiments

```bash
# Navigate to experiments directory
cd experiments

# Run federated learning experiment
python run_federated_experiment.py
```

---

## Dependencies

Key dependencies include:
- **PyTorch** (≥2.0): Deep learning framework
- **Flower (FLwr)**: Federated learning framework
- **Transformers**: Pre-trained model support
- **Weights & Biases (wandb)**: Experiment tracking
- **NumPy, Pandas, scikit-learn**: Data processing and evaluation

See `requirements.txt` for the complete list of dependencies.

---

## Citation

If you use this code in your research, please cite:

```bibtex
@misc{fl-kd-expertise2024,
  title={Expertise-Aware Federated Learning with Asymmetric Knowledge Distillation},
  author={Kumar, Shashwat and Tiwari, Shourya and Bade-Gite, Shilpa},
  year={2024},
  note={Research Prototype}
}
```

---

## License

This project is a research prototype. Please contact the authors for licensing information.

---

## Contact

For questions, issues, or collaborations, please contact the authors or open an issue in the repository.

---

## Acknowledgments

This work is part of ongoing research in federated learning and knowledge distillation.

---

*Last updated: 2024*
