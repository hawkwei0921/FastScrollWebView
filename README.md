# Description:
  Scroll WebView quickly

## A. Publish to GitHub:
 1. Share project to GitHub
 2. Add a TAG at Release

## B. Publish to JitPack:
 1. Go to https://jitpack.io/
 2. Paste <Account>/<Repository> and press the look up button
    ex: hawkwei0921/FastScrollWebView

## C. Gitpack Usage:
 1. Add it in .\build.gradle
```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
 2. Add it in .\app\build.gradle 
```
	dependencies {
	        compile 'com.github.hawkwei0921:FastScrollWebView:v1.0.0'
	}
```
