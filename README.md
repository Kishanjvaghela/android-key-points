# android-key-points
Android's basic key points while developing apps.

#### ListView
* Dont include ListView in ScrollView.
* ListView must be match_parent.

#### List
* Use [MultiComparator](./code/MultiComparator.java) in [Collections.sort()](https://docs.oracle.com/javase/7/docs/api/java/util/Collections.html#sort(java.util.List,%20java.util.Comparator)) for multiple comparision.

#### Image
* For [EXIF](https://developer.android.com/reference/android/media/ExifInterface.html) and rotation support use [Glide](https://github.com/bumptech/glide) instead of [Picasso](https://github.com/square/picasso). [[Source](https://stackoverflow.com/a/38775606/3758898)]


