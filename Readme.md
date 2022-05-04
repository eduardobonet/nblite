# NBLite: Minimalistic ClientSide Notebooks

Check it out: https://eduardobonet.gitlab.io/nblite/

![example](./img/example.png)

NBLite is a proof of concept that creates a client side runnable version of a notebook, adding minimal styling and content, with the goal of exploring PyScript.

NBLite parses a notebook, creates the HTML, identifies the depedencies with 60 lines of javascript.

## TODO

- [ ] Custom pyenv paths 
- [ ] Just show the scripts instead of using a repl
- [ ] Styling injection
- [ ] Add repl for exploration
- [ ] Lines should continue
- [ ] Better output support (plt.plot(x,y) for example)

## Opening local files

To open a notebook locally, you will need to run your browser with CORS disabled:

- [Instruction on opening Chrome without CORS](https://stackoverflow.com/questions/3102819/disable-same-origin-policy-in-chrome)