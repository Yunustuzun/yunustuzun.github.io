# Custom Paginator for Grid Table

In this blog post, I will mention how we add paginator to grid tables. Firstly, the paginator control was in older versions. After 1.38 version of UI5, we couldn’t add paginator in grid tables.

When I started coding the pagination structure, It seems very easy. But after some parts of filtering, sorting, changing page count functionality, it became more and more complex. For Example; if you will use filtering you should regenerate paginator vs.

After this workings, I plan to create a new custom control and use it in view in an easy way.

You can view it in [Plunker](http://embed.plnkr.co/9Jlh6N/).
