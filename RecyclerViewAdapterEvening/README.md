# IspaceAndroidEvening

Evening Repository
------
Public repository
![TheMaster](https://github.com/Jeffreylarbiakor/IspaceAndroidEvening/blob/main/RecyclerViewAdapterEvening/Main-Activity.jpg)
![TheMaster](https://github.com/Jeffreylarbiakor/IspaceAndroidEvening/blob/main/RecyclerViewAdapterEvening/Image-Card-Layout-xml.jpg)


It uses a BitmapShader and **does not**:
* create a copy of the original bitmap
* use a clipPath (which is neither hardware accelerated nor anti-aliased)
* use setXfermode to clip the bitmap (which means drawing twice to the canvas)

Gradle
------
```
dependencies {
    ...
    implementation 'androidx.core:core-ktx:1.3.0'
    implementation 'androidx.appcompat:appcompat:1.1.0'
    implementation 'androidx.constraintlayout:constraintlayout:1.1.3'
    implementation 'com.google.android.material:material:1.4.0'
}
```

 Usage
-----
```xml
 <ImageView
            android:id="@+id/image_view_dice_one"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:contentDescription="@string/str_image_desc_one"
            android:padding="@dimen/padding_eight"
            android:src="@drawable/dice_empty"
            tools:src="@drawable/dice5" />
		
```

License
-------

    Copyright 2022 - 2023 Jeffrey Larbi-Akor

    Licensed under the ispace fundation, Version 3.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at iSpace Foundation
