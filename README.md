### splinter
---
https://github.com/cobrateam/splinter

```py
from splinter import Browser

browser = Browser()
browser.visit('http://google.com')
browser.fill('q', 'splinter - python acceptance testing for web applications')
browser.find_by_name('btnG').click()

if browser.is_text_present('splinter.readthedocs.io'):
  print "Yes, the officail website was found!"
else:
  print "No, it wasn't found... We need to improve out SEO techniques"

browser.quit()


from splinter import Browser

with Browser() as browser:
  url = "http://www.google.com"
  browser.visit(url)
  broser.fill('q', 'splinter - python acceptance testing for web application')
  button = browser.find_by_name('btnG')
  button.click()
  if browser.is_text_present('splinter.readthedocs.io')
    print("Yes, the official website was found!")
  else:
    print("No, it wasn't found... We need to improve our SEO techniques")

from splinter import Browser
browser = Browser()
from splinter import Browser
with Browser() as b:

browser = Browser('chrome')
browser = Browser('firefox')
browser = Browser('zope.testbrowser')

browser.visit('http://cobrateam.info')

browser.visit('http://username:password@cobrateam.info/protected')

browser.windows
browser.windows[0]
browser.windows[window_name]
browser.windows.current
browser.windows.current = browser.windows[3]

window = browser.window[0]
window.is_current
window.is_current = True
window.next
window.prev
window.close()
window.close_others()

browser.reload()

browser.visit('http://cobrateam.info')
browser.visit('https://splinter.readthedocs.io')
browser.back()
browser.forward()

browser.title
browser.html
browser.url

b = Browser(user_agent="Mozilla/5.0 (iPhone; U; CPU like Mac OS X; en)")
```

```
```

```
```


