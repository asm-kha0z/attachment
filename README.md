# :mailbox: attachment :paperclip:

This is a forked Google Gmail Mailbox attachment extractor script and extracts specified attachments (PDFs) from email boxes in mbox format. In contrast to other scripts, this will also include attachments that were in the inline format. Inline attachments are particularly relevent if your mbox includes emails sent from Apple Mail users. If a PDF is dragged into the body of Apple Mail, it will be attached inline (similar to a Picture) and not coded as a regular file attachment.

Particularly useful for Google Takeout, which exports email from Gmail in `mbox` format.

# Usage:

``` bash
mbox-extract-attachments <mbox-file> [extraction-directory]
```

# Requirements

* Python 3 (tested on 3.5) :snake:
* tqdm (optional)
