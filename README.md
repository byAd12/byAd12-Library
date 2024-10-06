
# byAd12-library - v1.0

**byAd12-library** is a Python library designed to facilitate the sending of massive ICMP (ping) messages to a specific target, as well as to provide information about the library itself.

## Project

- **PyPi**: [https://pypi.org/project/byAd12-library/](https://pypi.org/project/byAd12-library/)
- **Installation**: 
  ```bash
  pip install byAd12-library
  ```

## Author

- **Website**: [https://byAd12.pages.dev](https://byAd12.pages.dev)
- **Email**: [adgimenezp@gmail.com](mailto:adgimenezp@gmail.com)

## Functions

### `Ping_Flood_(IPv4)`
Sends massive pings (ICMP messages) to a target (local or server) using IPv4.

### `byAd12_Info_()`
Provides information about the library.

## Required dependencies

- **threading**: 
  ```bash
  pip install threading
  ```

- **ping3**: 
  ```bash
  pip install ping3
  ```

## Example

```python
from byAd12_library import Ping_Flood_, byAd12_Info_

# Send massive pings
Ping_Flood_("192.168.1.1")

# Get information about the library
info = byAd12_Info_()
print(info)
```

## Contributions

Contributions are welcome. If you have suggestions or improvements, feel free to open an issue or a pull request in the repository.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.