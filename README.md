# TextInputLayoutStyle

![](https://github.com/gzeinnumer/TextInputLayoutStyle/blob/master/preview/preview_1.png)

- Type 1
```xml
<com.google.android.material.textfield.TextInputLayout
    style="@style/MyTextInputLayoutOutlinedBox.Spesial"
    android:layout_margin="@dimen/def_margin"
    android:layout_weight="1"
    android:hint="Label"
    android:paddingTop="0dp">

    <com.google.android.material.textfield.TextInputEditText
    style="@style/MyTextInputEditText.Spesial" />

</com.google.android.material.textfield.TextInputLayout>
```

- Type 2
```xml
<com.google.android.material.textfield.TextInputLayout
    style="@style/MyTextInputLayoutOutlinedBox.Spesial.V2"
    android:layout_margin="@dimen/def_margin"
    android:layout_weight="1"
    android:hint="Label"
    app:endIconMode="clear_text">

    <com.google.android.material.textfield.TextInputEditText
    style="@style/MyTextInputEditText.Spesial.V2" />

</com.google.android.material.textfield.TextInputLayout>
```

- Type 3
```xml
<com.google.android.material.textfield.TextInputLayout
    style="@style/MyTextInputLayoutOutlinedBox.Spesial.V3"
    android:layout_margin="@dimen/def_margin"
    android:layout_weight="1"
    android:hint="Label"
    app:endIconMode="clear_text">

    <com.google.android.material.textfield.TextInputEditText
    style="@style/MyTextInputEditText.Spesial.V3" />

</com.google.android.material.textfield.TextInputLayout>
```

Step 1. Add this additional file and code

- res
  - color
    - [input_text_no_underline.xml](https://github.com/gzeinnumer/TextInputLayoutStyle/blob/master/app/src/main/res/color/input_text_no_underline.xml)
    - [mygzn_indicator_text_color.xml](https://github.com/gzeinnumer/TextInputLayoutStyle/blob/master/app/src/main/res/color/mygzn_indicator_text_color.xml)
  - drawable
    - [mygzn_text_input_edittext.xml](https://github.com/gzeinnumer/TextInputLayoutStyle/blob/master/app/src/main/res/drawable/mygzn_text_input_edittext.xml)
    - [mygzn_text_input_edittext_3d_shadow.xml](https://github.com/gzeinnumer/TextInputLayoutStyle/blob/master/app/src/main/res/drawable/mygzn_text_input_edittext_3d_shadow.xml)
    - [mygzn_text_input_edittext_white.xml](https://github.com/gzeinnumer/TextInputLayoutStyle/blob/master/app/src/main/res/drawable/mygzn_text_input_edittext_white.xml)
    - [mygzn_text_input_layout.xml](https://github.com/gzeinnumer/TextInputLayoutStyle/blob/master/app/src/main/res/drawable/mygzn_text_input_layout.xml)
  - values
    - [colors.xml](https://github.com/gzeinnumer/TextInputLayoutStyle/blob/master/app/src/main/res/values/colors.xml)
    - [dimens.xml](https://github.com/gzeinnumer/TextInputLayoutStyle/blob/master/app/src/main/res/values/dimens.xml)
    - [strings.xml](https://github.com/gzeinnumer/TextInputLayoutStyle/blob/master/app/src/main/res/values/strings.xml)
    - [themes.xml](https://github.com/gzeinnumer/TextInputLayoutStyle/blob/master/app/src/main/res/values/themes.xml)

Step 2. Or add this **implementation** to depedencies to skip **Step 1**

```gradle
//maven { url 'https://jitpack.io' }
implementation 'com.github.gzeinnumer:SimpleMaterialStyle:version'
```

More simple with [SimpleMaterialStyle](https://github.com/gzeinnumer/SimpleMaterialStyle)

---

```
Copyright 2021 M. Fadli Zein
```