#stl2srt.py

A program to convert subtitles files stored using the EBU (European Broadcasting Union) file format to the much simpler SRT file format. SRT also has the benfir of being trivial to convert to WebVTT, the [W3C](http://www.w3c.org) sanctioned subtitle format

## Usage
  
`stl2srt.py [-h] [--help] [-d] [--debug] input.stl output.srt`

>  `-h`<br/>
>  `--help`  Display this usage notice
>
>  `-d`<br/>
>  `--debug` Display raw frames as they're read

## Bibliography

* Wikipedia has some information:<br/>
[Subtitle captioning](http://en.wikipedia.org/wiki/Subtitle_%28captioning%29)

* The file format description is available at:<br/>
[EBU spec (PDF)](http://tech.ebu.ch/docs/tech/tech3264.pdf)

## License

This software is release under the GNU GPL v2 terms and conditions. See the GPL.txt file for the complete license text
