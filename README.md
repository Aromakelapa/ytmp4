# Youtube Video Downloader
Convert YouTube video link into downloaded formats, and get info.

## Install
```
npm install ytmp4
```

## Changelog
- #### v1.0.2
  - Add link identifier.

## Usage
```
const ytmp4 = require('ytmp4')

ytmp4('https://www.youtube.com/watch?v=36uDReSdFDU')
  .then((res) => {
    console.log(res)
  })
  .catch((err) => {
    console.log(err)
  })
```

## Issues & Contact
- Create issue session in [Github Repo](https://github.com/Aromakelapa/ytmp4/issues)

- You can reach me on [Telegram](https://t.me/Aromakelapa)

### Thanks for using my module, Hope you forgive me if it shows an error, because I'm newbie at this :>