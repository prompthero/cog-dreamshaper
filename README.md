# Dreamshaper Cog for Replicate API

Model: [Dreamshaper](https://prompthero.com/ai-models/dreamshaper-download)

Author: [@prompthero](prompthero.com)

## Instructions

---

First, `git clone` this repo and cd into it:

```
git clone https://github.com/prompthero/cog-dreamshaper

cd cog-dreamshaper
```

### Install cog:

```
sudo curl -o /usr/local/bin/cog -L https://github.com/replicate/cog/releases/latest/download/cog_`uname -s`_`uname -m`

sudo chmod +x /usr/local/bin/cog
```

### Try to run a prediction:

```
sudo cog run script/download-weights
```

### Download the weights:

```
sudo cog predict -i prompt="monkey scuba diving"
```

### Create a model in Replicate:

### Publish your model

```
cog login
cog push r8.im/<your-username>/<your-model-name>
```
