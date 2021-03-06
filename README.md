# CZ4042 Neural Network

This LaTex document is a summary of the course CZ4042 Neural Network, offered by School of Computer Science and Engineering, Nanyang Technological University, Singapore. 

To download this document in PDF format: [download now](https://github.com/Andyccs/neural-network-summary/releases/download/v1.0/CZ4042NeuralNetworkSummary.pdf)

## Development

If you would like to build this document from source, first you need to install TeX:

```Shell
# For ubuntu
$ sudo apt-get install texlive-full

# For Mac OX
$ brew cask install mactex
```

Once you have TeX installed, make sure that you can use `pdflatex` command in terminal. To build the document in PDF format:

```Shell
$ make
```

To automatically build the PDF while editing `.tex` file, you need to install watch-cli using `npm` first:

```Shell
$ npm install -g watch-cli
```

Then you start watching for changes:

```Shell
$ make watch
```
