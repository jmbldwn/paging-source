[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/owner/my-element)

# paging-source

This web component automatically makes paged requests for data from a URL to populate a local list.  
Parameters for how far ahead (or behind) to ensure data is retrieved cause the component to look further ahead of the 
scroll position.

The complete service URL is assumed to support two URL parameters, skip, and limit, specifying the first index
and the number of items to retrieve.

## Installation

import paging-source.html

## Usage

<paging-source 
    url="<base url>" 
    pageSize="<desired request size>"
    firstVisibleIndex="<index of first item visible in scroll window>"
    lastVisibleIndex="<index of last item visible in scroll window>"
    readAhead="<number of items beyond the last visible index to attempt to read before needed>"
    readBehind="<number of items before the first visible index to attempt to read before needed>"
    items="<array of accumulated items>"
    ></paging-source>
    
## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

2016-11-06 First Checkin

## Credits

Jim Baldwin

## License

MIT
