Simple demo script to read/update user call intercept settings
---------

    | usage: call_intercept.py [-h] [--token TOKEN] [-d] user_email [{on,off}]
    | 
    | positional arguments:
    |   user_email     email address of user
    |   {on,off}       operation to apply
    | 
    | options:
    |   -h, --help     show this help message and exit
    |   --token TOKEN  admin access token to use
    |   -d, --debug    show detailed REST trace

The script uses the access token passed via the CLI, reads one from the WEBEX_ACCESS_TOKEN environment variable or
obtains tokens via an OAuth flow. For the last option the integration parameters are read from environment variables which can be set in a ``.env`` file


