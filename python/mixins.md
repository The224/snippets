---
description: Easily add extra properties and methods into multiple classes
---

# Mixins

Easily add extra properties and methods into multiple classes.

```python
import logging


class LoggingMixin:
    @property
    def logger(self):
        return logging.getLogger(self.__class__.__name__)


class TestClass(LoggingMixin, ):
    pass


test = TestClass()
test.logger.info("Hello World") >> INFO:TestClass:Hello World
```



