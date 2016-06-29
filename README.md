# Build Varians Gradle

Build type variants

See build.gradle : 
```gradle
productFlavors {
        
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

}
```


You must create folder beta and paid in folder app and file you will change by build type varians must same name, see the structure :

see more : https://developer.android.com/studio/build/build-variants.html

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
