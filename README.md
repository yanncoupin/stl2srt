#to_srt.py

A command line utility written in Python to convert some variants of subtitles in to the much simpler SRT file format with optional formatting. SRT also has the benefit of being trivial to convert to WebVTT, the [W3C](http://www.w3c.org) sanctioned subtitle format. Supported input file formats are:

* STL subtitles files stored using the EBU (European Broadcasting Union) file format
* TT (W3C Timed Text) files and their variants from the SMPTE and the EBU

This conversions can be optionally done while preserving as much formatting as possible. The output formatting is done using inline html tags and the following attributes are supported:

* bold
* italic
* underlined
* color

## Usage
  
`to_srt.py [-h] [--help] [-d] [--debug] [-r] [--rich] [-s] [--stl] [-t] [--tt] input_file output.srt`

>  `-h`<br/>
>  `--help`  Display this usage notice
>
>  `-d`<br/>
>  `--debug` Display raw frames as they’re read
>
>  `-r`<br/>
>  `--rich` Keep the rich formatting contained in the STL file
>  
>  `-s`<br/>
>  `--stl` Source format is STL, this is actually the default value and isn’t really useful
>
>  `-t`<br/>
>  `--tt` Source format is Time Text


## Bibliography

* Wikipedia has some information about:
	* [Subtitle captioning](http://en.wikipedia.org/wiki/Subtitle_%28captioning%29)
	* [SRT unofficial reference](http://en.wikipedia.org/wiki/SubRip#SubRip_text_file_format)

* The file format specifications are available at:
	* [EBU STL spec (PDF)](http://tech.ebu.ch/docs/tech/tech3264.pdf)
	* [W3C Time Text reference](http://www.w3.org/TR/2010/REC-ttaf1-dfxp-20101118/)
	* [SMPTE Time Text extensions (PDF)](https://www.smpte.org/sites/default/files/st2052-1-2010.pdf)
	* [EBU Timed Text extensions (PDF)](http://tech.ebu.ch/docs/tech/tech3350.pdf?vers=1.0)

## License

Starting with version 2.1 released on September 22nd, 2014, this software is now released under the Apache License, Version 2.0

You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Previous versions, up to 2.0.8, were licensed under the GPL v2 terms and conditions.