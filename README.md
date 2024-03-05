## Tailwind Subset

This repository contains a subset of [Tailwind](https://tailwindcss.com/).

[dist/subset.css](dist/subset.css) is embedded in the [inox binary](https://github.com/inoxlang/inox/blob/main/internal/tailwind/subset.go).

During the development of an Inox project the project server detects Tailwind class names and includes the corresponding rules in `/static/gen/tailwind.css`.

> This repository has been created by making changes to https://github.com/0x1eef/tail.css.

## License

Copyright of src/ belongs to the
[tailwind project](https://tailwindcss.com/).
<br>
[LICENSE](https://github.com/tailwindlabs/tailwindcss/blob/master/LICENSE)
