# DEGauss Official Website

This is the official website for DEGauss - Dynamic-Static Decomposition with Gaussian Splatting for Distractor-free 3D Reconstruction.

## About DEGauss

DEGauss is a cutting-edge computer vision framework that revolutionizes 3D scene reconstruction through dynamic-static decomposition using Gaussian splatting techniques. Our technology enables robust 3D reconstruction in challenging environments with dynamic objects and distractors.

## Features

- **Advanced 3D Reconstruction**: State-of-the-art Gaussian splatting technology
- **Dynamic-Static Decomposition**: Intelligent separation of dynamic and static elements
- **Distractor-Free Processing**: Robust handling of distractors and noise
- **Egocentric Data Support**: Specialized algorithms for first-person perspective data
- **High Performance**: Optimized algorithms for real-time processing
- **Easy Integration**: Simple APIs and comprehensive documentation

## Installation

### Python Package
```bash
pip install degauss
```

### Conda
```bash
conda install -c conda-forge degauss
```

### From Source
```bash
git clone https://github.com/BatFaceWayne/DeGauss.git
cd DeGauss
pip install -e .
```

## System Requirements

- Python 3.8 or higher
- CUDA-compatible GPU (recommended)
- 8GB RAM minimum, 16GB recommended
- OpenCV 4.5+
- PyTorch 1.9+

## Quick Start

```python
import degauss

# Initialize DEGauss
model = degauss.DeGaussModel()

# Load your data
data = degauss.load_data("path/to/your/data")

# Process the scene
result = model.process(data)

# Extract reconstructed scene
scene = result.get_scene()
```

## Documentation

For detailed documentation, tutorials, and API reference, visit our [documentation page](https://lzhmeng.github.io/DEGauss.github.io/#documentation).

## Research

DEGauss is research that was presented at ICCV 2025. If you use DEGauss in your research, please cite:

```bibtex
@inproceedings{degauss2025,
  title={DeGauss: Dynamic-Static Decomposition with Gaussian Splatting for Distractor-free 3D Reconstruction},
  author={Author Name and Others},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  year={2025}
}
```

## Community

- **GitHub**: [https://github.com/BatFaceWayne/DeGauss](https://github.com/BatFaceWayne/DeGauss)
- **Issues**: [Report bugs and feature requests](https://github.com/BatFaceWayne/DeGauss/issues)
- **Discussions**: [Community discussions](https://github.com/BatFaceWayne/DeGauss/discussions)

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

## Contact

For questions and support, please contact us at contact@degauss.org or open an issue on GitHub.

---

© 2024 DEGauss Team. All rights reserved.