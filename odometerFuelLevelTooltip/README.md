# Odometer & Fuel Level Tooltip Sample Map Add-in

_Testing the new Map API calls._

### About

This example features the following engine data in the tooltip when hovering over a vehicle on the live map or following a breadcrumb trail of a vehicle's trip history:

1) **Odometer Value** - in the user's preferred unit of measurement _(km/mi)_
2) **Fuel Level** - shown as a percentage _(this is only shown for fuel-engine, hybrid, and plug-in hybrid vehicles **and** if this measurement is supported for the vehicle)_
3) **Battery Charge Level** - shown as a percentage _(this is only shown for hybrid, plug-in hybrid, and electric vehicles **and** if this measurement is supported for the vehicle)_

Engine data is updated each time the cursor is moved.

The browser's sessionStorage is used to cache engine data to prevent unnecessary repetitive API calls. sessionStorage is temporary storage and is cleared whenever the user's session ends (i.e. the window or tab is closed).

### References
- [Map Add-in Tooltip Example][tooltip]
- [Map Add-in Events Example][events]
- [Map Add-in Request Example][request]

[tooltip]: https://git.geotab.com/map-add-ins/simple-map-add-ins/tree/master/tooltip
[events]: https://git.geotab.com/map-add-ins/simple-map-add-ins/tree/master/events
[request]: https://git.geotab.com/map-add-ins/simple-map-add-ins/tree/master/request
