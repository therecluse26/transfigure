# Transfigure Ideas

### Upgrade tool for various languages

Core concept: A tool to allow users to input two version numbers of a particular language (or use a manifest file for additional configurability) and check for deprecations within their current code base, to assist in upgrades

Will encourage developers to keep their code bases up to date with current language versions, eliminating vulnerabilities and encouraging good general practices

- Store many versions of a particular programming language standard libraries in database for API access
    - Allow additional common packages
    - Allow upload of package API syntax from community
        - Follow a peer-review process, requiring a certain level of upvotes or review from a trusted moderator before pushing
    - Delivery schemes
        - Host a public API (or paid)
        - Allow users to download entire database of a given language locally using cli

- Deprecation checker between versions
    - Checks entire code base against API
    - Check for replacement syntax
    - Pull new (or at least notify user of) required dependencies for replacements

- Automatic upgrade option
    - Requires version control to be up to date with current state of source code
    - Automatically refactors entire code base (if necessary and possible) to conform with new version specs

