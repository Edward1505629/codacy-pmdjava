Since: PMD 3.9

Avoid using implementation types (i.e., HashSet); use the interface (i.e, Set) instead

Example(s):
```
import java.util.ArrayList;
import java.util.HashSet;

public class Bar {
		// Use List instead
	private ArrayList list = new ArrayList();
		// Use Set instead
	public HashSet getFoo() {
    return new HashSet();
  }
}
```
