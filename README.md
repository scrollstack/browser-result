# Browser Detector

Mainly there are two objects that are used for browser detection which is as follows:

* navigator.appName - purpose is to determine the web browser
* navigator.appVersion - purpose is to determine the version of the web browser.


## Information

<table>
<tr>
<td>Package</td><td>browser-result</td>
</tr>
<tr>
<td>Description</td>
<td>Get browser info</td>
</tr>
</table>

## Usage

#### Install

```sh
$ npm install --save-dev browser-result
```

## Example

```js
import browser from 'browser-result'

console.log(browser);
// {android: false chrome: true chrome_version: 97 gecko: false gecko_version: false ie: false ie_version: null ios: false mac: true safari: false webkit: true webkit_version: 537} 
```

#### PRs welcome for additional features