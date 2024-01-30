# FlaskIntroduction

This repo has been updated to work with `Python v3.8` and up.

## How To Run

1. Setup virtual env:

```
$ python3 -m venv .venv
```

2. Then run the command:

```
$ .venv\bin\activate
```

2. Then run the command (Mac):

```
$ source .venv\bin\activate
```

3. Then install the dependencies:

```
$ pip install -r requirements.txt
```

4. Finally start the web server:

```
$ python3 app.py
```

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```

## Contributing

Since this is a repository for a tutorial, the code should remain the same as the code that was shown in the tutorial. Any pull requests that don't address security flaws or fixes for language updates will be automatically closed. Style changes, adding libraries, etc are not valid changes for submitting a pull request.
