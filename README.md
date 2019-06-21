# py-stdout-logging

Log anything!

Usage:
------

Import and call once `Log.get_logger(level=Log.DEBUG)` then call `Log.info`,
`Log.warning`, `Log.error`, `Log.debug`, `Log.critical` with any number of any
type of argument (type must have `__str__` or `__unicode__` implemented.
Generally all data structure implements this, if you are using your own type,
implement `__str__` or `__unicode__`)
