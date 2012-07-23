# redis-stat

A command-line Redis monitoring tool written in Ruby.

## Installation

```
gem install redis-stat
```

## Usage

```
usage: redis-stat [HOST[:PORT]] [INTERVAL [COUNT]]

        --csv=OUTPUT_CSV_FILE_PATH   Save the result in CSV format
    -v, --verbose                    Show more info
        --version                    Show version
        --help                       Show this message
```

## Examples

```
redis-stat

redis-stat 1

redis-stat localhost:6380

redis-stat localhost:6380 1 10

redis-stat localhost:6380 1 10 --csv=/tmp/output.csv --verbose
```

## Screenshot

![](https://github.com/junegunn/redis-stat/raw/master/screenshots/redis-stat-0.1.0.png)


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request