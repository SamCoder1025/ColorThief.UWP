# Get Dominant Color

A code for grabbing the color palette from an image. Uses C# and .NET to make it happen.

### This is a ported project of [Color Thief](https://github.com/lokesh/color-thief/) 

Many thanks for C# code [UWP Version](https://gist.github.com/zumicts/c5050a36e4ba742dc244)

## Available at NuGet. 
https://www.nuget.org/packages/ksemenenko.ColorThief/

### Platforms:
|Platform|Supported|Version|
| ------------------- | :-----------: | :------------------: |

|Windows 10 UWP|Yes|10+|
|Windows Phone 8|No|8.0+|
|Windows Phone 8.1|No|8.1+|
|Windows Store|No|8.1+|
|Xamarin.iOS|No|iOS 6+|
|Xamarin.Android|No|API 10+|
|Xamarin.Mac|No||
|Desktop .NET 4.5|Yes||
|Desktop .NET 4.6|Yes||

## How to use

### Get the dominant color from an image
```cs
var colorThief = new ColorThief();
colorThief.GetColor(sourceImage);
```

### Build a color palette from an image

In this example, we build an 8 color palette.

```cs
var colorThief = new ColorThief();
colorThief.GetPalette(sourceImage, 8);
```
