# RobocodeBot

A `dotnet new` template for creating **Robocode Tank Royale** bots in C#.

This template creates:
- A custom-named bot class
- A matching `.csproj`
- Proper namespaces
- Preconfigured Robocode Tank Royale dependencies

---

## Installation

Install the template from NuGet:

Open command line and paste in:

```bash
dotnet new install RobocodeBot::1.0.4
```

Once you have the package installed, use file explorer to navigate to the folder that will house your bot.

Click on the file path at the top, type cmd, then press enter to open the command line in your desired folder.

Once you have opened your command line in the correct folder paste in the following command:

```bash
dotnet new robocodebot -n YourBotName
```

A new folder with the name of your bot should have been created.

inside you see all the files you will need to program your bot (however the .cs file is probably the most important to you).

Once you have created your bot folder, follow this link to view the official documentation for programming your bot:

https://robocode.dev/