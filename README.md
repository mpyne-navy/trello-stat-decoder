# Overview

This repository hosts a web page that can be used to extract specific
[Trello](https://trello.com/) stats from a Trello board's JSON dump into a CSV
file.

You should just pay for Trello. It's not expensive and it includes direct
export to CSV if you give them money for their work. But if you work in an
organization where approval for "IT purchasing" will happen after the heat
death of the universe, then this may be the next best thing, as long as you
like my CSVs.

# Usage

Drag-and-drop the Trello JSON extract from your board onto the drop area.

The output panel at the bottom will automatically extract the tasks into a CSV
format textarea that you can copy-and-paste out of.

You can see the [live version](http://mpyne-navy.github.io/trello-stat-decoder/).

NOTE: There are **no communications** with Trello, or any server, to make this
work. Everything happens directly in the browser itself, and should even be
usable with the network disconnected once the page is loaded.

# Libraries

This uses:

* [PaperCSS](https://www.getpapercss.com/) (ISC license)

Thanks to:

* [jq](https://stedolan.github.io/jq/), which powered the first, non-Web-based
  version of this capability. But it turns out that organizations which can't
  figure out how to throw money at Trello also can't figure out how to enable
  people to use command-line JSON processors.

The software itself is MIT-licensed.
