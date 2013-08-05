Bootstrap-pagination
====================
Bootstrap-pagination improves on https://code.google.com/p/one-simple-table-paging/ for those who want front-end pagination that fits with the Bootstrap aesthetic.

Demo: http://www.samjhill.com/projects/bootstrap-pagination/

Usage
-----
Include Bootstrap, jQuery, Bootstrap-Pagination, and Javascript.

``` html
<meta http-equiv="X-UA-Compatible" content="IE=9; IE=8;" />
<link rel="stylesheet" href="http://netdna.bootstrapcdn.com/twitter-bootstrap/2.3.2/css/bootstrap-combined.min.css">
    
<script src="http://codeorigin.jquery.com/jquery-1.10.2.min.js"></script>
<script src="http://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/2.3.1/js/bootstrap.min.js"></script>
<script type="text/javascript" src="js/bootstrap-pagination.js"></script>
```

Call the plugin by giving your table the ID main-table, then include this line in your javascript.
``` javascript
<script type="text/javascript">
     $('#main-table').bootstrapPagination({rowsPerPage: 5});
</script>
```