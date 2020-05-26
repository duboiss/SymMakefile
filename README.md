# SymMakefile
SymMakefile is a simple Makefile for symfony developers.

You can use it in your symfony projects for automate some tasks during your development.

More info about [Makefile](https://en.wikipedia.org/wiki/Makefile).

## Examples
- make lint : run all linters (twig, xliff, yaml and service container)
- make purge : delete cache and logs
- make start : install project (including dependencies and database), load fixtures and launch web server

## Prerequisites
[Symfony binary](https://github.com/symfony/cli) : you can do without it if you remove the associated commands from the Makefile.

Help command requires unix tools (grep, sed...) to be installed.

#### Windows users
You need to install [Make for Windows](http://gnuwin32.sourceforge.net/packages/make.htm) and add it in your path.

For unix tools, if you use git, select "Use Git and optional Unix tools from the Command prompt" during its installation.

## Usage
Display all available commands:
```sh
$ make help
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Alternatives
- https://github.com/mykiwi/symfony-bootstrapped
- https://www.strangebuzz.com/en/snippets/the-perfect-makefile-for-symfony

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
