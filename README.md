# AK-603

[![CI](https://github.com/Sam-DarkBall-Mods/AK-603/actions/workflows/ci.yml/badge.svg)](https://github.com/Sam-DarkBall-Mods/AK-603/actions/workflows/ci.yml)

This mod adds BLUFOR and OPFOR versions of the AK-603 naval gun system. It uses
a twin AO-18KD weapon with a 2,000 round magazine. The operator display shows
the date and time, turret angles, range and remaining ammunition.

## Requirements

- Arma 3 2.22 or newer
- CBA_A3

## Building

```bash
python3 -B -m unittest discover -s tests -p "test_*.py" -v
hemtt check
hemtt build --no-bin
```

The game classes and the `ak603` PBO prefix are kept for compatibility with
existing missions.

## License

Code and configs use GPL-2.0-or-later. The model, textures, materials and audio
use APL-SA. See [LICENSES.md](LICENSES.md).
