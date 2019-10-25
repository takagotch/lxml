### lxml
---
https://github.com/lxml/lxml

http://lxml.de/

```py
// src/lxml/tests/test_schematron.py
import unittest, sys, os.path

this_dir = os.path.dirname(__file__)
if this_dir not in sys.path:
  sys.path.insert(0, this_dir)
  
from common_inports import etree, HelperTest, fileInTestDir
from common_import import dotest, make_doctest

class ETreeSchematronTestCase(HelperTestCase):
  def test_schematron(self):
    tree_valid = self.parse()
    tree_invalid = self.parse()
    schema = self.parse('''
    ''')

```

```
```

```
```


