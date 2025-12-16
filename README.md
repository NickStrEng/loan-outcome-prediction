# Startup guide

Follow these simple steps to run the data, model training and evaluation pipeline for loan application outcome prediction.

## Prerequisites

Before starting, verify you have:
- Python 3.14 installed (`python3 --version`)
- Git installed - `git --version`

## Setup

### 1. Install uv

**macOS/Linux:**
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

**Windows:**
```powershell
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

**Verify installation:**
```bash
uv --version
```

### 2. Clone repository from GitHub


```bash
# Clone from GitHub
git clone https://github.com/NickStrEng/loan-outcome-prediction.git

# Navigate to project directory
cd loan-outcome-prediction
```

## 3. Set up virtual environment and install dependencies

```bash
# uv automatically reads pyproject.toml and installs packages
uv sync
```

This command:
- Creates virtual environment in `.venv/`
- Installs all dependencies from `pyproject.toml`
- Creates/updates `uv.lock` for reproducible builds

## Build and evaluate models

Just run the notebook end-to-end
