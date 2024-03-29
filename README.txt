Audacity(R) v2.4.2.AR0: free, open source, cross-platform audio software for 
multi-track recording and editing: https://github.com/irulanCorrino/audacity-2-4-2 

Audacity is copyright (c) 1999-2019 by Audacity Team. This copyright 
notice applies to all documents in the Audacity source code archive, 
except as otherwise noted (mostly in the lib-src subdirectories). 
"Audacity" is a registered trademark of Dominic Mazzoni. 

The Audacity documentation is licensed under the Creative Commons
Attribution 3.0 license: https://creativecommons.org/licenses/by/3.0/legalcode .

/* ____________________________________________________________________________________ */
WARNING: this version of Audacity is 'An Antique Release' --it is maintained
not by Audacity Team, who have moved on to produce Audacity v3, but a single
maintainer irulanCorrino. i relicense this software piece under GPL v3.0-or-later.
previous maintainers were reckless enough to have a bunch of incompatible clauses
in individual files [GPL-generic vs. GPL-2 vs. GPL-2-or-later], which case effectively
invalidate any of their potential claims of license agreement violation.

nevertheless i ought to provide users of this version with links to previous
maintainer`s resources because i cannot maintain a dedicated site for it.
be aware that you would need to dive deeply into archived forum topics or
read past versions of the manual; they would not provide you with a support
for this antique version ...maybe i would be able to perform bugfixes however.

my intent was to keep this version 'as it is' but probably i would try improving
it in a future, i am goint to keep its version number as associated with app`s name
and to introduce different supplementary release naming scheme in a case of futher
development ['AntiqueRelease<INTEGER>'].
so for giving 'feedback on Audacity, suggestions for new or improved features, 
and bug reports' you would have to contact me on GitHub:
https://github.com/irulanCorrino/audacity-2-4-2/issues
https://github.com/irulanCorrino/audacity-2-4-2/pulls

here is how it was back then:
'User support is provided on Audacity Forum:
https://forum.audacityteam.org/ .

We welcome feedback on Audacity, suggestions for new or improved features, 
and bug reports. Please visit 
https://forum.audacityteam.org/viewforum.php?f=25 .

Compilation instructions for Audacity are provided in the source code:
* Windows: win\build.txt
* macOS: mac/build.txt
* GNU/Linux: linux/build.txt 

You can ask for help with compilation problems at:
https://forum.audacityteam.org/viewforum.php?f=19 .

If you want to suggest some simple text change in our code, please submit a 
pull request on https://github.com/audacity/audacity/pulls . It's usually 
best to discuss functional code changes with us first on audacity-devel: 
https://lists.sourceforge.net/lists/listinfo/audacity-devel .'
                                                            irulan
                                                             February 3rd, 2023

/* ____________________________________________________________________________________ */


Version 2.4.2.AR0

Contents of this README:

1.  Licensing
2.  Changes since version 2.4.1
3.  Known Issues at Release
4.  Source Code, Libraries and Additional Copyright Information

--------------------------------------------------------------------------------

1. Licensing
    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.


--------------------------------------------------------------------------------

2. Changes since version 2.4.1: 


Improvements

 * Audacity is now built with (our version of) the wx3.1.3 library.
   Previously we used wx3.1.1.
 * We added a command 'Reset Configuration' to reset to default 
   settings.
 * MP3 Audio is now exported without padding.

See also: https://wiki.audacityteam.org/wiki/New_features_in_Audacity_2.4.2


Bug Fixes

 Over 30 bugs in 2.4.1 fixed, including:

 * 2442 - Windows: Crash when importing (or editing) to a disk 
   with insufficient disk space available
 * 2471 - Mix Stereo down to Mono fails if space at start of track.
 * 2439 - Mix and Render to New Track selects left channel of new
   stereo track


See also: https://wiki.audacityteam.org/wiki/Release_Notes_2.4.2


-------------------------------------------------------------------------------


3. Some Known Issues in 2.4.2:

For best workarounds and other known issues in 2.4.2, please see:
  https://wiki.audacityteam.org/wiki/Release_Notes_2.4.2/Issues 


