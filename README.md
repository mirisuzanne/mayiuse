# mayiuse
like [caniuse](http://caniuse.com/),
but for permission instead of data.
No more complex charts,
we'll give you a straight-forward answer.
If your boss complains,
you can tell her we
said it was ok.


Development
-----------

If you want to run this project in a `virtualenv`_
to isolate it from other Python projects on your system,
create a virtualenv and activate it.
Then run ``pip install -r requirements.txt``
to install the dependencies for this project
into your Python environment.

.. _virtualenv: http://www.virtualenv.org

Run ``yarn`` to install
all the required npm packages
for linting and compiling Sass.

The site templates are in ``templates/``,
and static files are in ``static/``.

To view the site live locally,
run ``make serve`` to watch rst content files,
or ``gulp`` to watch and compile Sass files as well —
then visit ``http://localhost:5000`` in your browser.

To regenerate the site as static HTML files
under the ``docs/`` directory,
run ``make build``.
