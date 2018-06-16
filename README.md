```
┌┬┐┬ ┬┌─┐┌─┐┌┬┐┌─┐┬ ┬┌─┐┌─┐┌─┐┬─┐
 │ ├─┤├┤ ├┤  │ ├┤ │ │┌─┘┌─┘├┤ ├┬┘
 ┴ ┴ ┴└─┘└   ┴ └  └─┘└─┘└─┘└─┘┴└─
```
## Introduction:
TheftFuzzer is a tool that fuzzes Cross-Origin Resource Sharing implementations for common misconfigurations.

## Usage:
`python theftfuzzer.py -h`


```
~$ python theftfuzzer.py -h                                ✔  1882  14:17:40
usage: theftfuzzer.py [-h] -d DOMAIN [-c COOKIE]

Cross Origin Resource Sharing Fuzzer by Corben Leo

optional arguments:
  -h, --help            show this help message and exit
  -d DOMAIN, --domain DOMAIN
                        URL / Target to fuzz
  -c COOKIE, --cookie COOKIE
                        File containing cookie to send in fuzzing requests
```
