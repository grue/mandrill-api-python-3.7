## Fork for python 3.7 support

`pip install mandrill-37`

# Mandril

Mandrill is a Python API client and suite of CLI-based tools for the Mandrill email as a platform service.

The API client is comprehensive, but the CLI functionality is minimal at this time.

Examples:
import mandrill
m = mandrill.Mandrill('YOUR_API_KEY')
print m.users.ping()
--> "PONG!"

CLI Examples:
mandrill setup
mandrill ping -c10
mandrill send -f from@example.com -t to@example.com -s "My Subject Line" < content.html
