<br/>
<p align="center">
  <a href="http://devlight.io">
      <img src ="https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScLVBKck51Z1Rzb0E" alt="Devlight"/>
  </a>
</p>
<br/>

ShadowLayout
============

This library allows you to create a shadow effect for your layout based on your child.

[![Android Arsenal](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScd2otYkEydkdjNUk)](http://android-arsenal.com/details/1/3524)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Android](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wSccEZaclNGN0R5OWc)](https://github.com/DevLight-Mobile-Agency)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Download](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScLXZTaGprRXZXeEU)](https://bintray.com/gigamole/maven/shadowlayout/_latestVersion)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![License](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScU0tmeFpGMHVWNWs)](https://github.com/DevLight-Mobile-Agency/ShadowLayout/blob/master/LICENSE.txt)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Codacy](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScSHhmckZyeGJDcXc)](https://www.codacy.com/app/gigamole53/ShadowLayout?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=DevLight-Mobile-Agency/ShadowLayout&amp;utm_campaign=Badge_Grade)

<br/>

<p align="center">
    <img src="https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScT3JXY2t5TzhkTDg"/>
</p>

You can check the sample app [here](https://github.com/DevLight-Mobile-Agency/ShadowLayout/tree/master/app).

Warn
====
```
This library is not more supported. 
If you want to add new feature or fix a bug, grab source code and do it. 
If you think your fix or feature would be useful to other developers, 
I can add link of your repository to this README file. 
Thank you for using our libraries.
```

Download
========

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
compile 'com.github.devlight.shadowlayout:library:1.0.2'
```

Or Maven:

```groovy
<dependency>
    <groupId>com.github.devlight.shadowlayout</groupId>
    <artifactId>library</artifactId>
    <version>1.0.2</version>
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
<com.gigamole.library.ShadowLayout
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:sl_shadowed="true"
    app:sl_shadow_angle="45"
    app:sl_shadow_radius="20dp"
    app:sl_shadow_distance="30dp"
    app:sl_shadow_color="#000">
    
    <!-- Set your child`s-->
    
</com.gigamole.library.ShadowLayout>
```

Getting Help
============

To report a specific problem or feature request, [open a new issue on Github](https://github.com/DevLight-Mobile-Agency/ShadowLayout/issues/new).

Author
======

Created by [Basil Miller](https://github.com/GIGAMOLE) - [@gigamole](mailto:gigamole53@gmail.com)

Company
=======

[![Facebook](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScaGhGVFNKU0VxMnc)](https://www.facebook.com/devlightagency)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![Twitter](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wScZ1ExQWh5cHF5cVE)](https://twitter.com/DevLightIO)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![LinkedIn](https://drive.google.com/uc?export=download&id=0BxPO_UeS7wSccGZINzEycE1nVFE)](https://www.linkedin.com/company/devlight)

[Here](https://github.com/DevLight-Mobile-Agency) you can see open source work developed by Devlight LLC.  
This and another works is an exclusive property of Devlight LLC. 

If you want to use this library in applications which will be available on Google Play, please report us or author of the library about it.

Whether you're searching for a new partner or trusted team for creating your new great product we are always ready to start work with you. 

You can contact us: info@devlight.io or opensource@devlight.io.  
Thanks in advance.

Devlight LLC, 2016  
[devlight.io](http://devlight.io) 
