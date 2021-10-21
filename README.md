# gsnodegraph

Custom node graph widget for wxPython, created to be used in [Gimel Studio](https://github.com/GimelStudio/GimelStudio).

It is specifically aimed towards an image-editing node graph setup and has styling specific to Gimel Studio, but it can be adapted for other node graph use-cases.

**NOT YET READY FOR PRODUCTION!**

Highly inspired by the look of Blender's nodes (with adjustments), if you couldn't tell. ;)


# Usage

Simply ```pip install gsnodegraph``` and run the ```main.py``` found in this repo to see the WIP nodegraph demo. The ``nodes.py`` file in the ``nodes`` folder gives a demo of how to setup nodes to work with the nodegraph.


# Status & Roadmap

Currently, the basic node graph interaction is working, but it's *not production-ready* quite yet!

**Roadmap/TODO**

- [x] Zoom/pan canvas (still buggy)
- [x] Basic node drag n' drop
- [x] Box selection
- [x] Multi-selection (still buggy)
- [x] Sockets and wires
- [x] Parameters
- [ ] Parameter socket ids
- [x] Make PYPI package
- [x] Implement node delete, duplicate and mute
- [ ] Refactor out context menu so that it can be created/edited outside of this package
- [ ] Support image thumbnails with expand and collapse functionality [#24](https://github.com/GimelStudio/GimelStudio/issues/24)
- [ ] Support multiple input datatypes [#83](https://github.com/GimelStudio/GimelStudio/issues/83)
- [ ] Auto connect nodes when dropped/dragged over a wire
- [ ] Keyboard shortcuts
- [ ] Configuration settings
- [ ] Lock zoom to a predefined range
- [ ] Node groups (or "nodes inside of a node") [#81](https://github.com/GimelStudio/GimelStudio/issues/81)
- [ ] Swap node inputs functionality
- [ ] Set image as background of node graph

**Extra possiblities**

- [ ] Nodegraph minimap?
- [ ] Support for multiple output nodes?
- [ ] Auto-arrange nodes in node graph (organize the nodes)?


# Contributing

All contributions are welcome! Feel free to open a PR or ask questions.
