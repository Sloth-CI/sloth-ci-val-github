# sloth-ci.validators.github

Sloth CI validator for [GitHub](https://github.com/) push events.


## Installation
    
    $ pip install sloth-ci.validators.github


## Usage

    provider:
        github:
            # Repository owner. Mandatory parameter.
            owner: moigagoo

            # Repository title as it appears in the URL, i.e. slug.
            # Mandatory parameter.
            repo: sloth-ci

            # Only pushes to these branches will initiate a build.
            # Skip this parameter to allow all branches to fire builds.
            branches:
                - master
                - staging
