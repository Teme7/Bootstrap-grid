# Bootstrap-grid

A CSS framework, Bootstrap layout is basically made up of rows and columns.

With the exception of the nav bar, all contents, i.e. the rows and columns are contained within the container div.

A maximum of 12 columns are nested in each row. A span (# of columns out of the 12) determines the width of each column.

A column can also have rows nested within it so long as that column itself is also contained in a row above it.

In the bootstrap layout heirarchy/sequence, a column width declaration such as div class="col-md-6" is nested within a row (div class="row"), which itself is contained within a container (div class="container"). Contents displayed on the web page know how much space to take only after such specification.

    <div class="container">
        <div class="row">
            <div class="col-md-6"
  
Responsivness to screen sizes are specified in the Bootstrap classes as such:
 xs (mobile phones), sm (tablets), md (laptop), and lg (larger than laptop).
