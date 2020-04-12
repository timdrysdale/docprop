# docprop
tools for writing and reading custom properties/data to pdf for use in gradex

## Information to track

- whether original scan was portrait or landscape (to trigger the correct layout at each step, esp when aspect ratio changes with addition of side bars
- contents of the QR code (for dumping to report on request long after QR code has been flattened)
- student exam number(where available)
- course code (where available)
- date of submission (for avoiding confusion with future years)
- number of pages in the original submission
- page number that this doc corresponds to (we'll get multiples later from marking teams, so need to know this for merging as current page number may be meaingless)
- document udid representing a tag that follows it through a process
- history of operations performed on the doc (tool version number, command line, plus batch id if supplied, or time/date/user/pcname/ip, any additional information on how this data was obtained - e.g. human or computer, which will to a certain extent be inferrable from the nature of the command - import manually edited files or merge with OCr generated ata etc )
- the location of any registration marks
- a file with the registration marks? to help sub-image search
- the location of the QR code
- any comments or queries that have been raised, 
- any marks that have been awarded (if in text format), as we may flatten them)
- any questions identified on the page
- any metrics on the confidence of OCR prediction
- any info on the source of data entered ... if not fitting into the operations object
- identification of the marker, moderator and checker, if they are able to provide this information (first page)
