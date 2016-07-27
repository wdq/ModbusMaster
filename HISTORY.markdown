## [v1.2.0 (2016-07-10)](/4-20ma/ModbusMaster/tree/v1.2.0)
- Done Extensive testing on Particle Photon. Bumped up version for reimport

---
## [v1.1.0 (2016-07-10)](/4-20ma/ModbusMaster/tree/v1.1.0)
- Port to Particle Photon by Anurag Chugh (https://github.com/lithiumhead)
- Replaced spaces with tabs for indentation
- If the initial bytes received in response to a transmitted frame are "zeros", keep discarding untl a non-zero byte is received
- Assign an use a TX_Enable pin to switch RS485 driver from receiving to transmitting.
- If debug is enabled, print TX and RX frames on Serial. Beware, enabling this messes up the timings for RS485 Transactions, causing them to fail.
- Empty the receive before beginning Modbus transaction by repeatedly calling read() until available() returns 0.

---
## [v0.9.1 (2013-01-02)](/4-20ma/ModbusMaster/tree/v0.9.1)
- Add Rakefile to manage prepare/release process
- Add .gitignore to skip doc/html, doc/latex files
- Add Doxyfile to repo
- Update copyright year
- Update email address
- Fix references to repo
- Move history to separate file
- Update README copyright, email

---
## [v0.9 (2011-12-04)](/4-20ma/ModbusMaster/tree/v0.9)
- Add support for Arduino 1.0

---
## [v0.8 (2011-11-09)](/4-20ma/ModbusMaster/tree/v0.8)
- Add support for ATmega2560

---
## [v0.7 (2010-02-09)](/4-20ma/ModbusMaster/tree/v0.7)
- Modified capitalization of functions to match Arduino style where first letter is lower-case

---
## [v0.6 (2010-02-04)](/4-20ma/ModbusMaster/tree/v0.6)
- Added documentation via Doxygen comments, modified methods used to get/set storage buffers

---
## [v0.5 (2010-01-30)](/4-20ma/ModbusMaster/tree/v0.5)
- Added ability to select serial port 0..3, modified methods used to get/set storage arrays, miscellaneous bug fixes

---
## [v0.3 (2010-01-29)](/4-20ma/ModbusMaster/tree/v0.3)

---
## [v0.2 (2010-01-25)](/4-20ma/ModbusMaster/tree/v0.2)

---
## [v0.1 (2010-01-24)](/4-20ma/ModbusMaster/tree/v0.1)
- Initial public release
