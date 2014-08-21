KIAppRate
=========

More friendly Appirator.

In your `AppDelegate:didFinishLaunchingWithOptions:`,

```objc
[KIAppRate rate:options];
```

or when you want to receive the user's selection

```objc
[KIAppRate rate:options withDelegate:delegate];
```

Options
---

`KIAppRate` also provides the builder to build an option

#### From `NSUserDefaults` (works nice with [mattt/GroundControl](https://github.com/mattt/GroundControl)!)

```
[KIAppRateOption optionWithUserDefaults:userDefaults];
```

#### On your hand

```objc
[KIAppRateOption launchCount:12];
// OR
[KIAppRateOption receiveNotification:@SomeNotificationName"];
```

