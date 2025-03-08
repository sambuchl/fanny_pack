### Copy all urls on page into clipboard
copy([...document.querySelectorAll("a")].map(a => `${a.innerText}: ${a.href}`).join("\n"));
