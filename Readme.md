# FixedHeader for DataTables with styling for [Bootstrap4](https://getbootstrap.com/docs/4.6/getting-started/introduction/)

This is the distribution package for the [FixedHeader extension](https://datatables.net/extensions/fixedheader) for [DataTables](https://datatables.net/) with styling for [Bootstrap4](https://getbootstrap.com/docs/4.6/getting-started/introduction/).

When displaying large amounts of data in a table, it can often be useful for the end user to have the column titles always visible. This is particularly true if using DataTables with pagination disabled, or the display length is set to a high value. The FixedHeader extension provides this ability.


## Installation

### Browser

To use DataTables with a simple `<script>` tag, rather than using this package, it is recommended that you use the [DataTables download builder](//datatables.net/download) which can create CDN or locally hosted packages for you, will all dependencies satisfied.

### npm

For installation via npm, yarn and other similar package managers, install this package with your package manager - e.g.:

```
npm install datatables.net-bs4
npm install datatables.net-fixedheader-bs4
```

Then, to load and initialise the software in your code use:

```
import DataTable from 'datatables.net-bs4';
import 'datatables.net-fixedheader-bs4'

new DataTable('#myTable', {
    // initialisation options
});
```


## Documentation

Full documentation and examples for FixedHeader can be found [on the DataTables website](https://datatables.net/extensions/fixedheader).


## Bug / Support

Support for DataTables is available through the [DataTables forums](//datatables.net/forums) and [commercial support options](//datatables.net/support) are available.

### Contributing

If you are thinking of contributing code to DataTables, first of all, thank you! All fixes, patches and enhancements to DataTables are very warmly welcomed. This repository is a distribution repo, so patches and issues sent to this repo will not be accepted. Instead, please direct pull requests to the [DataTables/FixedHeader](http://github.com/DataTables/FixedHeader). For issues / bugs, please direct your questions to the [DataTables forums](//datatables.net/forums).


## License

This software is released under the [MIT license](//datatables.net/license). You are free to use, modify and distribute this software, but all copyright information must remain.

