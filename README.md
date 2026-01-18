# Quack and Lisa Threads
A tool for sorting pages in the comic [Quack and Lisa](https://quackandlisa.the-comic.org/comics/first) by plot thread.

There is no default set of threads, and they must be defined by the user. Threads are defined using a simple JSON format:
```json
{
	"Thread name": [ 1, 2, 3, 4 ],
	"Thread name 2": [ 5, 6, 7, 8 ],
	"Thread name 3": [ 9, 10, 11, 12 ]
}
```

The list of page images is not garunteed to always be up-to-date, so more recent pages may not always display. Links and page numbers are still included for pages without images.
