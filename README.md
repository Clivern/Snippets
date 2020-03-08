<p align="center">
    <img alt="Snippets Logo" src="https://raw.githubusercontent.com/clivern/Snippets/master/img/logo.png?v=1.0.0" width="150" />
    <h3 align="center">Snippets</h3>
    <p align="center">Sublime Text Snippets</p>
    <p align="center">
        <a href="https://github.com/Clivern/Snippets/releases"><img src="https://img.shields.io/badge/Version-1.0.0-red.svg"></a>
        <a href="https://github.com/Clivern/Snippets/blob/master/LICENSE"><img src="https://img.shields.io/badge/LICENSE-MIT-orange.svg"></a>
    </p>
</p>


## Documentation

#### Installation:

Add the package to Sublime Text 3 packages directory:

```zsh
$ cd $HOME/Library/Application\ Support/Sublime\ Text\ 3/Packages
$ export SNIPPETS_LATEST_VERSION=$(curl --silent "https://api.github.com/repos/Clivern/Snippets/releases/latest" | jq '.tag_name' | sed -E 's/.*"([^"]+)".*/\1/')
$ rm -rf Snippets
$ curl -sL https://github.com/Clivern/Snippets/archive/{$SNIPPETS_LATEST_VERSION}.tar.gz | tar xz
$ mv Snippets-* Snippets
```

#### MySQL Snippets

`clivern-mysql-db-create`: Create Database.
`clivern-mysql-db-drop`: Drop Database.


## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, Snippets is maintained under the [Semantic Versioning guidelines](https://semver.org/) and release process is predictable and business-friendly.

See the [Releases section of our GitHub project](https://github.com/clivern/beetle/releases) for changelogs for each release version of snippets. It contains summaries of the most noteworthy changes made in each release.


## Bug tracker

If you have any suggestions, bug reports, or annoyances please report them to our issue tracker at https://github.com/clivern/beetle/issues


## Security Issues

If you discover a security vulnerability within snippets, please send an email to [hello@clivern.com](mailto:hello@clivern.com)


## Contributing

We are an open source, community-driven project so please feel free to join us. see the [contributing guidelines](CONTRIBUTING.md) for more details.


## License

© 2020, clivern. Released under [MIT License](https://opensource.org/licenses/mit-license.php).

**Snippets** is authored and maintained by [@clivern](http://github.com/clivern).
