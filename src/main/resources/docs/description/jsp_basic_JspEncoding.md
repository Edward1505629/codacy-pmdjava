Since: PMD 4.0

A missing 'meta' tag or page directive will trigger this rule, as well as a non-UTF-8 charset.

Example(s):
```
Most browsers should be able to interpret the following headers:
                
                <%@ page contentType="text/html; charset=UTF-8" pageEncoding="UTF-8" %>
                    
                <meta http-equiv="Content-Type"  content="text/html; charset=UTF-8" />
```

[Source](https://pmd.github.io/pmd-5.6.1/pmd-jsp/rules/jsp/basic.html#JspEncoding)
