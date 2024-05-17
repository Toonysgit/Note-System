---
tags:
  - resource
Area:
  - "[[Developer]]"
---
## [[My first IPFS file]]

Upload your first file in IPFS and attach the link

To complete this activity you need an APP_ID and an API_KEY. Visit **https://docs.vottun.io/start/get-your-api-key** where you will find how to get them.

Make a POST request to the **https://ipfsapi-v2.vottun.tech/ipfs/v2/file/upload** endpoint.

In our documentation you have a section which explains how to make this request. 

https://docs.vottun.io/api/ipfs#upload-file

---
POST https://ipfsapi-v2.vottun.tech/ipfs/v2/file/upload

---


curl --location 'https://ipfsapi-v2.vottun.tech/ipfs/v2/file/upload' \
--form 'filename="My first IPFS file"' \
--form 'file=@"./Pictures/ThisIsThePicture.jpg"'

{
    "hash": "https://ipfsgw.vottun.tech/ipfs/bafkreicedifa2rrqtshgm7fwkl37sccrcofiouuts3ehgyx2m6gh5byfoe"
}

{
    "hash": "https://ipfsgw.vottun.tech/ipfs/bafkreicoh3zh5q6na4azn4t6vxhtnfipxcea2dkpg7hv7kd6nfw5zljlzi"
}