# Bootstrap-grid

Bootstrap layout is basically made up of rows and columns.

With the exception of the nav bar, all contents, i.e. the rows and columns are contained within the container div.

Each column is a div, and that div is enclosed in a row div. There are a maximum of 12 columns nested within each row. A span (# of columns out of the 12) determines the width of each column.

A column can also have rows nested within it so long as that column itself is also contained in a row above it.

In the bootstrap layout heirarchy/sequence, a column width declaration is nested within a row, which itself is contained within a container. Contents displayed on the web page know how much space to take only after such specification:

    <div class="container">
        <div class="row">
            <div class="col-md-6"
  
Responsivness to different screen sizes are specified in the Bootstrap classes as such:
 xs (mobile phones), sm (tablets), md (laptops), and lg (larger than laptop).
