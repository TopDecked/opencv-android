# OpenCV for Android
[![Build Status](https://travis-ci.org/piruin/opencv-android.svg?branch=master)](https://travis-ci.org/piruin/opencv-android)
[![Download](https://api.bintray.com/packages/blazei/maven/opencv-android/images/download.svg) ](https://bintray.com/blazei/maven/opencv-android/_latestVersion)

I've took [OpenCV Library](https://github.com/opencv/opencv) and exported it as `.aar` library. Now you can easily use OpenCV in a Gradle / Android Studio project.

## Usage Maven Repo

I've uploaded the `.aar` in my maven repository. You only need to add following lines to your `build.gradle` to add the dependency:
```groovy
repositories {
    maven { url  "https://dl.bintray.com/blazei/maven" }
}

dependencies {
    implementation 'org.opencv:opencv-android:3.+'
}
```

See download badge for latest version

## License
[OpenCV license](https://github.com/opencv/opencv/blob/master/LICENSE) license

