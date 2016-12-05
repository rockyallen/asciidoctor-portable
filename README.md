# asciidoctor-portable
Portable version of asciidoctor, -pdf and -epub

The goal of this project is to assemble the main asciidoctor applications into a fully portable distribution you can unpack anywhere (even to a memory stick or CD) and be able to run them immediately.

Specifically:

* Include asciidoctor, asciidoctor-pdf, asciidoctor-epub and asciidoctor-fopub

* Cross platform (Linux/Windows)

* No prerequisites on the target computer

* No internet access required

* User privelleges only

* No installation required other than unzipping

* Simple instructions for upgrading components

Caveats:

* JDK 1.7+ may be required on the target PC (TBC)

## Installation

1. Download as zip.

2. Unpack anywhere.

3. (Optional) Add installation directory to you path for easier running.

## Running

The installtion folder contains batch and shell scripts for the 4 applications included.
They run exactly as the command lines for each application.

## Upgrading

1. Download the up-issued gem

2. Open a command window to <install-dir>/jruby

3. type `gem install --force --local <gemfile>.gem`.

## Status

Just this file so far....

