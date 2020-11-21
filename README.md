# Raspberry Pi Compute Module 4 (CM4) Base Carrier

![Rendered example of RPi CM4 Carrier Template PCB](https://raw.githubusercontent.com/ShawnHymel/rpi-cm4-base-carrier/main/images/rpi-cm4-base-carrier-rendered.jpg)

Simple carrier board for the Raspberry Pi Compute Module 4. It provides power to the module through the USB-C connector (power only, no data), USB client mode (host mode is not supported), Qwiic/Stemma connector for I2C lines, SPI, UART, and power/activity LEDs.

Feel free to modify this design for your own application. This PCB is not intended to be an end product but rather a demo to get people started making their own carrier boards for the CM4.

Note that USB traces were calculated for a 2-layer board with a 1.6mm height.

## License

Schematic and PCB layout files are licensed under the [CC BY 4.0](https://creativecommons.org/licenses/by/2.0/) license.

Individual components and footprints found in the CM4IO library are licensed as per the Design Files license found [here](https://datasheets.raspberrypi.org/license.html).

THE DESIGN IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS DESIGN INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS DESIGN.
