### Changelog

**0.3.0-justpark.1** (JustPark fork — https://github.com/storyblok/storyblok-swift/pull/10)

- Fixed a 2–3s delay on every `StoryblokClient.story()` fetch on iOS: the cache probe it issues first was counted as a failed request by the rate limiter when it missed, backing off the real fetch.

**0.3.0**

- Renamed `Blok` to `Block` throughout the Rich Text View for consistency. Deprecated `Blok` typealiases and delegate methods are provided for backward compatibility.
- Removed a redundant `Story` initializer.

**0.2.0**

- Initial release of the Storyblok Client
- Initial release of the Rich Text View
- Added JetNews sample app

**0.1.0**

- Initial release of the URLSession Extension
