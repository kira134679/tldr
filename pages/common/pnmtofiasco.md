# pnmtofiasco

> Convert a PNM image to a compressed FIASCO file.
> More information: <https://netpbm.sourceforge.net/doc/pnmtofiasco.html>.

- Convert a PNM image to a compressed FIASCO file:

`pnmtofiasco {{path/to/file.pnm}} > {{path/to/file.fiasco}}`

- Specify the input files through a pattern:

`pnmtofiasco {{[-i|--image-name]}} "{{img[01-09+1].pnm}}" > {{path/to/file.fiasco}}`

- Specify the compression quality:

`pnmtofiasco {{[-q|--quality]}} {{quality_level}} {{path/to/file.pnm}} > {{path/to/file.fiasco}}`

- Load the options to be used from the specified configuration file:

`pnmtofiasco {{[-f|--config]}} {{path/to/fiascorc}} {{path/to/file.pnm}} > {{path/to/file.fiasco}}`
