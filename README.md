# Waffle issue when chaining .to.emit.withArgs

The purpose of this example is to demonstrate how in certain situations the when chaining multiple `.to.emit` checks in a Test, the previous validations are ignored.

This is quite dangerous, as one would expect all checks are in place and all validations are performed, impacting directly catching errors during regression testing.

## How to reproduce

To run the tests simply follow these steps:

1. Clone repository

```bash
$ git clone git@github.com:julianmrodri/multi-emit-example.git
```

2. Move to project folder and install dependencies

```bash
$ yarn install
```

3. Run tests

```bash
$ yarn test
```


