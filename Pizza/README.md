# Amfphp Pizza for Apache Royale

The Amfphp _Pizza_ example, ported to [Apache Royale](https://royale.apache.org/).

## Server

The backend for this sample is included with the Amfphp distribution.

- [Clone Amfphp from Github](https://github.com/silexlabs/amfphp-2.0)

- Start a local HTTP server supporting PHP on port **8080** where the server's document root directory is the root of the Amfphp repository.

> It's probably easiest to use PHP's built-in development web server.

```sh
git clone https://github.com/silexlabs/amfphp-2.0.git
cd amfphp-2.0
php -S localhost:8080
```

## Build

- Copy this sample project's root directory into _[amfphp root]/Examples/Royale/Pizza/_.

- Open the project in your favorite IDE that supports Apache Royale.

- Run your IDE's build command, or use [asconfigc](https://npmjs.org/package/asconfigc) to build from the command line.

Then, open the following URL in a web browser:

http://localhost:8080/Examples/Royale/Pizza/bin/js-debug/index.html