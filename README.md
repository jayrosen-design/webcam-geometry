## a-frame webcam component

simple webcam component for [A-Frame](https://aframe.io).

_Note: Requires the latest WebRTC spec.
This can be easily shimmed with
[`webrtc-adapter`](https://github.com/webrtc/adapter)_

### API

#### Component Name

Base name is `<a-webcam>`.


```html

 <a-assets>
   <video id="element" src autoplay="true" webkit-playsinline crossorigin="anonymous"> </video>
</a-assets>

<!-- other -->

  <a-video id="screen-1" 
                    material="src:#element; shader: standard;"
                    geometry="primitive: plane; segmentsHeight: 16; segmentsWidth: 16"
                    a-webcam
                    position="0 0 0" 
                    rotation="-10 0 0"
                    width="4" height="3">
    </a-video>
```


## A-Frame
Built with [A-Frame](https://aframe.io), a web framework for building virtual reality experiences. Make WebVR with HTML and Entity-Component. Works on Vive, Rift, desktop, mobile platforms.

Click and drag on desktop. Open it on a smartphone and use the device motion sensors. Or [plug in a VR headset](https://webvr.rocks)!
