# NAME

App::CSV2Chart - generate charts on the command line.

# Screenshots

![Image](./screenshots/csv2chart-2019-05-28.webp)

# VERSION

version 0.4.0

# SYNOPSIS

    ( echo "time,value" ; echo -n $'1,24\n2,36\n3,1977') | \
        csv2chart xlsx --output spreadsheet.xlsx \
            --exec gnumeric \
            --title "Values vs. Times"

# NAME

csv2chart - command line utility to convert CSV data to a graphical chart

# COPYRIGHT & LICENSE

Copyright 2019 by Shlomi Fish

This program is distributed under the MIT / Expat License:
http://www.opensource.org/licenses/mit-license.php

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

# SUPPORT

## Websites

The following websites have more information about this module, and may be of help to you. As always,
in addition to those websites please use your favorite search engine to discover more resources.

- MetaCPAN

    A modern, open-source CPAN search engine, useful to view POD in HTML format.

    [https://metacpan.org/release/App-CSV2Chart](https://metacpan.org/release/App-CSV2Chart)

- Search CPAN

    The default CPAN search engine, useful to view POD in HTML format.

    [http://search.cpan.org/dist/App-CSV2Chart](http://search.cpan.org/dist/App-CSV2Chart)

- RT: CPAN's Bug Tracker

    The RT ( Request Tracker ) website is the default bug/issue tracking system for CPAN.

    [https://rt.cpan.org/Public/Dist/Display.html?Name=App-CSV2Chart](https://rt.cpan.org/Public/Dist/Display.html?Name=App-CSV2Chart)

- AnnoCPAN

    The AnnoCPAN is a website that allows community annotations of Perl module documentation.

    [http://annocpan.org/dist/App-CSV2Chart](http://annocpan.org/dist/App-CSV2Chart)

- CPAN Ratings

    The CPAN Ratings is a website that allows community ratings and reviews of Perl modules.

    [http://cpanratings.perl.org/d/App-CSV2Chart](http://cpanratings.perl.org/d/App-CSV2Chart)

- CPANTS

    The CPANTS is a website that analyzes the Kwalitee ( code metrics ) of a distribution.

    [http://cpants.cpanauthors.org/dist/App-CSV2Chart](http://cpants.cpanauthors.org/dist/App-CSV2Chart)

- CPAN Testers

    The CPAN Testers is a network of smoke testers who run automated tests on uploaded CPAN distributions.

    [http://www.cpantesters.org/distro/A/App-CSV2Chart](http://www.cpantesters.org/distro/A/App-CSV2Chart)

- CPAN Testers Matrix

    The CPAN Testers Matrix is a website that provides a visual overview of the test results for a distribution on various Perls/platforms.

    [http://matrix.cpantesters.org/?dist=App-CSV2Chart](http://matrix.cpantesters.org/?dist=App-CSV2Chart)

- CPAN Testers Dependencies

    The CPAN Testers Dependencies is a website that shows a chart of the test results of all dependencies for a distribution.

    [http://deps.cpantesters.org/?module=App::CSV2Chart](http://deps.cpantesters.org/?module=App::CSV2Chart)

## Bugs / Feature Requests

Please report any bugs or feature requests by email to `bug-app-csv2chart at rt.cpan.org`, or through
the web interface at [https://rt.cpan.org/Public/Bug/Report.html?Queue=App-CSV2Chart](https://rt.cpan.org/Public/Bug/Report.html?Queue=App-CSV2Chart). You will be automatically notified of any
progress on the request by the system.

## Source Code

The code is open to the world, and available for you to hack on. Please feel free to browse it and play
with it, or whatever. If you want to contribute patches, please send me a diff or prod me to pull
from your repository :)

[https://github.com/shlomif/CSV2Chart](https://github.com/shlomif/CSV2Chart)

    git clone https://github.com/shlomif/CSV2Chart.git

# AUTHOR

Shlomi Fish <shlomif@cpan.org>

# BUGS

Please report any bugs or feature requests on the bugtracker website
[https://github.com/shlomif/app-csv2chart/issues](https://github.com/shlomif/app-csv2chart/issues)

When submitting a bug or request, please include a test-file or a
patch to an existing test-file that illustrates the bug or desired
feature.

# COPYRIGHT AND LICENSE

This software is Copyright (c) 2019 by Shlomi Fish.

This is free software, licensed under:

    The MIT (X11) License
