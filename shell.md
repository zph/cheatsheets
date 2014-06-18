# Shell (Bash/Zsh)

## Basics:

- Use readonly and local to set variables.
  `readonly var="foo"`
- Use `"${variable}/bar"` style expansion
- `$(echo whois)` not backticks

## Safety measures to add at beginning of bash script

```
set -o nounset
set -o pipefail
set -o errexit
set -o xtrace
```

## Credit/Further Resources:

- http://www.kfirlavi.com/blog/2012/11/14/defensive-bash-programming/
- https://google-styleguide.googlecode.com/svn/trunk/shell.xml
