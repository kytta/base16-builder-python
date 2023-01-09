# base16-builder-python

A Python implementation of a [Base16] Builder that follows
[the latest spec][base16-builder-spec]

## Usage

```sh
cat scheme.yaml | python3 -m base16_builder --template template.mustache > scheme.file
```

# Licence

© 2023 [Nikita Karamov]\
Licensed under the [ISC License].

---

This project is hosted on Codeberg:
<https://codeberg.org/kytta/base16-builder-python.git>

[base16]: https://github.com/chriskempson/base16
[base16-builder-spec]: https://github.com/chriskempson/base16/blob/main/builder.md
[isc license]: https://spdx.org/licenses/ISC.html
[nikita karamov]: https://www.kytta.dev/
