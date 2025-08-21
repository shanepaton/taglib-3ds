# TagLib-3DS - TagLib for the Nintendo 3ds

#### Build Instructions

```bash
mkdir build-3ds
cd build-3ds
cmake -DCMAKE_TOOLCHAIN_FILE=../3ds.toolchain.cmake ..

cmake --build .
```
Copy the output from ```build-3ds``` into your DevkitPro libraries folder.

https://taglib.org/

TagLib is a library for reading and editing the metadata of several
popular audio formats. Currently, it supports both ID3v1 and ID3v2
for MP3 files, [Ogg Vorbis][] comments and ID3 tags
in [FLAC][], MPC, Speex, WavPack, TrueAudio, WAV, AIFF, MP4, APE, ASF,
DSF, DFF and AAC files.

TagLib is distributed under the [GNU Lesser General Public License][]
(LGPL) and [Mozilla Public License][] (MPL). Essentially that means that
it may be used in proprietary applications, but if changes are made to
TagLib they must be contributed back to the project. Please review the
licenses if you are considering using TagLib in your project.

  [Ogg Vorbis]: https://xiph.org/vorbis/
  [FLAC]: https://xiph.org/flac/
  [GNU Lesser General Public License]: https://www.gnu.org/licenses/lgpl.html
  [Mozilla Public License]: https://www.mozilla.org/MPL/MPL-1.1.html
