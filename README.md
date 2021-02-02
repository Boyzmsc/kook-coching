# Kook Coching


## App Info

### Version

```kotlin
compileSdkVersion 29
buildToolsVersion '30.0.2'

minSdkVersion 21
targetSdkVersion 29
```



### Execution Environment

* **Used AVD** : Pixel 3 API 29

* **Used Library**

```kotlin
// Firebase를 연동하고 사용
implementation 'com.google.firebase:firebase-firestore:21.7.1'
implementation 'com.google.firebase:firebase-storage:19.1.1'
implementation 'com.google.firebase:firebase-auth:20.0.0'
implementation 'com.google.firebase:firebase-database:19.5.1'

// Jsoup을 이용한 Crawling
implementation 'org.jsoup:jsoup:1.11.3'

// 동기, 비동기 문제를 해결하기 위해 코루틴 사용
implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.3.9'

// 게시글과 댓글 목록을 꾸미기 위해 CardView 사용
implementation 'androidx.cardview:cardview:1.0.0'

// 게시글과 댓글 목록을 보여주기 위해 RecyclerView 사용
implementation "androidx.recyclerview:recyclerview:1.1.0"
implementation "androidx.recyclerview:recyclerview-selection:1.1.0-rc03"

// 이미지 업로드를 위해 Multi Image Picker 사용
implementation 'gun0912.ted:tedbottompicker:2.0.1'
implementation 'gun0912.ted:tedpermission:2.2.3'

// Url 주소에 맞는 사진을 ImageView와 연동 후 사용
implementation 'com.github.bumptech.glide:glide:4.9.0'

// 코루틴을 쉽게 다룰 수 있는 Task.await를 사용
implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-play-services:1.2.1'
```



## Function

* App Structure (앱 구조)
* Login, Register (로그인, 회원가입)
* Home (홈)
* White Board (글쓰기)
* Board (게시판)
* Post View (글)



## Run Screen

<div style="text-align: center"><table><tr>
  <td style="text-align: center">
    <img src="https://user-images.githubusercontent.com/28584213/106650821-b4767180-65d6-11eb-9f23-8065701de29b.png" width="300"/>
</td>
  <td style="text-align: center">
    <img src="https://user-images.githubusercontent.com/28584213/106650964-dcfe6b80-65d6-11eb-985d-6ca55c0d974d.png" width="300"/>
</td>
</tr></table></div>
<div style="text-align: center"><table><tr>
  <td style="text-align: center">
<img src="https://user-images.githubusercontent.com/28584213/106651094-061efc00-65d7-11eb-8170-6b8efdd3ae26.png" width="300"/>
</td>
<td style="text-align: center">
<img src="https://user-images.githubusercontent.com/28584213/106651065-fdc6c100-65d6-11eb-8b42-d6817c301e72.png" width="300"/>
</td></tr></table></div>



