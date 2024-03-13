# Getting started

## Installation

### For a project

It is recommended to install Textstat in a virtual environment for the project
you're working on. 

=== "poetry"

    ```
    poetry add textstat
    ```

=== "pipenv"

    ```
    pipenv install textstat
    ```

=== "pip"

    ```
    pip install textstat
    ```


### Standalone

If you just want to use Textstat as a command line tool, you can install
it standalone in it's own dedicated virtual environment using [`pipx`][pipx].

```
pipx install textstat
```

<small>Install [`pipx`](https://pipx.pypa.io/stable/installation/) if you haven't already.</small>


### With git

Alternatively, you can install directly from source if you would prefer. This will
install the latest from [`main`](https://github.com/textstat/textstat/tree/main).

=== "poetry"

    ```
    poetry add git+https://github.com/textstat/textstat.git
    ```

=== "pipenv"

    ```
    pipenv install git+https://github.com/textstat/textstat.git
    ```

=== "pip"

    ```
    pip install git+https://github.com/textstat/textstat.git
    ```

=== "pipx"

    ```
    pipx install git+https://github.com/textstat/textstat.git
    ```

If you require a specific version or branch, you can specify the tag to use.

=== "main"

    ```
    poetry add git+https://github.com/textstat/textstat.git@main
    ```

=== "dev"

    ```
    poetry add git+https://github.com/textstat/textstat.git@dev
    ```

=== "version"

    ```
    poetry add git+https://github.com/textstat/textstat.git@0.7.3
    ```



[pipx]: https://pipx.pypa.io/stable/ "Pipx"