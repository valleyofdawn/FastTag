# FastTag

**FastTag** is a fast, interpretable, and recursive marker-based cell annotation method for single-cell RNA-seq data.

It uses known marker sets to score cells and iteratively splits them based on expression patterns, producing robust subtype annotations with minimal prior assumptions.

---

## Features

- Automated scoring of marker gene sets
- Recursive splitting of heterogeneous populations
- Marker pruning and filtering
- Compatible with `scanpy` and `AnnData`
- Easily extendable and interpretable

---

## Installation

Coming soon as a pip-installable package. For now, clone the repository:

```bash
git clone https://github.com/yourusername/fasttag.git
cd fasttag
