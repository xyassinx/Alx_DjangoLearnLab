﻿# Create Operation

Command:
```python
from bookshelf.models import Book
book = Book(title="1984", author="George Orwell", publication_year=1949)
book.save()
#Expected Output:
#<Book: 1949 by George Orwell (1949)>