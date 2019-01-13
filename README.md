﻿# Salesforce.NetCore.Streaming.CLI

This project is an accelerator for developing applications that subscribe to the [Streaming API](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/) from Salesforce.  This includes Push Topics, Change Data Capture, generic events, and platform events.

## Prerequisites

* .NET Core 2.1+
* Visual Studio 2017+ / Visual Studio Code

## Installation

Use the [dotnet cli](https://docs.microsoft.com/en-us/dotnet/core/tools/) to build and run the application.

```bash
dotnet build
dotnet run
```

## Usage

```c#
// TODO:  Place sample code here
```

## Credits

The CometD.NET library in this project is a modified version of the [CometD.NET Library](https://github.com/Oyatel/CometD.NET) which works on versions of .NET prior to Core.  I made alterations to this, primarily around how Json serialization works to make it compatible with .NET Core.  Some additional modifications were also made to the library to enhance it.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)