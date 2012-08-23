#stl2srt.py

A program to convert STL subtitles files stored using the EBU (European Broadcasting Union) file format to the much simpler SRT file format with optional formatting. SRT also has the benefit of being trivial to convert to WebVTT, the [W3C](http://www.w3c.org) sanctioned subtitle format

## Usage
  
`stl2srt.py [-h] [--help] [-d] [--debug] input.stl output.srt`

>  `-h`<br/>
>  `--help`  Display this usage notice
>
>  `-d`<br/>
>  `--debug` Display raw frames as they're read
>
>  `-r`<br/>
>  `--rich` Keep the rich formatting contained in the STL file

## Bibliography

* Wikipedia has some information about:
	* [Subtitle captioning](http://en.wikipedia.org/wiki/Subtitle_%28captioning%29)
	* [SRT unofficial reference](http://en.wikipedia.org/wiki/SubRip#SubRip_text_file_format)

* The file format description is available at:
	* [EBU spec (PDF)](http://tech.ebu.ch/docs/tech/tech3264.pdf)

## License

This software is release under the GNU GPL v2 terms and conditions. See the GPL.txt file for the complete license text
