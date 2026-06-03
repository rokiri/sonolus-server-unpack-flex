# sonolus-server-unpack-flex

fork of ['sonolus-unpacker'](https://github.com/carbeni/sonolus-server-unpack)

Unpack resources from Sonolus servers. Unpacked folder structure intended to be
compatible with [`sonolus-pack`](https://github.com/Sonolus/sonolus-pack).

## Setup

Install dependencies from repository root:
```
pip install -r requirements.txt
```

Add repository folder to `PATH` in order to access script in other directories.

## Example Usage

```
# Unpack Bandori engine
ssu.py -s <SERVER URL> engine bandori
    or
python ssu.py -s <SEVER URL> engine bandori

# Unpack level
ssu.py -s <SERVER URL> level 12203
    or
python ssu.py -s <SERVER URL> level 12345
```