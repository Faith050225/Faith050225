
<!-- activity_main.xml -->
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="16dp">

    <EditText
        android:id="@+id/ageEditText"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Enter your age"
        android:inputType="number"
        android:padding="10dp"
        android:textSize="16sp"
        android:layout_marginBottom="16dp"/>

    <Button
        android:id="@+id/matchButton"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/ageEditText"
        android:layout_marginTop="16dp"
        android:text="Match Age"/>

    <Button
        android:id="@+id/clearButton"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/matchButton"
        android:layout_marginTop="16dp"
        android:text="Clear"/>

    <TextView
        android:id="@+id/matchesTextView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_below="@id/clearButton"
        android:layout_marginTop="16dp"
        android:textSize="18sp"/>

</RelativeLayout>
