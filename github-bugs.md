This file contains github bug reports
=====================================

- If the repository (in which to clone) already exists, the harness should detect that and append some integer i+1 after it to avoid collision.

For example, if I clone Repo A into a repo named "Foo" five times, I should get the resulting repo

Foo
Foo 2
Foo 3
Foo 4
Foo 5

- 