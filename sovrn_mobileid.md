# Mobile ID Import Methods

## FTP

Available for asynchronous batch transfers. Please format inputs in the following manner:

```
{
   "kind": "directory#mobiledevices",
   "mobiledevices": [
    {
     "kind": "directory#mobiledevice",
     "resourceId": "resourceId value",
     "deviceId": "deviceId value",
     "name": [
      "Foo"
     ],
     "email": [
      "foo@example1.com"
     ],
     "model": "Nexus 6",
     "os": "Android 6.0.1",
     "type": "ANDROID",
     "status": "APPROVED",
     "hardwareId": "1234567890",
     "firstSync": "2016-02-04T12:00:00.0Z",
     "lastSync": "2016-02-04T12:00:00.0Z",
     "userAgent": "Google Apps Device Policy 6.0",
   },
    {
     "kind": "directory#mobiledevice",
     "resourceId": "resourceId value",
     "deviceId": "deviceId value",
     "name": [
      "Foo"
     ],
     "email": [
      "foo@example2.com"
     ],
     "model": "Nexus 6",
     "os": "Android 4.0.2",
     "type": "ANDROID",
     "status": "APPROVED",
     "hardwareId": "0987654321",
     "firstSync": "2016-02-04T12:00:00.0Z",
     "lastSync": "2016-02-04T12:00:00.0Z",
     "userAgent": "Google Apps Device Policy 4.2",
   },
   ]
  }

```

Where fields are missing, please confer with your Sovrn representative to agree on formatting standards.

## HTTP POST
Available for near-real time, asynchronous stream or asynchronous batch transfers. Please format inputs in the following manner:

```
{
   "kind": "directory#mobiledevices",
   "mobiledevices": [
    {
     "kind": "directory#mobiledevice",
     "resourceId": "resourceId value",
     "deviceId": "deviceId value",
     "name": [
      "Foo"
     ],
     "email": [
      "foo@example1.com"
     ],
     "model": "Nexus 6",
     "os": "Android 6.0.1",
     "type": "ANDROID",
     "status": "APPROVED",
     "hardwareId": "1234567890",
     "firstSync": "2016-02-04T12:00:00.0Z",
     "lastSync": "2016-02-04T12:00:00.0Z",
     "userAgent": "Google Apps Device Policy 6.0",
   },
    {
     "kind": "directory#mobiledevice",
     "resourceId": "resourceId value",
     "deviceId": "deviceId value",
     "name": [
      "Foo"
     ],
     "email": [
      "foo@example2.com"
     ],
     "model": "Nexus 6",
     "os": "Android 4.0.2",
     "type": "ANDROID",
     "status": "APPROVED",
     "hardwareId": "0987654321",
     "firstSync": "2016-02-04T12:00:00.0Z",
     "lastSync": "2016-02-04T12:00:00.0Z",
     "userAgent": "Google Apps Device Policy 4.2",
   },
   ]
  }

```
