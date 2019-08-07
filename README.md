# BagsVsAirlines
Information about [bagsvsairlines.com](https://bagsvsairlines.com)

If you'd like to make a correction or want information added, please open an issue using the `Issues` tab above. This will require a free GitHub account to proceed.

## About

Bags vs. Airlines is a simple site that exists to provide information about what bags fit on a given airline. Over time the databas will grow to include a larger quanity of both bags and airlines. The user interface will change once the dropdown lists become too large to comfortably scoll through.

There are no tracking scripts or cookies used by the site. This increases privacy and speeds loading times. Advertisments may appear in the future, because infrastructure costs money. In that case, they will be minimally intrusive and will not have trackers or cookies.

## Future plans

A wish list of things that might be added to the site (also see the [issues board](https://github.com/bagsvsairlines/BagsVsAirlines/labels/enhancement)):

- adding personal item wieght for the airlines that be like that
- an "official" tag added to items which indicates the dimensions were provided by the bag maker or airline, and not just copied from their website
- minimal advertising (promo links on a bag or brand, search specific ads based on comparable dimensions/volumes of bags, etc)
- infrastructure expansion based on traffic

## Contact

Please [open an issue here](https://github.com/bagsvsairlines/BagsVsAirlines/issues) to get in touch. 

### Notes

#### Measuments
- bags are stored so that the longest measurement is the height, for consistency. This also means that messengers/briefcase style bags will be rotated 90˚ from their published dimensions.
- dimensional measures are stored in millimeters
- bag volume is stored as litres, rounded down (because black magic is more predictable that bag volumes)
- bag wieght is stored as grams

#### Rounding

- Metric to imperial measurements are done by multiplying mm by 0.03937008 to get inches.
- Both centimeters and inches as rounded to the nearest half unit.
