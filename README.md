# SwipMenuLayout

SwipMenuLayout支持任何View的侧滑

## 使用方法：

1、引用

在Project的gradle中加入：
```groovy
    allprojects {
        repositories {
            ...
            maven { url 'https://jitpack.io' }
        }
    }
```
在Module的gradle中加入：
```groovy
    dependencies {
        compile 'com.github.like5188:SwipMenuLayout:1.0.0'
    }
```
2、使用
```java
    <com.like.swipmenulayout.SwipeMenuLayout xmlns:swipe="http://schemas.android.com/apk/res-auto"
        android:id="@+id/swipe_layout"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:background="?selectableItemBackground"
        android:clickable="true"
        swipe:contentViewId="@+id/content_view"
        swipe:leftViewId="@+id/left_view"
        swipe:rightViewId="@+id/right_view">
        
        您的视图......
        
    </com.like.swipmenulayout.SwipeMenuLayout>
```
# License
```xml
    Copyright 2017 like5188
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
    http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
