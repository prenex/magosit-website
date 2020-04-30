MagosIT website
===============

One variation of a simple MagosIT Kft static website for the company with fast loading times and easy-to-change markup based content.

Uses prosopopee
---------------

https://pypi.org/project/prosopopee/

Usage:

		prosopopee
		prosopopee preview
		prosopopee deploy
		prosopopee test
		prosopopee (-h | --help)
		prosopopee.py --version

Before of course we need to actiate venv (after installation):

		. .venv/bin/activate

See:

https://github.com/Psycojoker/prosopopee

Install using venv
------------------

		python3 -m venv <DIR>
		source <DIR>/bin/activate

		python -m ensurepip --default-pip
		pip install prosopopee # does not work for me, but adds dependencies

		git clone <url-of-prosopopee>
		cd <path-to-prosopopee>
		#Based on http://cerfacs.fr/coop/python3_doc/pip_install/
		pip install . # this installs it well
		# might add dependency by installing the dependencies txt file too!

This is needed for locally installing the stuff. Maybe that way one can install manually too using the setup.py (see manuals online)
