# xquery-csv-parser
## A flexible delimited text parser in XQuery.


_(note: this code has been around and unpublished for a few years, this just ports it to MarkLogic's dialect of XQuery)_

## Usage

Parses a sequence of strings into fields using delimiters. By default the delimiters are commas.

```
csv:parse-sequence($lines, map:map())
```

