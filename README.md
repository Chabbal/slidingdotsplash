
# Add slidingdotsplash to your project

compile 'com.chabbal:slidingdotsplash:1.0.1'

       <com.chabbal.slidingdotsplash.SlidingSplashView
        android:id="@+id/splash"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:imageResources="@array/img_id_arr"/>
        
Create an integer-array in strings.xml

    <integer-array name="img_id_arr">
        <item>@drawable/img1</item>
        <item>@drawable/img2</item>
        <item>@drawable/img3</item>
        <item>@drawable/img4</item>
    </integer-array>
