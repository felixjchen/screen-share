# Screen Share

- application for streaming desktop, browser window or browser tabs video and audtio to other users
- https://screenshare.netlify.app/

## Motivation

- watch movies and youtube together with friends
- show friends webpages
- use peer to peer

## Implementation

- peer to peer using [Peer.js](https://peerjs.com/) (WebRTC wrapper)
- front-end created with [IBM Carbon Design](https://www.carbondesignsystem.com/)
- screen capturing by [Screen Capture API](https://developer.mozilla.org/en-US/docs/Web/API/Screen_Capture_API)

## Todo
- new UI with React
- Share links with URL parameters
- Custom player controls
- Testing

## Takeaway

- Peer to peer applications => <ins>no need to write or host a backend</ins>
- Browsers have powerful API's ([Media Stream API](https://developer.mozilla.org/en-US/docs/Web/API/Media_Streams_API), [Screen Capture API](https://developer.mozilla.org/en-US/docs/Web/API/Screen_Capture_API), ...)
- [Netlify](https://www.netlify.com/) is great
- React may have been better choice for frontend
