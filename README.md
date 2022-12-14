# Web Scrapping

This app requires to have installed Python

## Check in terminal python installation

### Windows:

```bash
❯ python
```

### Mac:

```bash
❯ python3
```

## Chrome driver installation

Download the corresponding [chrome driver](https://chromedriver.chromium.org/downloads) according Chrome version(chrome://version/).

### Windows:

Put the .exe file in the direcory _C:/Windows/_

### Mac or Linux:

Put the .exe file in the directory _/usr/local/bin/_

## App installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install pipenv.

```bash
❯ pip install pipenv
```

Download source code in a folder, open a terminal and run:

```bash
❯ pipenv install --ignore-pipfile
```

To activate the Virtual Environment:

```bash
❯ pipenv shell
```

## Usage

```bash
❯ python app.py URL1
```

```bash
❯ python app.py URL1 URL2 URL3 ...
```

## Examples

The next lines will have the same effect

```bash
❯ python app.py tunja-boyaca.gov.co
❯ python app.py www.tunja-boyaca.gov.co
❯ python app.py http://www.tunja-boyaca.gov.co
```

Passing multiple URLs:

```bash
❯ python app.py https://www.tunja-boyaca.gov.co www.castillalanueva-meta.gov.co
```
