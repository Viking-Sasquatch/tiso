# TISO

The TISO (Title Industry Standards Organization) project aims to provide a standard set of data structures and helper libraries for use in exchanging data.

## Getting Started

### Prerequisites

- [NodeJS](https://nodejs.org/en/) (10.16 or higher)

### Installation

To get started with TISO, run the following from the commandline:

1. Clone the repo (`git clone git@github.com:Viking-Sasquatch/tiso.git`)
2. Install all of the node packages (`npm install`)

To get started with TISO, just clone this repo and review the json examples and schemas in the `src` folder.


## Running the tests


To validate JSON files individually, install jsonlint:

```
npm install jsonlint -g
```

Validate a file like this:

```
jsonlint myfile.json
```

## Built With

- [JSON](http://json.org/) - Data interchange format used
- [JSON Schema](http://json-schema.org/) - Standard for JSON payload schema
- [JSONschema.net](https://jsonschema.net/) - Initial schema creation and editing
- [JSONLint](https://jsonlint.com/) - Validation of JSON

## Contributing

Please read [CONTRIBUTING.md](https://github.com/Viking-Sasquatch/tiso/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

- **Ken Taylor** - _Initial work_ - [Ken Taylor](https://github.com/switchspan)
- **Luke Champ** - _Additional schemas_ - [Luke Champ](https://github.com/thechampl)

<!-- See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project. -->

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

