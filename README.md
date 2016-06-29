# Build Varians Gradle

Build type variants

See build.gradle : 
```gradle
prod {
        applicationId
        "com.dizzay.buildtypes.app.main"
        versionName "1.0-main"
}

beta {
        applicationId
        "com.dizzay.buildtypes.app.beta"
        versionName "1.0-beta"
}

paid {
        applicationId
        "com.dizzay.buildtypes.app.paid"
        versionName "1.0-paid"
}
```


You must create folder beta and paid in folder app, the structure see :
```
app
---main
-------res
----------drawable
------------------myImage.png
---beta
-------res
----------drawable
------------------myImage.png
---paid
-------res
----------drawable
------------------myImage.png

```
