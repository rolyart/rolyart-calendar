# rolyart-calendar
Simple pure JS calendar. [Demo](http://apps.rolyart.ro/rolyart-calendar)
## Install

1. Add `rolyart-calendar.js`
2. Add `style.css`
3. Add calendar container `<div id="myCalendar"></div>`
4. Init calendar:
`let config = {
    container: 'calendar',
    months: ["January", "February", "March", "Aprile", "May", "June", "July", "August", "September", "Octomber", "November", "December"],
    weekDays: ["S", "M", "T", "W", "T", "F", "S"],
}
let calendar = new RolyartCalendar(config)`
