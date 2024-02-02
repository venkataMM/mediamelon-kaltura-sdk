# mediamelon-kaltura-sdk

## Getting Started

```javascript
var config = {
  ...
  plugins: {
    mediaMelonKPPlugin: {            
      customerId: '1128815782',
      domainName: 'DOMAIN_NAME',
      subscriberTag: 'SUBSCRIBER_TAG',
      subscriberId: 'SUBSCRIBER_ID',
      subscriberType: 'SUBSCRIBER_TYPE',
      playerName: 'PLAYER_NAME',
      playerVersion: 'PLAYER_VERSION',
      playerBrand: 'PLAYER_BRAND',
      playerModel: 'PLAYER_MODEL',
      videoAssetInfo: {
        assetId: 'ASSET_ID',
        assetName: 'ASSET_NAME',
        videoId: 'VIDEO_ID',
        seriesTitle: 'SERIES_TITLE',
        episodeNumber: 'EPISODE_NUMBER',
        season: 'SEASON',
        contentType: 'CONTENT_TYPE',
        drmProtection: 'DRM_PROTECTION',
        genre: 'GENRE',
      },            
      appName: 'APP_NAME',
      appVersion: 'APP_VERSION',
      deviceMarketingName: 'DEVICE_MARKETING_NAME',
      videoQuality: 'VIDEO_QUALITY',
      deviceId: 'DEVICE_ID',
      videoQuality: "VIDEO_QUALITY",
      customTags: {
        'KEY1' : "VALUE1",
        'KEY2' : "VALUE2"
      }
    }
  }
  ...
};

var player = KalturaPlayer.setup(config);
```