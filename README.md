# php-csp-ruler
Developed by Joe Fox

This script allows monitoring of the content security header length, as some firewalls block HTTP responses where there are headers that exceed a certain length (from personal experience, I've seen 4096 used as the length that starts getting requests blocked).

## 1) Usage guide
1) Copy the `tests/tests.php.template` to `tests/tests.php`.
2) Run `./csp-ruler.

## 2) Planned improvements
1) Send the output to a file at a specified path.
2) Add support for a config array (similar structure to the tests file).
3) Do something with the metrics (different levels of verbosity).
4) Add an option to check the length of all (or specified headers, potentially splitting these up for common and individual).
5) Move to a more OO structure which will allow it to be re-used.
6) Unit tests.
