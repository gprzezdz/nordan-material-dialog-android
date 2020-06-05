# Nordan Material Dialog
[![platform](https://img.shields.io/badge/platform-Android-yellow.svg)](https://www.android.com)
[![API](https://img.shields.io/badge/API-24%2B-brightgreen.svg?style=plastic)](https://android-arsenal.com/api?level=24)
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg?style=flat-square)](https://www.apache.org/licenses/LICENSE-2.0.html)


## Dependency

Add this to your module's `build.gradle` file:

```gradle
dependencies {
	...
	implementation 'com.github.Dan629pl:NordanMaterialDialog:1.0.1'
}
```
<h2>Nordan Material Dialog</h2>

```diff
        new NordanAlertDialog.Builder(this)
                .setDialogType(DialogType.INFORMATION)
                .setAnimation(Animation.POP)
                .isCancellable(false)
                .setTitle("Information dialog")
                .setMessage("This is INFORMATION dialog type in Nordan Material Dialog library.")
                .setPositiveBtnText("OK")
                .onPositiveClicked(() -> {/* Do something here */})
                .show();
```

```diff
        new NordanAlertDialog.Builder(this)
                .setDialogType(DialogType.QUESTION)
                .setAnimation(Animation.POP)
                .isCancellable(false)
                .setTitle("Question dialog")
                .setMessage("This is QUESTION dialog type in Nordan Material Dialog library.")
                .setPositiveBtnText("Yes")
                .setNegativeBtnText("No")
                .onNegativeClicked(() -> {/* Do something here */})
                .onPositiveClicked(() -> {/* Do something here */})
                .show();
```


```
<h2>Nordan Loading Dialog</h2>

```diff
  NordanLoadingDialog.createLoadingDialog(this,"Loading...").show();
```

## Animation

## Screenshots
<img src="https://github.com/Dan629pl/NordanMaterialDialog/tree/master/img/dialogs_small.png" style="height: auto !important;width: auto !important;">

## Default dialogs types

## Donation
If this library  help you reduce time to develop, you can buy me a coffee! :) 

<a href="https://www.buymeacoffee.com/Dan629"><img src="https://www.buymeacoffee.com/assets/img/bmc-meta-new/apple-icon-72x72.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

## License

* [Apache Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

```
Copyright 2020 Daniel Owczarczyk

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

 http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.