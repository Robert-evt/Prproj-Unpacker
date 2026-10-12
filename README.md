# .prproj Perl Unpacker

A Perl utility for unpacking Adobe Premiere Pro project files into XML.

## Requirements

- Perl
- `IO::Uncompress::Gunzip` (Perl module)

## Usage

Extract the XML from a `.prproj` file and save it to the default output location:

```powershell
perl .\unpack.pl "path\to\your\file.prproj"
```

Specify a custom output file:

```powershell
perl .\unpack.pl "path\to\your\file.prproj" "path\to\output\file.xml"
```

## License

See [LICENSE](LICENSE) for details.