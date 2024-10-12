# Foundations Installations

## Setting up a second computer
If you are using a different computer for server side than you did for front end (or setting up Windows with Bootcamp on your Mac), you will need to do all of the front end installations first. They can be found [here](https://classroom.google.com/c/NTcxMzcyMjE5Mzk2?cjc=kxtsj3b).

## Prerequisites

### Mac Users

- You can choose to use either Visual Studio Code
  - <b>Visual Studio Code</b>
    - Ensure you have Visual Studio Code installed on your system. If not, download and install it from the [official website](https://code.visualstudio.com/).
    - Use the instructions below to download and verify that you have <b>.NET 8</b> installed on your machine.
    - Use the instructions below to install the C# Extension Required for .NET development in VS Code.

### Windows Users
- You can use Visual Studio for Windows. However, you can also use Visual Studio Code. 
  - <b>Visual Studio (Recommended)</b>
    - Use the instructions below to download and verify that you have <b>.NET 8</b> installed on your machine.
    - [Download Visual Studio Community for Windows](https://visualstudio.microsoft.com/vs/community/)
  - <b>Visual Studio Code</b>
    - Ensure you have Visual Studio Code installed on your system. If not, download and install it from the [official website](https://code.visualstudio.com/).
    - Use the instructions below to download and verify that you have <b>.NET 8</b> installed on your machine.
    - Use the instructions below to install the C# Extension Required for .NET development in VS Code.

## Installing .NET 8 SDK

[Download it for Windows here](https://download.visualstudio.microsoft.com/download/pr/6224f00f-08da-4e7f-85b1-00d42c2bb3d3/b775de636b91e023574a0bbc291f705a/dotnet-sdk-8.0.403-win-x64.exe
) <br>
[Download it for M1/M2 Macs here](https://download.visualstudio.microsoft.com/download/pr/35b0fb29-cadc-4083-aa26-6cecd2e7ffa1/1a9972a435b73ffdd0b462f979ea5b23/dotnet-sdk-8.0.403-osx-arm64.pkg
) <br>
[Download it for Intel Macs here](https://download.visualstudio.microsoft.com/download/pr/d6b3fe61-3c0e-45da-9e37-cef64d4fd3eb/28d536e0ecfbb330ab49454a5e3962f6/dotnet-sdk-8.0.403-osx-x64.pkg
)

When the download completes, run (open) the file downloaded by your browser and click `Install` when prompted to. 

Verify that the install has worked by opening a new terminal (or bash) and running `dotnet --version`. You should see `8.0.403`, or something similar. If your terminal doesn't recognize the command, ask an instructor to help. 


## C# Extension for VS Code
The official C# extension from Microsoft for VS Code provides a number of helpful features including syntax highlighting, Intellisense (code completion and hints) and tools for debugging in your editor.

Install it by opening Vistual Studio Code, clicking on extension tab (open with Ctrl+Shift+X), searching for `C#`, and select the `C# Dev Kit` extension by Microsoft and click `Install`.
