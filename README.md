<div align="center">
  <img src="https://raw.githubusercontent.com/elwynynion/YouTube-Statistics-Tracker/main/preview.png">
</div>

<br/>
This is my simple YouTube Statistics, You can count subscribers, Views, Video. 

### How to use
- Go to [`src`](https://github.com/elwynynion/YouTube-Statistics-Tracker/tree/main/src) file then customize it whatever you want. <br/>
- Change subscribers count to views and more. **Examples** 👇 
- Subscribers Count
```javascript
subCount.innerHTML = strc(data["items"][0].statistics.subscriberCount);
```
- Views Count
```javascript
subCount.innerHTML = strc(data["items"][0].statistics.viewsCount);
```
- Views Count
```javascript
subCount.innerHTML = strc(data["items"][0].statistics.videoCount);
```


### technologies
- [YouTube API V3](https://developers.google.com/youtube/v3/getting-started)
- Odometer

<br/>
<img src="https://img.shields.io/badge/clone-148-green">
