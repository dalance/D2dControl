# D2dControl

[![Build status](https://ci.appveyor.com/api/projects/status/ey3x8chjrxwa967s?svg=true)](https://ci.appveyor.com/project/dalance/d2dcontrol)

**D2dControl** is a WPF Control for Direct2D with SharpDX.

## Install
Download from [nuget](https://www.nuget.org/packages/D2dControl/)

## Dependencies
- SharpDX ( >= 3.0.0 )

## Usage
Create a class derived from `D2dControl.D2dControl`, and override `Render` method.
In `Render` method, you can use `SharpDX.Direct2D1.RenderTarget` for calling Direct2D functions.
See [sample project](https://github.com/dalance/D2dControl/tree/master/Sample) for details.