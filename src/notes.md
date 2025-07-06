replacing `dbus` with `pydbus`
also needs `sudo apt install python3-gi`

```shell
sudo apt install libcairo2-dev libxt-dev libgirepository1.0-dev #nope.

pip install pycairo PyGObject``` #nope.

python-gi-dev # nope.

Opted to simply comment them out and pray.

wiringpi will 100% need work, it's barely supported & working as-is.