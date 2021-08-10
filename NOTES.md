# Setup

Setup dreamerv2:
```bash
cd
git clone https://github.com/magamba/dreamerv2
cd dreamerv2
conda env create -f environment.yml
conda activate dreamerv2
pip install --editable .
```

Setup mini atari:
```bash
cd
git clone https://github.com/kenjyoung/MinAtar.git
cd MinAtar
conda env create -f environment.yml
pip install --editable .
```

Comment out line 2 (GUI) in `MinAtar/environments/__init__.py` if running headless.

Download `results.zip` and extract to `results_official` in the repo root.
