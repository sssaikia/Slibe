
[![Release](https://jitpack.io/v/sssaikia/Slibe.svg?style=flat-square)](https://jitpack.io/#sssaikia/Slibe)

## Add to your project

### Step 1. Add it in your project level build.gradle
```java
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  ```
  

### Step 2. Add it in your app level build.gradle

	dependencies {
	        compile 'com.github.sssaikia:Slibe:1.0'
	}

## RecyclerItemClickListener usage

```java
someRecyclerview.addOnItemTouchListener(
                new RecyclerItemClickListener(getActivity(), new RecyclerItemClickListener.OnItemClickListener() {
                    @Override
                    public void onItemClick(View view, int position) {
                        //DO stuff
                    }
                })
        );
```

## Google map route distance

```java

String distance= getDistance(final double lat1, final double lon1, final double lat2, final double lon2);

```
## TinyDB usage
//initialize
TinyDB tinyDB = new TinyDB();

//save data
tinyDB.putString(String key, String value);

//retrive data
String str = tinyDB.getString(String key);

## License
```
MIT License

Copyright (c) 2017 Simanta Saikia

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
