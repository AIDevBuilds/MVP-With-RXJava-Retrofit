# MVP with RxJava and Retrofit (Android)

Android sample of the Model-View-Presenter pattern with RxJava 2 and Retrofit.

This is an older sample kept for reference. It is not actively maintained.

## What it shows

- `BasePresenter` and `BaseView`, and a splash screen built as `SplashFragment`, `SplashPresenter` and `SplashView`
- A `NetworkModule` and `PostApi` for `GET /posts` on [JSONPlaceholder](https://jsonplaceholder.typicode.com)

## Stack

Java, RxJava 2.1.9, RxAndroid 2.0.2, Retrofit 2.3.0 with the Moshi converter, `minSdkVersion 15`, `compileSdkVersion 27`.

## Run

Open the project in Android Studio and run the `app` module. It uses an older Android Gradle plugin (3.1.x) and `compileSdkVersion 27`, so Android Studio may ask you to update the Gradle wrapper and plugin.

## License

MIT. See [LICENSE](LICENSE).