-------------------------------------------------------------------------------

4.  Source Code, Libraries and Additional Copyright Information

Source code to this program is always available; for more information visit
our web site at:

  https://www.audacityteam.org/download/source

Audacity is built upon other free libraries; some of these libraries may have
come with Audacity in the lib-src directory.  Others you are expected to install
first if you want Audacity to have certain capabilities.  Most of these libraries
are not distributed under the terms of the GPL, but rather some other free,
GPL-compatible license.  Specifically:

  expat: BSD-like license.
    Provides XML parsing.  Included with Audacity.

  FFmpeg: GPL or LGPL (according to how you obtain/configure it)
    Provides decoding/encoding of additional formats. Optional separate
    download.

  libid3tag: GPL
    Reads/writes ID3 tags in MP3 files.  Optional
    separate download as part of libmad.

  libflac: Xiph.Org BSD-like licence (the parts we use)
    Decodes and Encodes Free Lossless Audio Codec files. Optional separate
    download.

  libmad: GPL
    Decodes MP3 files.  Optional separate download.

  libmp3lame: LGPL
    Encodes MP3 files.

  libnyquist: BSD-like license.
    Functional language for manipulating audio; available
    within Audacity for effects processing.

  libogg: BSD-like license.
    Optional separate download, along with libvorbis.

  libsndfile: LGPL
    Reads and writes uncompressed PCM audio files.
    Included with Audacity.

  libsoxr: LGPL
    The SoX Resampler library performs one-dimensional sample-rate conversion.

  libvamp: new-style BSD
    Plug-in interface and support library for audio analysis plug-ins.
    Included with Audacity.

  libvorbis: BSD-like license.
    Decodes and encodes Ogg Vorbis files.  Optional
    separate download.

  lv2: a merging of the lilv (ISC license), lv2 (LGPL), msinttypes, serd (ISC), 
    sord, sratom, and suil libraries to support LV2 plug-ins. 

  portsmf: BSD-like license.
    library for reading and writing midi files. Included with Audacity

  sbsms: GPL v2
    Pitch and tempo changing library. Included in Audacity

  SoundTouch: LGPL
    Changes tempo without changing pitch and vice versa.
    Included in audacity

  Twolame: LGPL
    Encodes MPEG I layer 2 audio (used in DVDs and Radio). Optional separate
    download.

  wxWidgets: wxWindows license (based on LGPL)
    Cross-platform GUI library - must be downloaded and
    compiled separately.


For more information, see the documentation inside each library's
source code directory.

--------------------------------------------------------------------------------
Additional copyright information:
--------------------------------------------------------------------------------

Nyquist

Copyright (c) 2000-2002, by Roger B. Dannenberg
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this
list of conditions and the following disclaimer.

Redistributions of source code must retain the copyright notice, the
list of conditions, and the disclaimer, all three of which appear below under
"COPYRIGHT AND LICENSE INFORMATION FOR XLISP."

Redistributions in binary form must reproduce the above copyright notice, this
list of conditions and the following disclaimer in the documentation and/or
other materials provided with the distribution.

Redistributions in binary form must reproduce the copyright notice, the
list of conditions, and the disclaimer, all three of which appear below under
"COPYRIGHT AND LICENSE INFORMATION FOR XLISP," in the documentation
and/or other materials provided with the distribution.

Neither the name of Roger B. Dannenberg, Carnegie Mellon University, nor the
names of any contributors may be used to endorse or promote products derived
from this software without specific prior written permission.

COPYRIGHT AND LICENSE INFORMATION FOR XLISP (part of Nyquist):

Copyright (c) 1984-2002, by David Michael Betz
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice,
this list of conditions and the following disclaimer.

Redistributions in binary form must reproduce the above copyright notice, this
list of conditions and the following disclaimer in the documentation and/or
other materials provided with the distribution.

Neither the name of David Michael Betz nor the names of any contributors may be
used to endorse or promote products derived from this software without specific
prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDER AND
CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES,
INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR
CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT
NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT,
STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF
ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
