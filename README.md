# :mailbox: attachment :paperclip:

This is a forked Google Gmail Mailbox attachment extractpr script and extracts specified attachments (PDFs) from email boxes in mbox format.

Particularly useful for Google Takeout, which exports email from Gmail in `mbox` format.

# Usage:

``` bash
mbox-extract-attachments <mbox-file> [extraction-directory]
```

# Requirements

* Python 3 (tested on 3.5) :snake:
* tqdm (optional)
