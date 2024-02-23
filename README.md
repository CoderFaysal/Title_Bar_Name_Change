# Title Bar Name Change

## In Activity
```
ActionBar actionBar = getSupportActionBar();
actionBar.setTitle("INTER_TOOLBAR_NAME");
```

## In Activity Title Bar & Back Icon
```
ActionBar actionBar = getSupportActionBar();
actionBar.setTitle("INTER_TOOLBAR_NAME");
actionBar.setDisplayShowHomeEnabled(true);
actionBar.setDisplayHomeAsUpEnabled(true);
```

Manifest
```
<activity
  android:parentActivityName="BACK_ACTIVITY_NAME">
</activity>
```



## In Fragment
```
AppCompatActivity appCompatActivity = (AppCompatActivity) getActivity();
  if (appCompatActivity !=null){
    appCompatActivity.getSupportActionBar().setTitle("INTER_TOOLBAR_NAME");
  } else {
    Toast.makeText(appCompatActivity, "Something else !!", Toast.LENGTH_SHORT).show();
  }
```

## In Fragment Title Bar & Back Icon

```
AppCompatActivity appCompatActivity = (AppCompatActivity) getActivity();
  if (appCompatActivity !=null){
    appCompatActivity.getSupportActionBar().setTitle("INTER_TOOLBAR_NAME");
    appCompatActivity.getSupportActionBar().setDisplayShowHomeEnabled(true);
    appCompatActivity.getSupportActionBar().setDisplayHomeAsUpEnabled(true);
  } else {
    Toast.makeText(appCompatActivity, "Something else !!", Toast.LENGTH_SHORT).show();
  }
```

Manifest
```
<activity
  android:parentActivityName="BACK_ACTIVITY_NAME">
</activity>
```

<img src="https://i.ibb.co/q0qWF0H/download.png"/>



<center>© All Right Reserved by Coder Faysal</center>




