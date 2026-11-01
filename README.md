# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


### AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

### EQUIPMENTS REQUIRED:

Latest Version Android Studio

### ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

### PROGRAM:
### Developed by: VIMALRAJ B
### Registeration Number : 212224230304
### Date : 01.11.26

### MainActivity.java
```java
package com.example.ex1;

import android.os.Bundle;
import android.widget.Toast;


import androidx.appcompat.app.AppCompatActivity;


public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast t = Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG);
        t.show();
    }
    protected void onStart(){
        super.onStart();
        Toast t  = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
        t.show();
    }
    @Override
    protected void onPause(){
        super.onPause();
        Toast t = Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG);
        t.show();
    }
    protected void onResume(){
        super.onResume();
        Toast t = Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG);
        t.show();
    }
    protected void onStop(){
        super.onStop();
        Toast t = Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG);
        t.show();
    }
    protected void onRestart(){
        super.onRestart();
        Toast t = Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG);
        t.show();
    }
    protected void onDestroy(){
        super.onDestroy();
        Toast t = Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG);
        t.show();
    }
}
```
### activity_main.xml

```xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Welcome to Android Studio"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```

## OUTPUT

<img width="792" height="442" alt="Screenshot 2026-11-01 191616" src="https://github.com/user-attachments/assets/5ac1dba8-30d7-467f-9331-3e68d10f850d" />


<img width="792" height="439" alt="Screenshot 2026-11-01 191638" src="https://github.com/user-attachments/assets/977523b5-68c9-41ee-862e-4c9b373ffde8" />


<img width="793" height="440" alt="Screenshot 2026-11-01 191655" src="https://github.com/user-attachments/assets/d8c79abd-1804-4a7d-8a3b-e87aad973c44" />


<img width="791" height="443" alt="Screenshot 2026-11-01 191710" src="https://github.com/user-attachments/assets/95021d2d-f177-44e2-a77e-689e31924798" />



<img width="794" height="445" alt="Screenshot 2026-11-01 191725" src="https://github.com/user-attachments/assets/68ea48cb-e66a-40d5-a40f-8844ea206ade" />




## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
