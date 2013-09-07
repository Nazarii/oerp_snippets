oerp_snippets
=============
Snippets to make OpenERP code writing quicker.

Installation
=============
Simply copy these folders to you'r sublime User configuration folder, in Ubuntu it is located by default in ~/.config/sublime-text-3/Packages/User/.
Snippets works both in Sublime V2 and V3.

Usage
============
Each filename in these folder represents it's alias in Sublime excluding .sublime-text extension, e.g after typing *f_search* it will return to Sublime following code:
```python

def search(self, cr, uid, args, offset=0, limit=None, order=None, context=None, count=False):
    result = super(model_table, self).search(cr, uid, args, offset=offset, limit=limit, order=order, context=context, count=count)
    return result
```
Enjoy it!
