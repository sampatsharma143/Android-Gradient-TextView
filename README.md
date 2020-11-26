# Android-Gradient-TextView


* Step 1. Add the JitPack repository to your build file
* Add it in your root build.gradle at the end of repositories:
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  ```
  
  *Step 2. Add the dependency
  
  
  ```
  dependencies {
	        implementation 'com.github.sampatsharma143:Android-Gradient-TextView:1.0.0'
	}
  
  ```
  
  *Step 3. Create an color array
  
  ```
    <array name="textview_colors">
        <item>@color/color1</item>
        <item>@color/color2</item>
        <item>@color/color3</item>
    </array>

  ```
  
  *Step 4. add a GradientTextView to your layout file 
  
  ```
  
    <com.sampatsharma.GradientTextView.GradientTextView
        android:layout_width="match_parent"
        android:text="Hello World"
        android:textSize="30sp"
        app:color_list="@array/textview_colors"
        app:gradient_direction="right"
        android:layout_height="wrap_content"
        tools:ignore="MissingConstraints" />
  
  ```
  
  That's it!
  
  
  
