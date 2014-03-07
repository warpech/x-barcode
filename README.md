# &lt;x-barcode&gt;

Web Component wrapper for UPC-A (for now) barcode using Polymer.

> Maintained by [Tomomi Imura](https://github.com/girliemac).

## Demo

> [Check it live](http://girliemac.github.io/x-barcode).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="bower_components/platform/platform.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/x-barcode.html">
	```

3. Start using it!

	```html
	<x-barcodet></x-barcode>
	```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [NodeJS](http://nodejs.org/download/).
2. Install [GruntJS](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g grunt-cli
    ```

3. Install local dependencies:

    ```sh
    $ npm install
    ```

4. Run a local server and open `http://localhost:8000`.

    ```sh
    $ grunt connect
    ```
    
## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`code`      | *int*                  | `00000000000`               | The first 11 disit of UPC-A code. The last digit (check sum) will be calculated.
`color`      | *string* 	   | `black`               | Color name or hex


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/girliemac/x-barcode/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)

## Yay, it works!

![scanning the barcode](https://lh4.googleusercontent.com/-cUBi64JvpGA/UwWk1J2iDCI/AAAAAAAAKH4/1d01QeASmls/w433-h770/14+-+1)