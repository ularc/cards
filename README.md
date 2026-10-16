# Building the documentation

1. Install `sphinx` (suggestion: Use a virtual environment)

    ```bash
    python -m venv cards-docs-env
    source cards-docs-env/bin/activate
    pip install sphinx sphinx-rtd-theme sphinx-tabs
    ```

2. Build the documentation. This will create the folder `_build` inside
   the project's root folder.

    ```bash
    cd cards
    # Note you can use other options besides "html" here (e.g. "latex").
    # Simply run "make" to see all available options.
    make html
    ```

3. Access the `index.html` file inside `cards/_build/html`
