
# Rapport

**Skriv din rapport här!**

_Du kan ta bort all text som finns sedan tidigare_.

I denna uppgift la jag till en vertical linear layout.
Sedan la jag till en edittext widget som man kan skriva text i 
Sedan la jag in en imageView med en bild på en hatt
Det sista jag la till var en knapp som säger till när du har tryckt på den.
Sedan så bytta jag plats på imageviewn och button 
Tillsist la jag till en margin på knappen så att det skulle se ut som att den var centrerad (använde margin för att det stod i uppgiften)

Button listener
```
        android.widget.Button button2=findViewById(R.id.button2);
        button2.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                Toast.makeText(MainActivity.this, "YOU PRESSED ME", Toast.LENGTH_SHORT).show();
            }
        });
```

vertivcal Layout
```
<LinearLayout
android:layout_width="409dp"
android:layout_height="wrap_content"
android:orientation="vertical"
tools:layout_editor_absoluteX="1dp"
tools:layout_editor_absoluteY="1dp">

        <EditText
            android:id="@+id/EditText"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"

            android:layout_weight="1"
            android:hint="Write In Me" />





        <ImageView
            android:id="@+id/imageView"
            android:layout_width="409dp"
            android:layout_height="263dp"
            android:layout_weight="1"
            app:srcCompat="@drawable/hatt" />
        <Button
            android:id="@+id/button2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginLeft="420px"
            android:layout_weight="1"
            android:text="Press Me" />
    </LinearLayout>
```
Bilder läggs i samma mapp som markdown-filen.

![](assignment3.jpeg)

