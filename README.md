# 14_pre_commit_hook

This module help to you find the roots of quadratic equation.
Our team provides you with tests. 
To use solver please import function to your code: 

```python
from quadratic_equation import get_roots
```

To auto-testing befor commiting move pre-commit to $PROJECT_NAME/.git/hooks/

```sh
mv pre-commit ./.git/hooks/pre-commit
chmod +x .git/hooks/pre-commit
```
