# drupal-ops
Assistant for coding standards tools.

To view the available coding standards:

```bash
vendor/bin/phpcs -i
```

RUN:
``` composer phpcs ```
It'll give output:
> Exit code 0 = no errors found.

> Exit code 1 = warnings found.

> Exit code 2 = errors found.

To fix, RUN: ```composer phpcbf```
