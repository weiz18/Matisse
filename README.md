[![](https://jitpack.io/v/lwj1994/Matisse.svg)](https://jitpack.io/#lwj1994/Matisse)

# Matisse

fork from https://github.com/zhihu/Matisse

* Order by edit time
* Separate the capture
* Fix crash when loading large image


## capture
you can directly call capture
```
Matisse.from(SampleActivity.this)
       .performCapture(new CaptureStrategy(true, "com.zhihu.matisse.sample.fileprovider", "test"), REQUEST_CODE_CHOOSE);
```

## How to

To get a Git project into your build:
### Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:
```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

### Step 2. Add the dependency
```
	dependencies {
	        implementation 'com.github.lwj1994:Matisse:Tag'
	}
```
