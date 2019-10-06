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

## Usage with docker

```
$ docker run ruby:2.6.5 /bin/bash -c "gem install mkpassword >/dev/null ; mkpassword -s 2 -l 15 -c 10"
0Ojuik'5p&pjnaS
yN9nHg_#PE571FG
60Idwa53\3EtXS'
-2&JiiZ43uDh5Js
?h88$wu8w2y86YE
gF@1wSHInnAeZ&p
9R%MjV6xF3ivil_
95x9rvhNze"1nY/
NAwEOoE*FQg$R7d
bHUHUzcnTc2{L^o
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/s3fxn/mkpassword.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
