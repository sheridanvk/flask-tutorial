### How to run this app

1. Clone the repo
2. Make sure you have `python3` installed (details at the [official website](http://python.org/download/))
3. Run the following (everything up to and including the % just indicates that you're running these commands in a terminal and should be ignored):

```bash
# Install and activate the virtual environment
% python3 -m venv venv
% virtualenv venv
% source venv/bin/activate

# Install the dependencies
(venv) % pip3 install -r requirements.txt

# Run the database migrations
(venv) % flask db upgrade
(venv) % flask run
```
