### FsiPaket dotnet tempalte

### Installation
1. `dotnet new -i <FILE_SYSTEM_DIRECTORY>`
2. `.paket/paket.exe install` (on windows)/ `mono .paket/paket.exe install` (on linux).
3. If some additional package is desired add it to `paket.dependencies`.
4. Don't forget to reference libs in `Program.fsx`.
5. Have fun with F# scripting!