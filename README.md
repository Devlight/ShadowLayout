ShadowLayout
============

This library allows you to create a shadow effect for your layout based on your child.

[![DevLight](https://lh4.googleusercontent.com/-9btnRFp_eVo/V5cfwZsBpMI/AAAAAAAAC4E/s4NGoezKhpAVdVofAoez1QWpzK5Na8_cQCL0B/w147-h20-no/devlight-badge.png)](http://devlight.com.ua)

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-ShadowLayout-yellow.svg?style=flat)](http://android-arsenal.com/details/1/3524)
[![Android](https://img.shields.io/badge/platform-android-brightgreen.svg?style=flat&label=Platform)](https://github.com/DevLight-Mobile-Agency)
[![Download](https://api.bintray.com/packages/gigamole/maven/shadowlayout/images/download.svg)](https://bintray.com/gigamole/maven/shadowlayout/_latestVersion)
[![Crates.io](https://img.shields.io/crates/l/rustc-serialize.svg?maxAge=2592000&label=License)](https://github.com/DevLight-Mobile-Agency/ShadowLayout/blob/master/LICENSE.txt)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/e924623771c64e8eb4de99582d713c7f)](https://www.codacy.com/app/gigamole53/ShadowLayout?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=DevLight-Mobile-Agency/ShadowLayout&amp;utm_campaign=Badge_Grade)

![](https://lh4.googleusercontent.com/-2JB-2cEv8lk/Vx4FmHQhjOI/AAAAAAAACTA/nrRGFjcQXBsGiISYSZ5k8gUsVcRw5GSRQCL0B/w349-h552-no/sl.png)

You can check the sample app [here](https://github.com/DevLight-Mobile-Agency/ShadowLayout/tree/master/app).

Download
------------

You can download a `.aar` from GitHub's [releases page](https://github.com/DevLight-Mobile-Agency/ShadowLayout/releases).

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
compile 'com.github.devlight.shadowlayout:library:1.0.1'
```

Or Maven:

```groovy
<dependency>
    <groupId>com.github.devlight.shadowlayout</groupId>
    <artifactId>library</artifactId>
    <version>1.0.1</version>
    <type>aar</type>
</dependency>
```

Android SDK Version
===================

`ShadowLayout` requires a minimum SDK version of 11. 

Sample
======

<b>Parameters</b>

For `ShadowLayout` you can set such parameters as:
 
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
    
<b>Tips</b>

Angle can only be positive and be in range from 0 to 360 degrees.

`ShadowLayout` automatically set padding for shadow space draw.

<b>Init</b>

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

Support
=======

If you'd like to support future development and new product features, please make a payments on Gratipay and Beerpay or become a patron on Patreon.

[![Gratipay](https://img.shields.io/gratipay/user/gigamole.svg?maxAge=2592000)](https://gratipay.com/~GIGAMOLE/)
[![Beerpay](https://beerpay.io/DevLight-Mobile-Agency/ShadowLayout/badge.svg?style=flat)](https://beerpay.io/DevLight-Mobile-Agency/ShadowLayout)
[![Patreon](https://lh5.googleusercontent.com/-lXI_oKp5724/V58ysdDtxHI/AAAAAAAAC7s/g91W_YT2SM0Q_VaIhDAMmoe-jHPP3ijJwCL0B/w140-h20-no/patreon-badge.png)](https://www.patreon.com/gigamole)

Also, if you use this library in applications that are available on Google Play, please report it to us or author.

Thanks in advance.