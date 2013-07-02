SN
==

This is a theme of [Nico](http://lab.lepture.com/nico/) blog.

If you want to use this theme, you can download it and set you nico.json like:

    {
        "name": "BinbinLiao's Blog",
        "description": "BinbinLiao's Blog",
        "categorys": [{
            "name": "programming",
            "showName": "program",
            "description": "程序设计方面的文章"
        }, {
            "name": "zatan",
            "showName": "生活杂谈",
            "description": "生活杂谈"
        }],
        "perpage": 10,
        "sorttype": "desc",
        "source": "content",
        "output": "_site",
        "theme": "_themes/SN",
        "permalink": "{{directory}}/{{filename}}.html",
        "writers": [
            "nico.PostWriter",
            "nico.FileWriter",
            "nico.StaticWriter",
            "nico.TagWriter",
            "nico.DirectoryWriter",
            "nico.ArchiveWriter"
        ],
        "trackCode": "<script defer async type=\"text/javascript\" src=\"//hm.baidu.com/h.js?f10c9b0005de625e589f7dc9804b2787\"></script>"
    }