# net8short Prefixes

This repository contains a list of prefixes for common shorter URLs, so for example, `youtube.com/watch?v=yr_HIrfr7is` just becomes `n8s.uk/~y.yr_HIrfr7is`. This might not look like much of a saving, but when sharing links in places with character limits (like Twitter or Discord), every character counts!

And the best part: the URLs can be expanded offline and do not rely on any kind of database, so you can just self host your own shortener with just these prefixes.

Combined with a filter list to remove tracking parameters (we recommend [this one](https://github.com/ClearURLs/Rules/blob/master/data.min.json)), you can share clean, short URLs easily.

## Usage

You can just paste an URL to the [net8 shortener](https://short.net8.cloud/?preferprefix) and it will automatically shorten it for you as well as remove tracking parameters.

And if you just want to have a privacy-respecting URL shortener, you can just use the [net8 shortener](https://short.net8.cloud/) without any prefixes. We don't collect any data about you or the URLs you shorten like some other services do ;)

## Contributing

Feel free to open an issue or a pull request if you want to add more prefixes: <https://n8s.uk/~gh.net8cloud.short-prefixes.new>

All prefixes are stored in the `prefixes.json` file in this repository, and all entries should be kept in alphabetical order.

Please note that we only accept prefixes for well-known domains and services, so please make sure that the prefix you want to add is widely used.

Although we'll try not to remove or edit any prefixes, we reserve the right to do so if a prefix is found to be inappropriate, misleading or just doesn't work properly anymore. Prefixes to NSFW content are not allowed, althogh mixed platforms like Twitter, Reddit or Discord are fine, we just don't want to link to platforms that are primarily NSFW like "the hub". We might change this policy in the future, but for now, please keep it clean.

Also, no prefix should be longer than 4 characters. If multiple prefixes point to different parts of the same services, please don't make the full prefix longer than 5 characters (like the `u` (for user) suffix appended might make the prefix 5 characters long).

In addition, prefixes should be kept alphanumerical (a-z, 0-9) only, no special characters. Prefixes should be handeled case-insensitively, but we recommend to use only lowercase characters for consistency.

## License

This repository is licensed under the [MIT License](LICENSE).

Feel free to use the prefixes in your own projects, but please make sure to give proper credit to the original source.
