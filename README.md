**arxiv-rss:** daily query for new arXiv articles in select topics via RSS

[Daily, De-Duplicated arXiv RSS Updates: Keyword Parsed, Plus Non-Parsed Content](https://persagen.com/2019/06/10/arxiv-rss.html)

* A BASH script for daily retrieval of new, de-duplicated content from preselected arXiv groups.  That content is parsed into two files: keyword-matched articles of interest, plus the remaining articles.

  * As a crude measure of utility, I typically click (Vim: `gx` keypress) perhaps 2% of links in a "arxiv-others" results file and perhaps 20% of links in a "arxiv-filtered") file, a ≥10-fold enrichment in articles of interest.

* The script can be scheduled to run daily via crontab, or manually executed.

* If you have desktop notification (e.g. Linux `notify-send`), then a persistent message will indicate the arrival of new content

    ![notification](https://persagen.com/files/misc/arXiv-RSS-notify-send2.png)

**Sample results (file manager)**

![sample_output](https://persagen.com/files/misc/arxiv-rss-Krusader.png)

**Sample, filtered results (Neovim)**

![neovim_filtered-results](https://persagen.com/files/misc/arxiv-rss-in_Neovim.png)
