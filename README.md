Crappy test coverage tool. It just works. It also can generate some shitty report.

## Installation

    npm install semicov

## Usage

Put following line before very first line of your code

    require('semicov').init('lib'); // 'lib' is name of dir with code

Optionally put this code somewhere

    process.on('exit', function () {
        require('semicov').report();
    });

And it will generate shitty report for you.

