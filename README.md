# BRICS-TRAINING
  <?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:background="@drawable/imgbit"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:id="@+id/imageView3"
        android:layout_width="391dp"
        android:layout_height="69dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0"
        app:srcCompat="@drawable/headermybit" />

    <Button
        android:id="@+id/button"
        android:layout_width="94dp"
        android:layout_height="50dp"
        android:layout_marginStart="4dp"
        android:text="HOME"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.129"
        android:layout_marginLeft="4dp" />


    <Button
        android:id="@+id/button2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="5dp"
        android:text="ABOUT"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="@+id/button4"
        app:layout_constraintHorizontal_bias="0.336"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.125" />

    <Button
        android:id="@+id/button3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="LIFE "
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="@+id/button4"
        app:layout_constraintHorizontal_bias="0.641"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.131" />

    <Button
        android:id="@+id/button4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="1dp"
        android:text="CONTACT"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.13" />

    <ImageView
        android:id="@+id/imageView6"
        android:layout_width="382dp"
        android:layout_height="617dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.137"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView3"
        app:layout_constraintVertical_bias="0.466"
        app:srcCompat="@drawable/homepage" />

    <Button
        android:id="@+id/button7"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="120dp"
        android:layout_marginEnd="119dp"
        android:text="STUDENT LOGIN"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/imageView3"
        app:layout_constraintVertical_bias="0.905"
        android:layout_marginLeft="120dp"
        android:layout_marginRight="119dp" />


</androidx.constraintlayout.widget.ConstraintLayout>
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/imgbit"
    tools:context=".MainActivity2">

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="186dp"
        android:layout_height="149dp"
        android:layout_marginStart="90dp"
        android:layout_marginEnd="113dp"
        android:layout_marginBottom="111dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.161"
        app:srcCompat="@drawable/unnamed" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="@font/joti_one"
        android:text="WELCOME TO BIT"
        android:textColor="#DD8C14"
        android:textSize="20sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.452" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="273dp"
        android:layout_height="45dp"
        android:layout_marginTop="40dp"
        android:layout_marginEnd="36dp"
        android:fontFamily="@font/carter_one"
        android:text="EXPLORE THE JOY OF LEARNING"
        android:textColor="#03A9F4"
        android:textSize="16sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.554" />

    <Button
        android:id="@+id/button6"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="128dp"
        android:layout_marginTop="80dp"
        android:layout_marginEnd="133dp"
        android:backgroundTint="#4C48D3"
        android:text="LET'S GO"
        android:textColorHighlight="#FFFFFF"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.759"
        app:rippleColor="#670A0A"
        app:strokeColor="#FFFFFF" />

</androidx.constraintlayout.widget.ConstraintLayout>
 xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/zxdf"
    tools:context=".MainActivity3">

    <ImageView
        android:id="@+id/imageView2"
        android:layout_width="297dp"
        android:layout_height="188dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.062"
        app:srcCompat="@drawable/address" />

    <ImageView
        android:id="@+id/imageView5"
        android:layout_width="302dp"
        android:layout_height="149dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.486"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.45"
        app:srcCompat="@drawable/phone" />

    <ImageView
        android:id="@+id/imageView7"
        android:layout_width="298dp"
        android:layout_height="143dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.821"
        app:srcCompat="@drawable/email" />

</androidx.constraintlayout.widget.ConstraintLayout>
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android" android:orientation="vertical" android:layout_width="fill_parent" android:layout_height="fill_parent">
    <TextView android:layout_width="fill_parent" android:layout_height="wrap_content" />
    <Button android:layout_height="wrap_content" android:clickable="true" android:autoLink="web" android:cursorVisible="true" android:layout_width="match_parent" android:id="@+id/button_so" android:text="WIKIBITSATHY" android:linksClickable="true" android:onClick="goToSo"></Button>
    <Button android:layout_height="wrap_content" android:layout_width="match_parent" android:text="Moodle" android:autoLink="web" android:clickable="true" android:id="@+id/button_sa" android:onClick="goToSu"></Button>
    <Button android:layout_height="wrap_content" android:layout_width="match_parent" android:text="Moodle" android:autoLink="web" android:clickable="true" android:id="@+id/button_sm" android:onClick="goToSu"></Button>


    <Button
        android:id="@+id/button_su"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:autoLink="web"
        android:clickable="true"
        android:onClick="goToSu"
        android:text="Moodle"></Button>
</LinearLayout>
package com.example.myapplication;



import android.os.Bundle;

import androidx.appcompat.app.AppCompatActivity;

public class MainActivity3 extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main3);

    }
}
package com.example.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

public class MainActivity4 extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main4);
    }
}
package com.example.myapplication;

import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;

import androidx.appcompat.app.AppCompatActivity;

public class MainActivity6 extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main6);
        Button loginButton = findViewById(R.id.loginButton);
        loginButton.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                Intent loginIntent = new Intent(MainActivity6.this, MainActivity7.class);
                startActivity(loginIntent);
            }
        });
    }
}
package com.example.myapplication;

import android.app.Activity;
import android.content.Intent;
import android.net.Uri;
import android.os.Bundle;
import android.view.View;

public class MainActivity7 extends Activity {

    @Override
    public void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main7);
    }

    public void goToSo (View view) {
        goToUrl ( "https://wiki.bitsathy.ac.in/");
    }

    public void goToSu (View view) {
        goToUrl ( "https://moodle.bitsathy.ac.in/");
    }

    public void goToSa (View view) {
        goToUrl ( "https://camps.bitsathy.ac.in/");
    }
    public void goToSm (View view) {
        goToUrl ( "https://dashboard.bitsathy.ac.in/");
    }




    private void goToUrl (String url) {
        Uri uriUrl = Uri.parse(url);
        Intent launchBrowser = new Intent(Intent.ACTION_VIEW, uriUrl);
        startActivity(launchBrowser);
    }

}
