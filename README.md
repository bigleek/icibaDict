

# Youdaodict

Translates the selected text into a tooltip automatically. 

Inspired by Google Translation Tooltip. The data originally came from the honored [Youdao](http://fanyi.youdao.com/). However, due to issues with the Youdao translation API, it has now been adjusted to use the Jīnshān Cíbà (金山词霸) API for data retrieval.

## Screenshot

![Screenshot for youdaodict](http://upload-images.jianshu.io/upload_images/927981-c88125ce5a60959a.gif?imageMogr2/auto-orient/strip)

## Feature

1. Functioning on every page you visit! No mixed content blocking and CSP restriction anymore.
2. Translate words and sentences. 
3. Pronunciation support for word look-up.
4. Simple and user-friendly design.
5. Real-time multilingual online translation.

## Notes

Script is enabled by default. you can change:

```javascript
var toggle = true;
```

to:

```javascript
var toggle = false;
```

to disable this script initially.

Using <kbd>ctrl</kbd>+<kbd>alt</kbd>+<kbd>q</kbd> to enable/disable this script.

## Why

The main reason is: Google translation tooltip can't work properly in China. Additionally, the Youdao translation API also faced some issues, leading to the switch to the Jīnshān Cíbà API to ensure stable functionality.

[More info on this article(in Chinese)](http://www.jianshu.com/p/b984d149ee48)

## ChangeLog

### 20151125

- <kbd>ctrl</kbd>+<kbd>alt</kbd>+<kbd>q</kbd> to disable/enable this script.

### 20250409

- Due to issues with the Youdao translation API, the data source has been switched to the Jīnshān Cíbà API to ensure better performance and reliability.

---
