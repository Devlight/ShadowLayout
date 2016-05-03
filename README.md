
[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-ShadowLayout-blue.svg?style=flat-square)](http://android-arsenal.com/details/1/3524)

ShadowLayout
===================

This library allows you to create a shadow effect for your layout based on your child.

![](https://lh4.googleusercontent.com/-2JB-2cEv8lk/Vx4FmHQhjOI/AAAAAAAACTA/nrRGFjcQXBsGiISYSZ5k8gUsVcRw5GSRQCL0B/w349-h552-no/sl.png)

U can check the sample app [here](https://github.com/DevLight-Mobile-Agency/ShadowLayout/tree/master/app).

Download
------------

You can download a .aar` from GitHub's [releases page](https://github.com/DevLight-Mobile-Agency/ShadowLayout/releases).

Or use Gradle jCenter:

```groovy
dependencies {
    repositories {
        mavenCentral()
        maven {
            url  'http://dl.bintray.com/gigamole/maven/'
        }
    }
    compile 'com.github.devlight.shadowlayout:library:+'
}
```

Or Gradle Maven Central:

```groovy
compile 'com.github.devlight.shadowlayout:library:1.0.0'
```

Or Maven:

```groovy
<dependency>
    <groupId>com.github.devlight.shadowlayout</groupId>
    <artifactId>library</artifactId>
    <version>1.0.0</version>
    <type>aar</type>
</dependency>
```

Android SDK Version
=========

ShadowLayout requires a minimum sdk version of 11. 

Sample
========

For ShadowLayout you can set such parameters as:
 
 - shadowed:
    
    allows you to handle shadow visibility.
    
 - shadow distance:
     
    allows you to set distance of shadow.    

 - shadow angle:
    
    allows you to set shadow angle.
    
 - shadow radius:
     
    allows you to set shadow radius.
     
 - shadow color:
     
    allows you to set shadow color.

Angle can only be positive and be in range from 0 to 360 degrees.

ShadowLayout automatically set padding for shadow space draw.

Check out in code init:

```java
final ShadowLayout shadowLayout = (ShadowLayout) findViewById(R.id.sl);
shadowLayout.setIsShadowed(true);
shadowLayout.setShadowAngle(45);
shadowLayout.setShadowRadius(20);
shadowLayout.setShadowDistance(30);
shadowLayout.setShadowColor(Color.DKGRAY);
```
            
Other methods check out in sample.

And XML init:

```xml
<com.gigamole.samples.ShadowLayout
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:sl_shadowed="true"
    app:sl_shadow_angle="45"
    app:sl_shadow_radius="20dp"
    app:sl_shadow_distance="30dp"
    app:sl_shadow_color="#000">
    
    <!-- Set your child`s-->
    
</com.gigamole.samples.ShadowLayout>
```

Getting Help
======

To report a specific problem or feature request, [open a new issue on Github](https://github.com/DevLight-Mobile-Agency/ShadowLayout/issues/new).

License
======

Apache 2.0 and MIT. See [LICENSE](https://github.com/DevLight-Mobile-Agency/ShadowLayout/blob/master/LICENSE.txt) file for details.


Author
=======

Made in [DevLight Mobile Agency](https://github.com/DevLight-Mobile-Agency)

Created by [Basil Miller](https://github.com/GIGAMOLE) - [@gigamole](mailto:gigamole53@gmail.com)
