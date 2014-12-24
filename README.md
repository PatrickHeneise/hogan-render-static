hogan-render-static
===================

This node.js script has been written to compile Hogan files without the need of Express, Grunt, Gulp or any other middleware/build tool. You can simply run it from an npm script (the initial purpose for this), as it is used in the [npm static boilerplate](https://github.com/blendedio/npm-static-boilerplate).

Check out the upper part to make sure the config is right:

    template_dir = path.resolve(__dirname, 'markup')
    output_dir = path.resolve(__dirname, 'dist')
    layout = 'layout.html'
