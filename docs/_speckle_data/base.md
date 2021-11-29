---
title: Basic Speckle Objects
---

# JSON format

  When a Speckle object is serialized (converted to JSON), the properties specified in the class definition become top-level name of the JSON object. Any user data attached to the object is stored under a top-level `properties` name.

  In the example below, the names `type`, `hash`, `applicationId` are defined as properties in the SpeckleObject class; the name `values` is defined in the SpeckleCoreGeometry Point class; and the `properties` name stores user data that was assigned to the object by a user.

  ```
  {
  "type": "Point",
  "value": [
    0.0,
    0.0,
    0.0
  ],
  "hash": "bf75e42a82d6e8d43023375cc7d2b7fc",
  "applicationId": "gh/bf75e42a82d6e8d43023375cc7d2b7fc",
  "properties": {
    "attractive-force": 192,
    "mass": 42
  }
}
```
## Custom Speckle Objects vs User data

The grasshopper client allows you to either add user data to a SpeckleObject, or create a custom Speckle Object. Despite the difference in the names, both of these will put all the data that you specify under the  `properties` name.