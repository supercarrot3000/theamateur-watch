# The Amateur: website watch

This repository checks the public website [theamateur.co.uk](https://theamateur.co.uk/) from outside its server, every hour:

- the home page and the AI Journalism page answer;
- the TLS certificate has at least 14 days left.

It reads only public pages and holds no secrets. A failed run emails the owner.

To prove the alert works, run the workflow by hand with **test_failure** ticked.
