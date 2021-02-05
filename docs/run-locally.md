# Run local

In Laravel 8, there is new package available called [https://laravel.com/docs/8.x/sail](https://github.com/dimovdaniel/qrmakerdocs/tree/69ae22bf536fbcb9ae642111076f83b0fac8c0e7/common/Laravel%20Sail/README.md).

We use this to run the site locally, and test it.

All you need is to install [https://www.docker.com/](https://github.com/dimovdaniel/qrmakerdocs/tree/69ae22bf536fbcb9ae642111076f83b0fac8c0e7/common/Docker/README.md) in your compute.

After that, open the code and execute the command

```text
./vendor/bin/sail up
```

You can add alias for the sail command.

Then open the site on localhost, and the install window should appear.

In .env instead of

```text
DB_HOST=127.0.0.1
```

use

```text
DB_HOST=mysql
```

