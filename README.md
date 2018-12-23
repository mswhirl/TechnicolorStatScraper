# Technicolor VDSL Modem Stat Scraper

Install dependencies with:
pip install -U -r requirements.txt

Please edit the top of settings.py for the IP/Username/Password as required.

On Windows the result will be saved to a file and opened in your default text editor.
On other OSes it will be printed to stdout.

Example output:
{'us': '20.94', 'ds': '61.08', 'uploaded': '866.77', 'downloaded': '2167.99'}

If authentication fails, a full exception trace and debug output for the SRP6 authentication will be displayed.
