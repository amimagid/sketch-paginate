# sketch-paginate
Pagination plugin for sketch app.

This is a work in progress plugin to add pagination to Artboards. Right now you’ll have to create a text layer with the layer name `{pagination}` in each Artboard. And each dartboard will have to be sorted by Sketch's default ordering (first Artboard in the layer list is actually the last Artboard).

Disclaimer: It was highly inspired by bomberstudios's [Sketch Commands > Numberize](https://github.com/bomberstudios/sketch-commands/tree/master/Sketch%20Commands.sketchplugin/Contents/Sketch/Numberize)

---

TO-DO
- [ ] fire a dialog window to define pagination appearance (ex: `page 1/2` or just `1/2 ` or even `page 1 of 2` etc)
- [ ] make it work with new symbols
- [ ] automatically create text layer with pagination
- [ ] define position of that auto-created layer
