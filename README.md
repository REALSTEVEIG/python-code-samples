# Python Code Samples

Three self-contained Python projects. Each has its own `README.md`, `pyproject.toml`, `src/` package and `tests/`.

| Project | Package | Focus |
| --- | --- | --- |
| [`image-processing/`](image-processing/) | `imgfeatures` | Normalization, grayscale conversion, convolution, Sobel/Canny edge detection, HOG-style feature extraction (NumPy, OpenCV for comparison) |
| [`ml-from-scratch/`](ml-from-scratch/) | `mlscratch` | k-nearest neighbors and k-means clustering in NumPy, with input validation and complexity analysis |
| [`graph-toolkit/`](graph-toolkit/) | `graphkit` | Dijkstra, BFS/DFS, Bellman-Ford, topological sort and more, in pure standard-library Python |

## Running a project

```bash
cd image-processing        # or ml-from-scratch / graph-toolkit
python -m venv .venv && source .venv/bin/activate
pip install -e ".[dev]"
pytest
```
