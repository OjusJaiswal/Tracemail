# Tracemail - A small e-mail header analyzer

**Description**

Tracemail is a small, Python 3.X.X script to print information about
an e-mail. Tracemail analyzes the headers of an e-mail and prints
information, such as the route the e-mail took, time per hop, etc.
This script was created to provide a simple program for analyzing e-mail
headers with as few dependencies as possible. This program takes one or more
e-mails in plain text format as input. Simply copy the source of an email,
including the headers, and paste it into a plain text file to use as input
for the program.

Note that this script requires a Python module named python-dateutil. It may
be a good idea to create a virtual environment using Venv to manage
dependencies without polluting the system packages