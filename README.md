<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:background="#CFD8DC"
    tools:context="com.example.android.myappportfolio.MainActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical">

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:text="My Nanodegree Apps!"
            android:textSize="28dp" />

        <Button
            android:layout_width="match_parent"
            android:layout_height="70dp"
            android:layout_marginLeft="60dp"
            android:layout_marginRight="60dp"
            android:layout_marginTop="30dp"
            android:gravity="center"
            android:text="SPORTIFY STREAMER"
            android:textSize="18sp"
            android:onClick="sportifyStreamer"/>

        <Button
            android:layout_width="match_parent"
            android:layout_height="70dp"
            android:layout_marginLeft="60dp"
            android:layout_marginRight="60dp"
            android:layout_marginTop="10dp"
            android:gravity="center"
            android:text="SCORES APP"
            android:textSize="18sp"
            android:onClick="scoresApp"/>

        <Button
            android:layout_width="match_parent"
            android:layout_height="70dp"
            android:layout_marginLeft="60dp"
            android:layout_marginRight="60dp"
            android:layout_marginTop="10dp"
            android:gravity="center"
            android:text="LIBRARY APP"
            android:textSize="18sp"
            android:onClick="libraryApp"/>

        <Button
            android:layout_width="match_parent"
            android:layout_height="70dp"
            android:layout_marginLeft="60dp"
            android:layout_marginRight="60dp"
            android:layout_marginTop="10dp"
            android:gravity="center"
            android:text="BUILD IT BIGGER"
            android:textSize="18sp"
            android:onClick="buildItBigger"/>

        <Button
            android:layout_width="match_parent"
            android:layout_height="70dp"
            android:layout_marginLeft="60dp"
            android:layout_marginRight="60dp"
            android:layout_marginTop="10dp"
            android:gravity="center"
            android:text="CAPSTONE: MY OWN APP"
            android:textSize="16sp"
            android:background="#E91E63"
            android:onClick="capstoneMyOwnApp"/>
    </LinearLayout>
</LinearLayout>
