# Frame TVs

Frames of services to TVs monitoring.

## Files Structure

    ./
    |
    +- carrega_frame.htm        # to load pages in de frames
    +- frame_four.htm           # template layout
    +- frame_three_bottom.htm   # template layout
    +- frame_three_top.htm      # template layout
    +- frame_three_v.htm        # template layout
    +- frame_two_h.htm          # template layout
    +- frame_two_v.htm          # template layout
    +- grupos_monitor.json      # data about monitoring frames: name, title, layout and links.
    +- index.htm                # index with two frames
    +- index2.htm               # just a copy of index: it was necessary because in case of use the browser's zoom, the N tabs with the same page will be get the same zoom.
    +- index3.htm               # just copy of index
    +- index_monitor.htm        # to read the anchor in the location bar and load de frames

## Usage

To add or change some group of pages/links, use the json file.

To charge the group of links, call in the Firefox browser:

    index.htm#[name_attribute] # eg. index.htm#grupoSites

___
Leslie Wittig Quintanilla
2012-10


