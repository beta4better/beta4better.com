---
layout: post
title: mali-drivers
date: '2016-12-07 14:17:20'
---

    $ sudo nano ~/trunk/src/private-overlays/overlay-veyron-private/virtual/opengles/opengles-3.ebuild
    
    diff --git a/virtual/opengles/opengles-3.ebuild b/virtual/opengles/opengles-3.ebuild
    index 77a48c3..55af75d 100644
    --- a/virtual/opengles/opengles-3.ebuild
    +++ b/virtual/opengles/opengles-3.ebuild
    @@ -10,7 +10,7 @@ SLOT="0"
     KEYWORDS="-* arm"

     DEPEND="
    -       media-libs/mali-drivers
    +       media-libs/mali-drivers-bin
            x11-drivers/opengles-headers
     "
     RDEPEND="${DEPEND}"
