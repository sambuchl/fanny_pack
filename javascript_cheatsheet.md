### Copy all urls on page into clipboard
'''javascript
copy([...document.querySelectorAll("a")].map(a => `${a.innerText}: ${a.href}`).join("\n"));
