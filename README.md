# Xamarin.Amplitude.Android

Xamarin.Android Bindings for Amplitude ([Website](https://amplitude.com), [Setup Instructions](https://developers.amplitude.com/docs/android))

## NuGet Feed

NuGet packages are built using Azure DevOps: [![Build Status](https://funmusic.visualstudio.com/Xamarin%20Amplitude%20Bindings/_apis/build/status/Production-Bindings-Xamarin.Amplitude.Android?branchName=refs%2Ftags%2Frelease-bindings-v2.31.1.3)](https://funmusic.visualstudio.com/Xamarin%20Amplitude%20Bindings/_build/latest?definitionId=168&branchName=refs%2Ftags%2Frelease-bindings-v2.31.1.3)

NuGet packages are published on [nuget.org](https://www.nuget.org/packages/Xamarin.Amplitude.Android/).

## Versioning Scheme

The versioning scheme of `Xamarin.Amplitude.Android` is derived from the versioning of `com.amplitude:android-sdk`.

### Example:

| com.amplitude:android-sdk | Xamarin.Amplitude.Android | Note |
|:--|:--|:--|
| 3.4.1 | 3.4.1.1 | First version of bindings for 3.4.1 |
| 3.4.1 | 3.4.1.17 | Bindings for 3.4.1 containing fixes |

## Trouble Shooting

If you encounter errors like `Java.Lang.NoClassDefFoundError: Failed resolution of: Lkotlin/jvm/internal/Intrinsics`, consider to explicitly reference the transitive dependencies of `Xamarin.Amplitude.Android`:

* Xamarin.Kotlin.StdLib
	* Version >= 1.4.10
