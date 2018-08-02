# George's typescript notes

## Requirements

I run on MacBook Pros with these installed:

```
node v10.1.0
docker 18 or greater
```


## Install

Paste this in your console.

```
git clone https://github.com/geocolumbus/typescript-notes.git \
&& cd typescript-notes \
&& npm install
```

## Development Environment

### Run

```bash
npm run dev
```

### Running tests

```bash
npm test
```

### Linting

```bash
npm run lint
```

## Production

### Building a docker container

```bash
docker build .
```
