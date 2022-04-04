# Depth First Search Visualizer


Visualizing Depth First Search Algorithm which is an algorithm that traverses or searches tree data structures and graphs. The algorithm starts at the root of a tree and follows each branch as far as it can, then backtracks until it encounters an unexplored path, and explores it. In simple words, depth-first search starts by the exploration of the graph to its deepest point. When the deepest point is reached, it backtracks to a previous unex-
plored neighbor. This process is then repeated until the whole graph is explored. If an isolated vertex is identified to be unvisited by the end of the process, DFS would be carried again starting from that vertex.


## Running DFS Visualizer

To run `DFS-Visualizer`, pip install using:

```bash
git clone https://github.com/omarrayyann/DFS-Visualizer
cd qudra
pip install --upgrade .
```

If you also want to download the dependencies needed to run optional tutorials, please use `pip install --upgrade .[dev]` or `pip install --upgrade '.[dev]'` (for `zsh` users).


#### Installation for Devs

If you intend to contribute to this project, please install `qudra` in editable mode as follows:
```bash
git clone https://github.com/qcenergy/qudra.git
cd qudra
pip install -e .[dev]
```

python3 -m venv venv
. venv/bin/activate
Please use `pip install -e '.[dev]'` if you are a `zsh` user.

#### Building documentation locally

Set yourself up to use the `[dev]` dependencies. Then, from the command line run:
```bash
mkdocs build
```

<img width="801" alt="Screen Shot 2022-03-29 at 12 42 43 PM" src="https://user-images.githubusercontent.com/77675540/160571282-87732406-67c7-4517-bae9-6104a6249773.png">

Then, when you're ready to deploy, run:
```bash
mkdocs gh-deploy
```

