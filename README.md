# DominoSimulator

DominoSimulator is command line apkication gem.
If you enter the picture, it outputs the breadth, the number of Domino needed to domino the picture. In addition, This will also output rendering of the Domino.

Domino is assumed that you use what you are lending in Japan Domino Association. 
The color of Domino is 9 colors of black, white, red, blue, yellow, green, orange, pink, and purple. 
Please refer to the website of Domino Association for more information.
http://www.domino.or.jp/

## Installation

    sudo apt-get install imagemagick

    sudo apt-get install libmagickwand-dev

    sudo apt-get install libjpeg-dev

Add this line to your application's Gemfile:

    gem 'domino_simulator'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install domino_simulator

## Usage

Specify the path to the image file to the first argument, please run the /lib/domino_simulator.rb.
Result is output, rendering will be output to the current directory.

    $ ./lib/domino_simulator.rb IMAGEFILE

## Contributing

1. Fork it ( https://github.com/kairiTakemura/domino_simulator/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
