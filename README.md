# Relace - A Twitter Bootstrap Migration Tool
This is the beta of the alpha.

### Usage

```sh
node app <globString> [options]

globString     Glob pattern for the files to be processed.

Options:
   -o, --outputDirectory   Write processed files to this directory

```

Process and replace a single file.

```sh
node app ./path/to/file.html
```

Process and replace multiple files using a glob pattern.

```sh
node app ./path/to/**/*.html
```

Process multiple files using a glob pattern and save to a different directory.

```sh
node app ./path/to/**/*.html --outputDirectory=./output
```