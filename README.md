# jQuery Countdown

jQuery Countdown is a countdown library with an amazing animation. Take a look
at the [demonstration] https://perivar.github.io/

Now you can download the PSD file
[here] https://github.com/Reflejo/jquery-countdown/blob/master/img/digits.psd

### Basic usage:

```javascript
  $('#counter').countdown({startTime: "01:12:32:55"});
```

### Complete usage:

```javascript
  $('#counter').countdown({
    stepTime: 60,
    format: 'hh:mm:ss',
    startTime: "12:32:55",
    digitImages: 6,
    digitWidth: 53,
    digitHeight: 77,
    timerEnd: function() { alert('end!!'); },
    image: "digits.png"
  });
```

### Added continuous countdown

```javascript
  $('#counter').countdown({
    format: 'sss',
    startTime: "120",
    continuous: true,
    timerEnd: function() { alert('end!!'); },
    image: "digits.png"
  });
```

### Countdown to a Date

Relative to current hour:

```javascript
  $('#counter').countdown({
    image: "digits.png",
    format: "mm:ss",
    endTime: '50:00'
  });
```

An absolute date:


```javascript
  $('#counter').countdown({
    image: "digits.png",
    format: "mm:ss",
    endTime: new Date('07/16/13 05:00:00')
  });
```

### Developers

- Martín Conte Mac Donell - <Reflejo@gmail.com> - [@fz](https://twitter.com/fz)
- [Matt Neary](http://mattneary.com) - <neary.matt@gmail.com>
- Enhanced to have more than one counter working on the same page by Per Ivar Nerseth
https://github.com/perivar/jquery-countdown

### Demo

Look at the [demo] https://perivar.github.io/
 