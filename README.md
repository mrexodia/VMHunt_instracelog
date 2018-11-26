# instracelog

Windows build files for [VMHunt PIN Trace tool](https://github.com/s3team/VMHunt/tree/master/tracer). Based on the [tiny_tracer](https://github.com/hasherezade/tiny_tracer) project by [hasherezade](http://hasherezade.net).

## How to build?

To compile the prepared project you need to use [Visual Studio 2017](https://visualstudio.microsoft.com/downloads/). It was tested with [Intel Pin 3.7](https://software.intel.com/en-us/articles/pin-a-binary-instrumentation-tool-downloads).

- Clone this repo into `\source\tools` that is inside your PIN root directory.
- Copy `instracelog.cpp` next to `instracelog.sln`
- Open the project in VS 2017 and build.
