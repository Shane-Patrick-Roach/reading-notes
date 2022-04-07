# Android: Location



## Overview

---

- Using the Google Play services location APIs, your app can request the last known location of the user's device. In most cases, you are interested in the user's current location, which is usually equivalent to the last known location of the device.
- Specifically, use the fused location provider to retrieve the device's last known location. The fused location provider is one of the location APIs in Google Play services.


### Get last known location

- In your activity's `onCreate()` method, create an instance of the Fused Location Provider Client as the following code snippet shows.
- Once you have created the Location Services client you can get the last known location of a user's device. When your app is connected to these you can use the fused location provider's `getLastLocation()` method to retrieve the device location.
- The `getLastLocation()` method returns a Task that you can use to get a Location object with the latitude and longitude coordinates of a geographic location.


###  The location object may be null in the following situations:

1. Location is turned off in the device settings. The result could be null even if the last location was previously retrieved because disabling location also clears the cache.
2. The device never recorded its location, which could be the case of a new device or a device that has been restored to factory settings.
3. Google Play services on the device has restarted, and there is no active Fused Location Provider client that has requested location after the services restarted. To avoid this situation you can create a new client and request location updates yourself. For more information, see Receiving Location Updates.

### Best Location Estimate

- `getLastLocation()` gets a location estimate more quickly and minimizes battery usage that can be attributed to your app. However, the location information might be out of date, if no other clients have actively used location recently.
- `getCurrentLocation()` gets a fresher, more accurate location more consistently. However, this method can cause active location computation to occur on the device



## Resources/Citations

---

- [Location Docs](https://developer.android.com/training/location)
