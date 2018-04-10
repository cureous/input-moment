fork from https://github.com/wangzuo/input-moment
addition of a few functionalities

### Usage
``` javascript
<InputMoment
  moment={this.state.moment}
  onChange={this.handleChange}
  onSave={this.handleSave}
  minStep={1} // default
  hourStep={1} // default
  prevMonthIcon="ion-ios-arrow-left" // default
  nextMonthIcon="ion-ios-arrow-right" // default
  tab={0} // default is 0 (datepicker), set it to 1 for timepicker
/>
```

### Development
- npm install
- npm start
- http://localhost:8080

### License
ISC
