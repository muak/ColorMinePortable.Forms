# ColorMinePortable for Xamarin.Forms

This is the extensions that it made ColorMinePortable(https://github.com/muak/ColorMinePortable) correspond to Xamarin.Forms.

## Nuget Installation

```bash
Install-Package ColorMinePortable.Forms
```

## Extentions

* Xamarin.Forms.Color conversion

## Xamarin Conversion

```csharp
var xcolor = Xamarin.Forms.Color.Red;
var rgb = xcolor.To<Rgb>(); //xamarin to ColorMine Rgb
var xcolor2 = rgb.ToXamarinForms(); // ColorMine Rgb to xamarin
```

## Dependency

* ColorMinePortable
* Xamarin.Forms