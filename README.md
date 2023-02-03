<p align="center">
  <img src="https://user-images.githubusercontent.com/98284211/216677522-ce61c475-77f2-42cc-8207-b1c1c8728104.png" />
</p>

## <div align="center">audacity-2-4-2</div>

 <div align="center"><ins>minimalist DAW [old school version w/o 'non-destructive editing' or SQLite3-based file format]</ins></div>


---

**Audacity** is an easy-to-use, multi-track audio editor and recorder for Windows, Mac OS X, GNU/Linux and other operating systems. Developed by a group of volunteers as open source.
<img align="right" width="33%" alt="Audacity screenshot, Architecture Graph" title="Audacity running with designed by me theme; Architecture Graph superimposed" src="https://user-images.githubusercontent.com/98284211/216704788-c52c2e40-5ad1-4103-8a39-70a24949a0ba.png">

- **Recording** from any real, or virtual audio device that is available to the host system.
- **Export / Import** a wide range of audio formats, extendible with FFmpeg.
- **High quality** using 32-bit float audio processing.
- **Plug-ins** Support for multiple audio plug-in formats, including VST[^1], LV2, AU[^2].
- **Macros** for chaining commands and batch processing.
- **Scripting** in Python, Perl, or any language that supports named pipes.
- **Nyquist** Very powerful built-in scripting language that may also be used to create plug-ins.
- **Editing** multi-track editing with sample accuracy and arbitrary sample rates.
- **Accessibility** for VI users.
- **Analysis and visualization** tools to analyze audio, or other signal data.



## <div align="center">Maintainer`s notice:</div>
- this version of Audacity is **<ins>'An Antique Release'</ins>** --it is maintained not by Audacity Team, who have moved on to produce Audacity v3, but a single maintainer `irulanCorrino`.
    - <del>[to my own risk]</del> i relicense this software piece under GPL v3.0-or-later.
    - `Audacity team` [previous maintainers] were reckless enough to have a bunch of incompatible clauses in individual files [GPL-generic vs. GPL-2 vs. GPL-2-or-later], which case effectively invalidate any of their potential claims of license agreement violation.
    - nevertheless i ought to provide users of this version with links to previous maintainer`s resources because i cannot maintain a dedicated site for it.
    - be aware that you would need to dive deeply into archived forum topics or read past versions of the manual; they would not provide you with a support for this antique version
    - ##### ...maybe i would be able to perform bugfixes however.

## <div align="center">Disclaimer:</div>
<img align="right" width="33%" alt="Audacity Layers" title="Audacity`s Architecture Graph" src="https://user-images.githubusercontent.com/98284211/216709408-052edd2d-d229-47cd-89f3-f891f0a91d3c.png">

- my intent was to keep this version <ins>'as it is'</ins> but probably i would try improving it in a future; i am goint to keep its version number as associated with app's name and to introduce different supplementary release naming scheme in a case of its futher development under Linux [`AntiqueRelease<INTEGER>`].
- ##### so for giving 'feedback on Audacity, suggestions for new or improved features, and bug reports' you would have to contact me on GitHub:
    - https://github.com/irulanCorrino/audacity-2-4-2/issues
    - https://github.com/irulanCorrino/audacity-2-4-2/pulls

### <div align="center">here is how it was back then:</div>
#### <div align="center">[ *~Warning:~* newer manual or forum topics may not be applicable to this particular software version ]</div>
<img align="left" width="7%" src="https://user-images.githubusercontent.com/98284211/216714450-3c73d748-b980-454f-8d0f-45c5d69199d7.png">

- Help with using Audacity is available from the [Audacity Forum](https://forum.audacityteam.org/).
- Information for developers is available from the [Audacity Wiki](https://wiki.audacityteam.org/wiki/For_Developers).

- We welcome feedback on [**Audacity**](https://www.audacityteam.org), suggestions for new or improved features, and bug reports. Please visit https://forum.audacityteam.org/viewforum.php?f=25

- Compilation instructions for Audacity are provided in the source code:
    * Windows: win\build.txt[^3]
    * macOS: mac/build.txt[^3]
    * GNU/Linux: linux/build.txt 

      - You can ask for help with compilation problems at: https://forum.audacityteam.org/viewforum.php?f=19

- If you want to suggest some simple text change in our code, please submit a pull request on https://github.com/audacity/audacity/pulls
- It's usually best to discuss functional code changes with us first on audacity-devel: https://lists.sourceforge.net/lists/listinfo/audacity-devel
---
##### <div align="right">irulan</div>
##### <div align="right">February 4th, 2023</div>
[^1]: only in MS Windows OS
[^2]: only in Apple macOS
[^3]: cannot help you people, i do not have any Windows OS or macOS systems, and i am even not interested in development for those two commercial platforms --irulan
