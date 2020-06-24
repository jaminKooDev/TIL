Menu
=========
## 1. 기본 타이틀로 추가하는 방법
```diff
<?xml version="1.0" encoding="utf-8"?>
<menu xmlns:android="http://schemas.android.com/apk/res/android">
+    <item android:id="@+id/MenuID" android:title="Menu Title"></item>
</menu>
```

## 2. 아이콘으로 추가하는 방법
```diff
<?xml version="1.0" encoding="utf-8"?>
<menu xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto">
+    <item android:id="@+id/item_main_zommin" android:title="Font Size Up" app:showAsAction="always" android:icon="@drawable/baseline_zoom_in_black_18dp"></item>
+    <item android:id="@+id/item_main_zoomout" android:title="Font Size Down" app:showAsAction="always" android:icon="@drawable/baseline_zoom_out_black_18dp"></item>
</menu>
```
