# signal-cli compiled for Raspberry Pi
See https://github.com/AsamK/signal-cli for the source and original author

So far, I've only tested/used the 'register' (with --captcha), 'verify' and 'send -m' commands.
All ran with no errors.

**rpi_signal-cli.0.8.1.tar**  -> Signal-cli v0.8.1
Build with:
- Raspberry PI 3B with Raspbian GNU/Linux 10 (buster)
- Java JDK c11.0.9.1
- Gradle v6.7.1
- Rust  1.41.1+dfsg1-1~deb10u1+rpi1
- protobuf-compiler 3.6.1.3-2+rpi1

These 2 libraries are already included in above mentioned tar file (stored here for possible future use):
- **zkgroup-java-0.7.1.jar** the dependent library build for Raspberry Pi, source is https://github.com/signalapp/zkgroup/releases release/tag: v0.7.1
- **signal-client-java-0.2.3.jar** the dependent library build for Raspberry Pi, source is https://github.com/AsamK/signal-cli/wiki/Provide-native-lib-for-libsignal release/tag: java-0.2.3

**Manual_build.pdf** -> the manual build steps used to build the tar file.

### Older version(s):
- rpi_signal-cli.0.7.4.tar -> Signal-cli v0.7.4 build on Raspberry PI 3B with Raspbian GNU/Linux 10 (buster)
- rpi_signal-cli.0.7.1.tar -> Signal-cli v0.7.1 build on Raspberry PI 3B with Raspbian GNU/Linux 10 (buster)

### ==== No warranty, implied or otherwise. Provided 'as is'. Use at your own risk. ====
