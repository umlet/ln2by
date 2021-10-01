# ln2by
Creating a symlink has never been that much fun!

By Zeus, I won't recall the argument order for creating a symlink with ``ln``.

I don't understand its ``man`` page. Other guides use *source* and *target* metaphors, which are either misleading or not misleading, and possibly both. And please don't mention the so-called "(3rd form)" of calling it.

Enter ``ln2by``: it creates a reference
- TO something existing      (1st argument),
- BY a newly created symlink (2nd argument).

In addition, ``ln2by`` won't let you overwrite an existing symlink, and it tries to catch the directory-as-2nd-argument calamity.
