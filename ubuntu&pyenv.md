## Start Container
```
docker run -it --rm ubuntu:24.04
```

## Commands
```
apt update
apt install -y curl git gcc make zlib1g-dev libssl-dev liblzma-dev sqlite3
curl https://pyenv.run | bash
PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
pyenv init -
pyenv install 3.6.15
pyenv versions
pyenv global 3.6.15
python --version
```
