# Foundations Installations

## Setting up a second computer
If you are using a different computer for server side than you did for front end (or setting up Windows with Bootcamp on your Mac), you will need to do all of the front end installations first. They can be found [here](https://classroom.google.com/c/NTcxMzcyMjE5Mzk2?cjc=kxtsj3b).

## Prerequisites
The .NET SDK includes all of the command line tools you will need to build and run your .NET programs for the first part of the course.

1. <b>Visual Studio Code:</b> Ensure you have Visual Studio Code installed on your system. If not, download and install it from the [official website](https://code.visualstudio.com/).
2. <b>.NET 8 SDK:</b> Use the instructions below to download and verify that you have .NET 8 installed on your machine.
3. <b>C# Extension for Visual Studio Code:</b> Required for .NET development in VS Code.

## Installing .NET 8 SDK

[Download it for Windows here](https://download.visualstudio.microsoft.com/download/pr/9e753d68-7701-4ddf-b358-79d64e776945/2a58564c6d0779a7b443a692c520782f/dotnet-sdk-8.0.203-win-x64.exe
) <br>
[Download it for M1/M2 Macs here](https://download.visualstudio.microsoft.com/download/pr/1951c62f-487d-4002-b3e6-92677e88b8b1/b1ed2348dbe68ac3f499252b7c9017e4/dotnet-sdk-8.0.203-osx-arm64.pkg
) <br>
[Download it for Intel Macs here](https://download.visualstudio.microsoft.com/download/pr/bcfcba7d-4a1d-4435-95c2-7c4143e01007/68804b02e9a3bcfd6f26b04d01219791/dotnet-sdk-8.0.203-osx-x64.pkg
)

When the download completes, run (open) the file downloaded by your browser and click `Install` when prompted to. 

Verify that the install has worked by opening a new terminal (or bash) and running `dotnet --version`. You should see `8.0.203`, or something similar. If your terminal doesn't recognize the command, ask an instructor to help. 


## C# Extension for VS Code
The official C# extension from Microsoft for VS Code provides a number of helpful features including syntax highlighting, Intellisense (code completion and hints) and tools for debugging in your editor.

Install it by opening Vistual Studio Code, clicking on extension tab (open with Ctrl+Shift+X), searching for `C#`, and select the `C# Dev Kit` extension by Microsoft and click `Install`.
