# LabVIEW Repository Template

This is a template repository for LabVIEW libraries. Source code from the source directory can be built into VIPM packages using the [build specification](./package/__LIBRARY_NAME__.vipb).

#### Usage

- Clone this repository

- Rename [.lvproj](./__LIBRARY_NAME__.lvproj) and [.vipb](./package/__LIBRARY_NAME__.vipb) files and update build specification metadata (product name, company name, author name, ...)

- Add library source code to /source

- Add some example VIs for your library to the .lvproj (the \*.vi files should be placed in /example). The .lvproj file should include the source library. In this way, you can install specific builds of your library into /vi.lib or /user.lib to use in other projects without causing dependency issues in your library's .lvproj

- Consider adding some documentation in the /doc folder.

- [Gather Images.vi](./doc/img/Gather Images.vi) saves images of your VIs and controls. These images can be found in the /doc/img folder under the same relative directory as in the project's main folder:
> `/source/...path...to.../Source VI.vi` becomes `/doc/img/...path...to.../Source VI.vi.png`

#### Requirements

- A LabVIEW installation
- [JKI VI Package Manager](https://vipm.jki.net/)
