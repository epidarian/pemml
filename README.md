# pemml
Rules specifications for various formatting and extensibility upgrades for the markdown syntax (tentantively named: Pagination Enabled Markdown-style Markup Language). Designed for publishing rather than frontloading html content

Folders will attempt to include various (incomplete) implementations of pemml.

==========

1. Thou shalt use the default github markdown syntax first and foremost.

  1a. Thou shalt use the pagination or print CSS or SCSS schematic to define your layout's physical space. Or don't I don't care.

2. Thou shalt indicate content pages with =( )= and use the parenthesis to indicate what kind of content will live there. 
  e.g.: =(?csv Roles)= should indicate a page titled "Roles" where the content is a table created from csv data. A page break will be automatically inserted before the next =( )=

  2a. When a data type is not defined the text inside that page shall be considered prose and therefore markdown rules shall apply.

  2b. When the data type is # the title will be used as a header for that section. 

    2b.a. Markdown header designations may be used for styling purposes.
  
3. Thou shalt indicate scriptable data with {}

  3a. When thy brackets are used thou shalt put them on their own damn line and properly indent your data inside.
  
  3b. When scriptable data is csv thou shalt indicate table headers by prepending # to the line. 
  
    3b.a. Markdown header designations may be used for styling purposes.
    
  3c. csv data values for table formatting shall be all like (See the text file
  
4. Thou shalt never use JSON when CSV works better.

5. Thy special holy icon =(! Index)= shall display a compiled index of thar document that shall be properly tiered according to page designations and then markdown title designations in that order. 

