# Android App Sender ID Modifier

Modify Sender ID for GCM.

This tool is suitable for [Android Empty App](https://github.com/kaosf/android-empty-app).

## Usage

```sh
./modify-android-sender-id 123456789012
```

The Sender ID string `<string name="sender_id"></string>` in `res/values/strings.xml` will be changed to `<string name="sender_id">123456789012</string>`.

## License

[MIT](http://opensource.org/licenses/MIT)
