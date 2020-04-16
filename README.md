# ARMEE Ventilator

## INTRO

This repository contains plans for a device which controls air (or gas) flow so that its output alternates between two pressure levels.  The pressures, flow rates and cycle times are similar to the typical output of a mechanical ventilator.  *It has no moving parts*, and could be produced very rapidly, at low cost and in very large numbers if needed.

The original design dates to the early 1960s:
* Hermann Ziermann. ["Fluid amplifier controlled respirator"](https://patents.google.com/patent/US3379194A/en). US Patent 3,379,194, 1968
* J.W. Joyce, Jr. ["TM 68-30 The Army Emergency Respirator"](./research/1968_Army_Emergency_Respirator.pdf). Harry Diamond Labs, US Army Materiel Command, 1968

We are working to modify it to make the output better match modern requirements.

This is an open source hardware project: all work is licensed under the CERN Open Hardware Licence v2 (strongly reciprocal).


## HOW TO CONTRIBUTE

Get the necessary [Equipment](./documentation/Equipment.md): a source of compressed air, pressure and flow gauges and a test lung.

Build one of the [Models](./models/), following the Build Instructions: the recommended method is to use a CNC mill to make this out of plastic, but feel free to experiment.

Run some tests following the [Test Instructions](./documentation/Test_Instructions.md).

Try to modify the design so as to address some of the [Open Issues](./documentation/Open_Issues.md).

Participate in the discussion on [Slack](http://millionvents.slack.com).


## MORE DOCUMENTATION

(Unofficial) Latest documentation: 
- https://docs.google.com/document/d/1ZnPGnA-GKtFLsJEDVVLLKqNAKSk3q6F47YqvtuoJVXw/


## DISCLAIMER

This is not a medical device, and is not intended to be used as part of a medical device. It is especially not intended to be used in critical life support equipment. It comes with ABSOLUTELY NO WARRANTY. If you build it and use it, you do so at your own risk. If you build devices incorporating this design and use them for any application, it is up to you to verify the performance is suitable for your application and complies with all applicable laws.

## COPYRIGHT AND LICENSE

Copyright 2020 
- Ryan Whitney M.ryan.whitney@gmail.com (PEEP Loop Models)
- Alex Izvorski aizvorski@gmail.com (Original Dimensions/Models)
- Chris Jung Chris@braeburnacoustics.com (CNC Machining Models)
- Arrtemio Mendoza artexmg@gmail.com (3D Printing Models)

This Source (CAD files and other design materials) describes Open Hardware and is licensed under the CERN-OHL-S v2.

You may redistribute and modify this Source and make products using it under the terms of the CERN-OHL-S v2 (https:/cern.ch/cern-ohl).

This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-S v2 for applicable conditions.

Source Location: https://github.com/MillionVentilators/ARMEE_Ventilator_1.0

As per CERN-OHL-S v2 section 4, should You produce hardware based on this Source, You must maintain the Source Location visible on the external case of the hardware or other product you make using this Source.

## DISCLAIMER OF WARRANTY, EXCLUSION AND LIMITATION OF LIABILITY

Additionally, the following important disclaimers from the CERN-OHL-S v2 license apply to all use (reproduced below for clarity). Do not download or use these files unless you have read and agree with the following.

6.1 DISCLAIMER OF WARRANTY -- The Covered Source and any Products are provided 'as is' and any express or implied warranties, including, but not limited to, implied warranties of merchantability, of satisfactory quality, non-infringement of third party rights, and fitness for a particular purpose or use are disclaimed in respect of any Source or Product to the maximum extent permitted by law. The Licensor makes no representation that any Source or Product does not or will not infringe any patent, copyright, trade secret or other proprietary right. The entire risk as to the use, quality, and performance of any Source or Product shall be with You and not the Licensor. This disclaimer of warranty is an essential part of this Licence and a condition for the grant of any rights granted under this Licence.

6.2 EXCLUSION AND LIMITATION OF LIABILITY -- The Licensor shall, to the maximum extent permitted by law, have no liability for direct, indirect, special, incidental, consequential, exemplary, punitive or other damages of any character including, without limitation, procurement of substitute goods or services, loss of use, data or profits, or business interruption, however caused and on any theory of contract, warranty, tort (including negligence), product liability or otherwise, arising in any way in relation to the Covered Source, modified Covered Source and/or the Making or Conveyance of a Product, even if advised of the possibility of such damages, and You shall hold the Licensor(s) free and harmless from any liability, costs, damages, fees and expenses, including claims by third parties, in relation to such use.
