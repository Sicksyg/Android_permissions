# Android_permissions

A small dataset in the form of a .json file with the app permissions used by Android. The data is obtained from Apples documentation at: https://developer.android.com/reference/android/Manifest.permission#constants


## Example of the dataset:
```
{
    "permissions": {
        "1": {
            "pkey": "NSBluetoothAlwaysUsageDescription",
            "commonName": "Bluetooth access",
            "descriptionSimple": "A message that tells the user why the app needs access to Bluetooth.",
            "descriptionDetailed": "This key is required if your app uses Bluetooth. The system prompts the user to grant permission to access Bluetooth when the app attempts to use it. You must provide a string value that explains why your app needs access to Bluetooth. This message is displayed in the permission prompt.",
            "protectionLevel": "Low",
            "link": "https://developer.apple.com/documentation/bundleresources/information_property_list/nsbluetoothalwaysusagedescription"
            }, ...
    }
}
```

## License

This dataset is lisenced under Creative Commons Attribution 4.0 International CC BY 4.0
