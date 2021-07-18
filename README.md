
    //<![CDATA[
    // Recent Post Gallery
    function gallerygrid(a) { 
        for (var t = a.feed.entry || [], e = ['<div class="recent-grid">'], i = 0; i < t.length; ++i) { 
            for (var l = t[i], r = l.title.$t, n = l.media$thumbnail ? l.media$thumbnail.url : "https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w680/nth.png", s = n.replace("s72-c", "s" + recentpost_thumbs + "-c"), h = l.link || [], c = 0; c < h.length && "alternate" != h[c].rel; ++c);
             var d = h[c].href, m = '<img src="' + s + '" width="' + recentpost_thumbs + '" height="' + recentpost_thumbs1 + '"/>', p = recentpost_title ? '<span class="ptitle">' + r + "</span>" : "", g = '<a href="' + d + '" target="_blank" title="' + r + '">' + m + p + "</a>"; e.push('<div class="galleryview">', g, "</div>") 
        } 
        e.push("</div>"), document.write(e.join("")) }
//]]>

    var recentpost_thumbs = 300;
    var recentpost_thumbs1 = 200;
    var recentpost_title = true;

    //<![CDATA[
    // Recent Post Gallery
    function gallerygrid1(a) { 
        for (var t = a.feed.entry || [], e = ['<div class="recent-grid1">'], i = 0; i < t.length; ++i) { 
            for (var l = t[i], r = l.title.$t, n = l.media$thumbnail ? l.media$thumbnail.url : "https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w680/nth.png", s = n.replace("s72-c", "s" + recentpost_thumbs + "-c"), h = l.link || [], c = 0; c < h.length && "alternate" != h[c].rel; ++c);
             var d = h[c].href, m = '<img src="' + s + '" width="' + recentpost_thumbs + '" height="' + recentpost_thumbs1 + '"/>', p = recentpost_title ? '<span class="ptitle1">' + r + "</span>" : "", g = '<a href="' + d + '" target="_blank" title="' + r + '">' + m + p + "</a>"; e.push('<div class="galleryview1">', g, "</div>") 
        } 
        e.push("</div>"), document.write(e.join("")) }
//]]>

    var recentpost_thumbs = 300;
    var recentpost_thumbs1 = 200;
    var recentpost_title = true;

    //<![CDATA[
    // Recent Post Gallery
    function gallerygrid2(a) { 
        for (var t = a.feed.entry || [], e = ['<div class="recent-grid2">'], i = 0; i < t.length; ++i) { 
            for (var l = t[i], r = l.title.$t, n = l.media$thumbnail ? l.media$thumbnail.url : "https://4.bp.blogspot.com/-O3EpVMWcoKw/WxY6-6I4--I/AAAAAAAAB2s/KzC0FqUQtkMdw7VzT6oOR_8vbZO6EJc-ACK4BGAYYCw/w680/nth.png", s = n.replace("s72-c", "s" + recentpost_thumbs + "-c"), h = l.link || [], c = 0; c < h.length && "alternate" != h[c].rel; ++c);
             var d = h[c].href, m = '<img src="' + s + '" width="' + recentpost_thumbs + '" height="' + recentpost_thumbs1 + '"/>', p = recentpost_title ? '<span class="ptitle2">' + r + "</span>" : "", g = '<a href="' + d + '" target="_blank" title="' + r + '">' + m + p + "</a>"; e.push('<div class="galleryview2">', g, "</div>") 
        } 
        e.push("</div>"), document.write(e.join("")) }
//]]>

    var recentpost_thumbs = 300;
    var recentpost_thumbs1 = 200;
    var recentpost_title = true;
