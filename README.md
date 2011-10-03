# Twilio Drupal Module

This is a simple module that interacts with the Twilio SMS api. It allows you to send SMS and accept incoming SMS from any other drupal module. It also takes care of the required welcome, help and stop.

### Using in other modules

You can respond to incoming SMS by using the twilio_respond hook in your module. All available hooks are currently called and all responses sent back as a reply. An example is available in our [summer game module](https://github.com/aadl/Summer-Game/blob/master/summergame.module#L1493)

### Twilio PHP Library

This module includes a vendored version of the Twilio php api. You can track newer versions at https://github.com/twilio/twilio-php