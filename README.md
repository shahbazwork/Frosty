![Showcase of the Frosty app with screenshots in a masonry grid](https://github.com/tommyxchow/frosty/assets/54859075/09178dcc-2fd2-4618-8076-502719159424)

## Download

  <a href="https://play.google.com/store/apps/details?id=com.tommychow.frosty">
    <img
      title="Get it on Android (Google Play Store)"
      alt="Google Play Store badge."
      src="https://user-images.githubusercontent.com/54859075/160051854-21a57556-6b5a-41e9-8127-334daf1fac47.svg"
      width="225px"
    />
  </a>
</p>

## Why

The official Twitch mobile app doesn't support emotes from [7TV](https://chrome.google.com/webstore/detail/7tv/ammjkodgmmoknidbanneddgankgfejfh), [BetterTTV (BTTV)](https://chrome.google.com/webstore/detail/betterttv/ajopnjidmegmdimjlfnijceegpefgped), and [FrankerFaceZ (FFZ)](https://chrome.google.com/webstore/detail/frankerfacez/fadndhdgpmmaapbmfcknlfgcflmmmieb) — third-party extensions for Twitch used by millions. As a result, only emote text names are rendered rather than their actual image or GIF, making the chat unreadable in many channels.

## Features

- Support for 7TV, BetterTTV, and FrankerFaceZ emotes and badges
- Browse followed streams, top streams, and top categories
- Autocomplete for emotes and user mentions
- Light, dark, and black (OLED) themes
- Search for channels and categories
- See and filter chatters in a channel
- Local chat user message history
- Theater and fullscreen mode
- Watch live streams with chat
- Picture-in-picture mode
- Block and report users
- Emote menu
- Sleep timer
- And more...

For a more detailed overview, visit [frostyapp.io](https://www.frostyapp.io/).

## Development setup

1. [Install Flutter](https://docs.flutter.dev/get-started/install).

2. Clone this repo (e.g., `git clone https://github.com/tommyxchow/frosty.git`).

3. Go to the [Twitch dev console](https://dev.twitch.tv/login) and register a new application to retrieve a **Client ID** and **Client Secret**.

4. Use [`--dart-define`](https://dartcode.org/docs/using-dart-define-in-flutter/) to set the `clientId` and `secret` environment variables with your **Client ID** and **Client Secret**.

5. Run `flutter pub get` to fetch all the dependencies.

6. Choose an emulator or device and run the app!

> [!IMPORTANT]
> Frosty uses [MobX](https://mobx.netlify.app/) for state management. Please refer to the documentation about code generation, otherwise your changes within MobX stores may not be applied.


Otherwise, downloading Frosty, leaving a review, or starring this repository is more than enough to show support. Thank you!

## License

Frosty is licensed under [AGPL-3.0-or-later](LICENSE).
