# gsnodegraph

Powerful custom node graph widget for wxPython, created to be used in [Gimel Studio](https://github.com/GimelStudio/GimelStudio).

Highly inspired by the overall look of the nodes in Blender 3D, if you couldn't tell. So if you've always wanted to find a node editor similar to Blender's, this is likely your repo. ;)

It is specifically aimed towards an image-editing node editor setup and is setup with styling specific to Gimel Studio by default. However, many colors and settings can be changed via the ``constants.py`` file and/or it can be adapted and changed for other node graph use-cases with a little knowlege of wxPython.


## Usage

Simply ```pip install gsnodegraph``` and run the ```main.py``` found in this repo to see the node graph demo. The ``nodes.py`` file in the ``nodes`` folder gives a demo of how to setup nodes to work with the nodegraph.

For a real-life example of this node graph in action, see [Gimel Studio](https://github.com/GimelStudio/GimelStudio) a node-based 2D image editor for which this node graph is originally intended.


## Status & Roadmap

Most of the functionality for a basic node graph is already here, with more features and fixes planned.

**Roadmap/TODO**

- [x] Zoom/pan canvas (still buggy)
- [x] Basic node drag n' drop
- [x] Box selection
- [x] Multi-selection (still buggy)
- [x] Sockets and wires
- [x] Parameters
- [x] Parameter socket ids
- [x] PYPI package
- [x] Node delete, duplicate and mute
- [ ] Refactor out context menu so that it can be created/edited outside of this package
- [x] Support for image thumbnails with expand and collapse functionality [#24](https://github.com/GimelStudio/GimelStudio/issues/24)
- [x] Support for different input datatypes [#83](https://github.com/GimelStudio/GimelStudio/issues/83)
- [ ] Auto connect nodes when dropped/dragged over a wire
- [ ] Keyboard shortcuts
- [x] Configurable settings
- [x] Lock zoom to a predefined range
- [ ] Node groups (or "nodes inside of a node") [#81](https://github.com/GimelStudio/GimelStudio/issues/81)
- [ ] Swap node inputs functionality
- [ ] Set image as background of node graph (WIP)

**Extra possiblities (may or may not happen...or may not be included in this package)**

- [ ] Nodegraph minimap?
- [ ] Support for multiple output nodes?
- [ ] Auto-arrange nodes in node graph (organize the nodes)?


## Contributing

All contributions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for details. Feel free to open a PR or ask questions. :)


## Releasing on PyPI

Navigate to the root directory

Run ``py -m build``

Then run ``twine upload dist/*`` and follow the prompts.


## License

gsnodegraph is licensed under the Apache 2.0 license. Feel free to use this as a starting point, etc for your own projects.
