---
-api-id: M:Windows.UI.Xaml.Controls.Maps.MapControl.GetLocationFromOffset(Windows.Foundation.Point,Windows.Devices.Geolocation.AltitudeReferenceSystem,Windows.Devices.Geolocation.Geopoint@)
-api-type: winrt method
---

<!-- Method syntax.
public void MapControl.GetLocationFromOffset(Point offset, AltitudeReferenceSystem desiredReferenceSystem, Geopoint location)
-->

# Windows.UI.Xaml.Controls.Maps.MapControl.GetLocationFromOffset

## -description
Converts a point on the map to a geographic location.
## -params

## -param offset
A point on the map to convert to a geographic location.

## -param desiredReferenceSystem
The altitude reference system of the geographic point.

## -param location
When this method returns, contains the corresponding geographic location.

## -remarks
Compare the [GetOffsetFromLocation](mapcontrol_getoffsetfromlocation.md) method. This method will throw an exception if the point is invalid.

## -see-also
[Display maps with 2D, 3D, and Streetside views](http://msdn.microsoft.com/library/3839e00b-2c1e-4627-a45f-6dda98d7077f).
## -examples
