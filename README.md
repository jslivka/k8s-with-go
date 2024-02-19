# Setup

* Install JupyterLab: https://jupyter.org/install

[https://github.com/janpfeifer/gonb/tree/main](gonb)

```sh
go install github.com/janpfeifer/gonb@latest && \
  go install golang.org/x/tools/cmd/goimports@latest && \
  go install golang.org/x/tools/gopls@latest

gonb --install
```

# Run

```
jupyter notebook
```

* Open `k8swithgo.ipynb`
