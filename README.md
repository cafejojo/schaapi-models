<p align="center">
    <br>
    <img src="https://user-images.githubusercontent.com/15815208/41853512-38dd02c4-788e-11e8-8e56-7035e66eabb7.png" width="400">
    <br>
    Early detection of breaking changes based on API usage
    <br>
    <br>
    <br>
</p>
    
[![Travis build status][travis-status]](https://travis-ci.org/cafejojo/schaapi-models)
[![AppVeyor build status][appveyor-status]](https://ci.appveyor.com/project/CafeJojo/schaapi-models/branch/master)
[![Codecov][codecov-status]](https://codecov.io/gh/cafejojo/schaapi-models/)
[![Schaap][schaap-status]](https://github.com/cafejojo/schaapi)
[![Built with love][baby-dont-hurt-me]](https://github.com/cafejojo/)

This module contains the models and interfaces of Schaapi, and is not executable. Please see the [main repo](https://github.com/cafejojo/schaapi) for more information.

## Requirements and Installation
Schaapi requires JRE 8 and has been tested on Windows and Unix systems.

## Changelog
Please see [releases](../../releases) for more information on what has changed recently.

## Testing
``` bash
$ ./gradlew check
```

## Documentation
``` bash
$ ./gradlew dokka
```

## Publishing
``` bash
$ ./gradlew uploadArchives --no-daemon
```

## Contributing
Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security
If you discover any security-related issues, please email security@cafejojo.org instead of using the issue tracker.

## Credits
- [Joël Abrahams](https://github.com/JSAbrahams)
- [Georgios Andreadis](https://github.com/gandreadis)
- [Casper Boone](https://github.com/casperboone)
- [F.W. Dekker](https://github.com/FWDekker)
- [All contributors](../../contributors)

## License
The MIT License (MIT). Please see the [license file](LICENSE) for more information.

[travis-status]: https://img.shields.io/travis/cafejojo/schaapi-models/master.svg?style=for-the-badge&logo=data:image/png;base64,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
[appveyor-status]: https://img.shields.io/appveyor/ci/CafeJojo/schaapi-models/master.svg?style=for-the-badge&logo=windows
[codecov-status]: https://img.shields.io/codecov/c/github/cafejojo/schaapi-models/master.svg?style=for-the-badge
[schaap-status]: https://img.shields.io/badge/Contains-%F0%9F%90%91-FF69B4.svg?style=for-the-badge
[baby-dont-hurt-me]: https://img.shields.io/badge/built%20with-%E2%9D%A4%EF%B8%8F-red.svg?style=for-the-badge
