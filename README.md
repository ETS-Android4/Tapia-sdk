# Tapia-sdk

SDKはTapiaで開発するためのものです。<br />
SDK for developing on Tapia. <br /><br />

## Installation

1.  git cloneするか、zipをダウンロードする。そうするとAndroid Studioでtapia-sampleを開く。<br /><br />
    Download or clone the project and then open the sample app (tapia-sample) in Android Studio. 

2.  `gradle.properties`に追加することで<br />
    Tapiaのライブラリーを使える。<br /><br />
    Add the following to your `gradle.properties`<br />
    This will add the Tapia library to your project. 

    ```
    sdk_username=yourUserName
    sdk_password=yourPassword
    ```

3.  声のデーターベースファイルも必要である。<br />
    プロジェクトからtapia-sample/app/micro_h16フォルダをコピーする。<br />
    あなたのTapiaかAndroidデバイスに次のように追加する。<br />
    そうするとTapiaのText-To-Speechを使える。<br /><br />
    You will also need to add the voice database file<br />
    You can copy the entire folder from tapia-sample/app/micro_h16<br />
    to the following folder on your Tapia or android device<br />
    to enable Tapia's Text to Speech. 　　
  
    ```
    /USB storage/micro_h16/tts_single_db_XXXXX.vtdb
    ```
    
4.  アカウントをまだ作成していない場合は、以下のurlで作成する。<br /><br />
    If you don't have an account yet, please create one at :<br />
    https://tos.mjirobotics.co.jp/
