# websdkdemo

## Websdk

```https://app.siprtc.io/dist/js/websdk.js```

include above script in your html file using 

```<script src="https://app.siprtc.io/dist/js/websdk.js"></script>```

## Intialise websdk

```SiprtcWebRTCSDK``` function helps to initialise websdk and return client object. using this object you can make or answer a call. 

```var g_client = new SiprtcWebRTCSDK();```

## Callback handling

```
function callback(status, event) {
  console.log("Status : " + status)
  console.log(event)
  switch (status) {
    ...
    ...
  }
}
```


## user creation and registraion

### create new user

### register user using websdk. 

## Make new Call 

## Answer Call 

## Reject call 

## Mute call

## Un-Mute Call 

## Hangup Call 
