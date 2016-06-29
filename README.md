# BuildVariansGradle

Build type variants

See build.gradle : 
<code>

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
</code>


You must create folder beta and paid in folder app, the structure see :
<br><br>
app <br>
---- main <br>
--------- res <br>
------------- drawable <br>
---------------------- myImage.png <br>
---- beta <br>
--------- res <br>
------------- drawable <br>
---------------------- myImage.png <br>
---- paid <br>
--------- res <br>
------------- drawable <br>
---------------------- myImage.png <br>
