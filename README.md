# Mplog-Parser compiled

PyInstaller compiled version of the `Mplog-Parser` Python script from
[Intrinsec's `Mplog-Parser` project](https://github.com/Intrinsec/mplog_parser).

The provided binary has been built using:

```bash
# Tested for Python 3.12.1 and PyInstaller 6.3.0.

git clone https://github.com/Intrinsec/mplog_parser.git

python3 -m pip install pyinstaller

python.exe -m PyInstaller --clean -n mplog_parser -F mplog_parser/mplog_parser/main.py
```
