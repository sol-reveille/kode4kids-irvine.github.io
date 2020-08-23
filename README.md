# Description

The code for kode4kids-irvine.github.io. Static, no server-side code, ajax POST request to web API to log form responses on Google Sheets, second request to send notification by email.

Possible issues:
- API key is visible to all users. This poses no security threat except for possibly our spreadsheet being spammed. It can't be helped, as GitHub only allows static pages, and without the resources to host my own server, all of this code is on the client side.
- CSS styling may vary between browsers. This issue has mostly been remedied with formalize.me.