# pemml
Rules specifications for various formatting and extensibility upgrades for the markdown syntax (tentantively named: Pagination Enabled Markdown-style Markup Language). Designed for publishing rather than frontloading html content

Folders will attempt to include various (incomplete) implementations of pemml.

==========

1. Thou shalt never use the default github markdown syntax first and foremost.

  1a. Thou shalt use the pagination or print CSS or SCSS schematic to define your layout's physical space. Or don't I don't care.

2. Thou shalt indicate content pages with =( )= and use the parenthesis to indicate what kind of content will live there. 
  e.g.: =(?csv Roles)= should indicate a page titled "Roles" where the content is a table created from csv data. A page break will be automatically inserted before the next =( )=

  2a. When a data type is not defined the text inside that page shall be considered prose and therefore markdown rules shall apply.

  2b. When the data type is # the title will be used as a header for that section for navigation purposes. This behavior is not default and therefore all data types can be prepended with a pound sign to anchor them. Or not, in which case pages will not automatically be used in navigation nor designated in the holy special symbol the almighty index.

    2b.a. Markdown header designations may be used for styling purposes.
  
3. Thou shalt indicate scriptable data with {}

  3a. When thy brackets are used thou shalt put them on their own damn line and properly indent your data inside.
  
  3b. When scriptable data is csv thou shalt indicate table headers by prepending # to the line. 
  
    3b.a. Markdown header designations may be used for styling purposes.
    
  3c. csv data values for table formatting shall be all like (See the text file)
  
  3d. Thou shalt import scriptable data automatically by indicating the url in an additional (data type){url} 
  
  e.g.: (?csv){www.numbers.net/all.csv}
  
4. Thou shalt never use JSON when CSV works better.

5. Thy special holy icon =(! Index)= shall display a compiled index of thar document that shall be properly tiered according to page designations and then markdown title designations in that order. 

  5a. Thy special holy icon is subject to the rules of =( )=
  
6. Pictures shall be able to be linked either by base64 or by normal html-style slop it in via url. 

7. Using | in a line shall split content equally in columns from left to right and attempt to justify the result.

8. Escape characters with \
  
  8a. Escape \ with \
  


