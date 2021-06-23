# signal-cli compiled for Raspberry Pi
See https://github.com/AsamK/signal-cli for the source and original author.

So far, I've only tested/used the 'register' (with --captcha), 'verify' and 'send -m' commands.
All ran with no errors.

**rpi_signal-cli.0.8.3.tar**  -> Signal-cli v0.8.3
Build with:
- Raspberry PI 3B with Raspbian GNU/Linux 10 (buster) Lite
- Java JDK v11.0.11+9-post-Raspbian-1deb10u1
- Gradle v7.1
- Rust  1.53.0
- protobuf-compiler 3.6.1.3-2+rpi1
- Git 2.20.1
- zip 3.0-11
- unzip 6.0-23+deb10u2

These 2 libraries are already included in the above mentioned tar file (stored here for possible future use):
- **zkgroup-java-0.7.0.jar** the dependent library build for Raspberry Pi, updated source is https://github.com/signalapp/zkgroup/releases release/tag: v0.7.2
- **signal-client-java-0.2.3.jar** the dependent library build for Raspberry Pi, updated source is https://github.com/AsamK/signal-cli/wiki/Provide-native-lib-for-libsignal release/tag: java-0.2.3

**Manual_build_v0.8.3.pdf** -> the manual build steps, used to build the tar file.

### Older version(s):
- rpi_signal-cli.0.8.1.tar -> Signal-cli v0.8.1 build on Raspberry PI 3B with Raspbian GNU/Linux 10 (buster)
- rpi_signal-cli.0.7.4.tar -> Signal-cli v0.7.4 build on Raspberry PI 3B with Raspbian GNU/Linux 10 (buster)
- rpi_signal-cli.0.7.1.tar -> Signal-cli v0.7.1 build on Raspberry PI 3B with Raspbian GNU/Linux 10 (buster)


### LICENSE
### ==== No warranty, implied or otherwise. Provided 'as is'. Use at your own risk. ====
Licensed under the GPLv3: http://www.gnu.org/licenses/gpl-3.0.html<br>
See https://github.com/AsamK/signal-cli for the source and original author
