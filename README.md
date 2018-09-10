# LabVIEW Library Rpository Template

This is a template repository for LabVIEW libraries. Source code from the [source](source) directory can be built into VIPM packages using the [build specification](package/__LIBRARY_NAME__.vipb).

#### Usage

1) Clone this repository
2) Rename [.lvproj](__LIBRARY_NAME__.lvproj) and [.vipb](package/__LIBRARY_NAME__.vipb) files and update build specification metadata (product name, company name, author name, ...)
3) Add library source code to [/source](source)
4) Add some example VIs for your library to the .lvproj (the *.vi files should be placed in [/example](example)). The .lvproj file should include the source library. In this way, you can install specific builds of your library into /vi.lib or /user.lib to use in other projects without causing dependency issues in your library's .lvproj

#### Requirements

- A LabVIEW installation
- [JKI VI Package Manager](https://vipm.jki.net/)
