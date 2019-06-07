# ibeacon_bluepy
This code is able to collect info about every device which is broadcasting bluetooth packets.

Requirements:
To make the scan we need to install the bluepy lib.
  Can be found at https://github.com/IanHarvey/bluepy with all own requirements
In case you use requests, the library used is requests-futures.
  To install type:
  <code>
  $ pip install requests-futures
  </code>


Usage:
To use this code, you will need to know the MAC of each beacon you're using.
1º Change the "beacons" variable adding your own beacons MAC address(STRINGS).

And thats it, it will be able to detected when you're close or not to a registered beacon.

Under MIT license.
