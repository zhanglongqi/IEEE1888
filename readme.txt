-------------------------------------------------- -------
IEEE1888 C language version of the protocol stack software
  Author: Ochiai Hideya
          Version: v201310
-------------------------------------------------- -------

1. first
This package, the C language version IEEE1888 protocol stack
It is included in the source code.

File configuration is as follows.
- Ieee1888.h main header file
- Client communication stub of query / data method of ieee1888_client.c IEEE1888
- Ieee1888_object_factory.c IEEE1888 generation plant of the object (transport and body, etc.)
- Sample implementation of ieee1888_sample_gw.c GW
- Sample implementation of ieee1888_sample_app.c APP
- Server communication stub of query / data method of ieee1888_server.c IEEE1888
- A collection of ieee1888_util.c useful functions (dump display of objects, etc.)
- Ieee1888_XMLgenerator.h header files for XML serialization
- Ieee1888_XMLgenerator.c IEEE1888 XML serialization of the object (generator) implementation
- Ieee1888_XMLparser.h header files for XML deserialized
- Ieee1888_XMLparser.c IEEE1888 XML deserialization function of the object (analyzer) implementation
- Ieee1888_datapool.h header file storage function implementation of the re-transmission waiting data
- Ieee1888_datapool.c storage function implementation of the re-transmission waiting data
- Makefile make build running configuration file
- Readme.txt this file

2. How to Build
In the Linux environment,
$ Make
It runs the.

Above,
ieee1888_sample_app and ieee1888_sample_gw
Of the executable file is generated.
This build is complete.

3. Improvement of methods
ieee1888_sample_gw.c has become FETCH, and WRITE server of the sample.
ieee1888_sample_app.c has become FETCH, a sample of WRITE client.
These were in the template, you will be able to implement a new application (GW, APP, etc.).

Other files, because it uses as a library, you do not need to be edited.
For more information, please refer to the "IEEE1888 protocol textbook (Impress Japan)".


4. Disclaimer
For events resulting from the use of this software,
Since the author and its related organizations can not assume the responsibility,
Please note.

5. license
BSD is the license.
Regardless of the personal and commercial, are available.

6. Updated content
· V201310 Edition <- v201212 edition of the update
- Improvements to work with IPv6 only environment (special thanks to Hiroyuki Ikegami)
- Eliminate the connection failure problem in ieee1888_client and ieee1888_server (special thanks to Motomasa Tanaka (motomasa-tanaka@mayekawa.co.jp))
- Add the license statement to the source code
- Ieee1888_server gcc build-time to came out warning: format not a literal ... are eliminated

7. Bug reports
Please contact me to Ochiai Hideya ochiai@vdec.u-tokyo.ac.jp.
