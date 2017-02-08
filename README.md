PhoneEditText
-------------
special phone edittext library, all international phone codes came from ![https://countrycode.org/](https://countrycode.org/)


Usage
-----
1- first of all, add gradle dependencie
```gradle

allprojects {
    repositories {
        jcenter()
        maven { url "https://jitpack.io" }
    }
}
        .
        .
        .


dependencies {
    compile 'com.github.leoxnidas:phoneedittext:phoneedittext:1.0'
}
```

2- add PhoneEditText to your layout
```xml
<com.github.leoxnidas.phoneedittext.PhoneEditText
        app:code="USA"
        android:layout_width="200dp"
        android:layout_height="wrap_content"/>
```

3- enjoy =P

![image](./img/phone.png)


License
--------
![LICENSE](./LICENSE.md)