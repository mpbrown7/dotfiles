echo 'export PYENV_ROOT="$HOME/.pyenv"' >> dot_zshrc
echo 'command -v pyenv >/dev/null || export PATH="$PYENV_ROOT/bin:$PATH"' >> dot_zshrc
echo 'eval "$(pyenv init -)"' >> dot_zshrc