# README TOO

I'm quietly updating this as I go to work with Apple Silicon and my local setup.

## Local setup

### Install these via Homebrew

    pyenv
    pyenv-virtualenv

### Install python

    pyenv install 3.13

### Create and activate the virtualenv and install Python packages

    pyenv virtualenv 3.13 dlp

    pyenv activate dlp

    # This is the Apple Silicon PyTorch

    pip install --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu

    pip install jupyter

### Open the project in VS Code

Assuming you have some plugins that work with Jupyter, Python, etc.

Open the first Jupyter notebook and select the `dlp` environment as the runtime.
