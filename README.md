# mkpassword

mkpassword - simple password generator

## Installation

    $ gem install mkpassword
    (you may need to run as root or through sudo.)

## Usage

```
mkpassword [options]
    -l length                           (default:12)
    -s number of special characters     (default:0)
    -c count                            (default:1)


$ mkpassword 
sBda9KLtmW2V

$ mkpassword -l 15
HoRwLab9CDbdq8S

$ mkpassword -l 15 -s 2
H{enlJVxuqeR#3j

$ mkpassword -l 15 -s 2 -c 5
0r]VWku;LL7ieqU
bY$DMXm5Zp!jXIF
hZfM3M98M+@kZIC
xlgHo|&loKCFGXN
UsJgZSR1^K0W;kM

```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/s3fxn/mkpassword.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
