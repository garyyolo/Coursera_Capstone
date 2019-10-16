

```python
conda install -c anaconda beautifulsoup4
```

    Collecting package metadata (current_repodata.json): ...working... done
    Solving environment: ...working... done
    
    ## Package Plan ##
    
      environment location: C:\Users\Gary\Anaconda3
    
      added / updated specs:
        - beautifulsoup4
    
    
    The following packages will be downloaded:
    
        package                    |            build
        ---------------------------|-----------------
        beautifulsoup4-4.7.1       |           py37_1         143 KB  anaconda
        ca-certificates-2019.5.15  |                0         166 KB  anaconda
        certifi-2019.6.16          |           py37_0         155 KB  anaconda
        conda-4.7.12               |           py37_0         3.0 MB  anaconda
        openssl-1.1.1c             |       he774522_1         5.7 MB  anaconda
        ------------------------------------------------------------
                                               Total:         9.2 MB
    
    The following packages will be UPDATED:
    
      conda                      pkgs/main::conda-4.7.10-py37_0 --> anaconda::conda-4.7.12-py37_0
    
    The following packages will be SUPERSEDED by a higher-priority channel:
    
      beautifulsoup4                                  pkgs/main --> anaconda
      ca-certificates                                 pkgs/main --> anaconda
      certifi                                         pkgs/main --> anaconda
      openssl                                         pkgs/main --> anaconda
    
    
    
    Downloading and Extracting Packages
    
    openssl-1.1.1c       | 5.7 MB    |            |   0% 
    openssl-1.1.1c       | 5.7 MB    |            |   0% 
    openssl-1.1.1c       | 5.7 MB    | 9          |  10% 
    openssl-1.1.1c       | 5.7 MB    | ###3       |  33% 
    openssl-1.1.1c       | 5.7 MB    | #####7     |  58% 
    openssl-1.1.1c       | 5.7 MB    | ########2  |  82% 
    openssl-1.1.1c       | 5.7 MB    | ########## | 100% 
    
    beautifulsoup4-4.7.1 | 143 KB    |            |   0% 
    beautifulsoup4-4.7.1 | 143 KB    | ########## | 100% 
    
    ca-certificates-2019 | 166 KB    |            |   0% 
    ca-certificates-2019 | 166 KB    | ########## | 100% 
    
    certifi-2019.6.16    | 155 KB    |            |   0% 
    certifi-2019.6.16    | 155 KB    | ########## | 100% 
    
    conda-4.7.12         | 3.0 MB    |            |   0% 
    conda-4.7.12         | 3.0 MB    | #5         |  16% 
    conda-4.7.12         | 3.0 MB    | ######3    |  64% 
    conda-4.7.12         | 3.0 MB    | ########## | 100% 
    Preparing transaction: ...working... done
    Verifying transaction: ...working... done
    Executing transaction: ...working... done
    
    Note: you may need to restart the kernel to use updated packages.
    

    
    
    ==> WARNING: A newer version of conda exists. <==
      current version: 4.7.10
      latest version: 4.7.12
    
    Please update conda by running
    
        $ conda update -n base -c defaults conda
    
    
    


```python
conda update -n base -c defaults conda
```

    
    Note: you may need to restart the kernel to use updated packages.
    

    usage: conda-script.py install [-h] [--revision REVISION]
                                   [-n ENVIRONMENT | -p PATH] [-c CHANNEL]
                                   [--use-local] [--override-channels]
                                   [--repodata-fn REPODATA_FNS]
                                   [--strict-channel-priority]
                                   [--no-channel-priority]
                                   [--no-deps | --only-deps] [--no-pin] [--copy]
                                   [--no-shortcuts] [-C] [-k] [--offline] [-d]
                                   [--json] [-q] [-v] [-y] [--download-only]
                                   [--show-channel-urls] [--file FILE]
                                   [--force-reinstall]
                                   [--freeze-installed | --update-deps | -S | --update-all | --update-specs]
                                   [-m] [--clobber] [--dev]
                                   [package_spec [package_spec ...]]
    conda-script.py install: error: argument -n/--name: not allowed with argument -p/--prefix
    


```python
conda install -c anaconda html5lib
```

    Collecting package metadata (current_repodata.json): ...working... done
    Solving environment: ...working... 
    The environment is inconsistent, please check the package plan carefully
    The following packages are causing the inconsistency:
    
      - defaults/win-64::anaconda==2019.07=py37_0
      - defaults/win-64::numba==0.44.1=py37hf9181ef_0
    done
    
    ## Package Plan ##
    
      environment location: C:\Users\Gary\Anaconda3
    
      added / updated specs:
        - html5lib
    
    
    The following packages will be downloaded:
    
        package                    |            build
        ---------------------------|-----------------
        _anaconda_depends-2019.03  |           py37_0           5 KB  anaconda
        anaconda-custom            |           py37_1           3 KB
        ca-certificates-2019.8.28  |                0         165 KB  anaconda
        certifi-2019.9.11          |           py37_0         155 KB  anaconda
        html5lib-1.0.1             |           py37_0         181 KB  anaconda
        openssl-1.1.1              |       he774522_0         5.7 MB  anaconda
        tbb-2019.4                 |       h74a9793_0         173 KB  anaconda
        ------------------------------------------------------------
                                               Total:         6.4 MB
    
    The following NEW packages will be INSTALLED:
    
      _anaconda_depends  anaconda/win-64::_anaconda_depends-2019.03-py37_0
      tbb                anaconda/win-64::tbb-2019.4-h74a9793_0
    
    The following packages will be UPDATED:
    
      ca-certificates                               2019.5.15-0 --> 2019.8.28-0
      certifi                                  2019.6.16-py37_0 --> 2019.9.11-py37_0
      openssl                                 1.1.1c-he774522_1 --> 1.1.1-he774522_0
    
    The following packages will be SUPERSEDED by a higher-priority channel:
    
      html5lib                                        pkgs/main --> anaconda
    
    The following packages will be DOWNGRADED:
    
      anaconda                                   2019.07-py37_0 --> custom-py37_1
    
    
    
    Downloading and Extracting Packages
    
    html5lib-1.0.1       | 181 KB    |            |   0% 
    html5lib-1.0.1       | 181 KB    | 8          |   9% 
    html5lib-1.0.1       | 181 KB    | ########## | 100% 
    
    _anaconda_depends-20 | 5 KB      |            |   0% 
    _anaconda_depends-20 | 5 KB      | ########## | 100% 
    
    tbb-2019.4           | 173 KB    |            |   0% 
    tbb-2019.4           | 173 KB    | ########3  |  83% 
    tbb-2019.4           | 173 KB    | ########## | 100% 
    
    anaconda-custom      | 3 KB      |            |   0% 
    anaconda-custom      | 3 KB      | ########## | 100% 
    
    openssl-1.1.1        | 5.7 MB    |            |   0% 
    openssl-1.1.1        | 5.7 MB    | #          |  11% 
    openssl-1.1.1        | 5.7 MB    | ###4       |  35% 
    openssl-1.1.1        | 5.7 MB    | #####8     |  59% 
    openssl-1.1.1        | 5.7 MB    | ########2  |  83% 
    openssl-1.1.1        | 5.7 MB    | ########## | 100% 
    
    certifi-2019.9.11    | 155 KB    |            |   0% 
    certifi-2019.9.11    | 155 KB    | ########## | 100% 
    
    ca-certificates-2019 | 165 KB    |            |   0% 
    ca-certificates-2019 | 165 KB    | ########## | 100% 
    Preparing transaction: ...working... done
    Verifying transaction: ...working... done
    Executing transaction: ...working... done
    
    Note: you may need to restart the kernel to use updated packages.
    


```python
conda install -c anaconda requests
```

    Collecting package metadata (current_repodata.json): ...working... done
    Solving environment: ...working... done
    
    ## Package Plan ##
    
      environment location: C:\Users\Gary\Anaconda3
    
      added / updated specs:
        - requests
    
    
    The following packages will be downloaded:
    
        package                    |            build
        ---------------------------|-----------------
        requests-2.22.0            |           py37_0          90 KB  anaconda
        ------------------------------------------------------------
                                               Total:          90 KB
    
    The following packages will be SUPERSEDED by a higher-priority channel:
    
      requests                                        pkgs/main --> anaconda
    
    
    
    Downloading and Extracting Packages
    
    requests-2.22.0      | 90 KB     |            |   0% 
    requests-2.22.0      | 90 KB     | #7         |  18% 
    requests-2.22.0      | 90 KB     | ########## | 100% 
    Preparing transaction: ...working... done
    Verifying transaction: ...working... done
    Executing transaction: ...working... done
    
    Note: you may need to restart the kernel to use updated packages.
    


```python
!conda install -c conda-forge folium=0.5.0 --yes
```

    Collecting package metadata (current_repodata.json): ...working... done
    Solving environment: ...working... failed with initial frozen solve. Retrying with flexible solve.
    Collecting package metadata (repodata.json): ...working... done
    Solving environment: ...working... done
    
    ## Package Plan ##
    
      environment location: C:\Users\Gary\Anaconda3
    
      added / updated specs:
        - folium=0.5.0
    
    
    The following packages will be downloaded:
    
        package                    |            build
        ---------------------------|-----------------
        altair-3.2.0               |           py37_0         749 KB  conda-forge
        branca-0.3.1               |             py_0          25 KB  conda-forge
        ca-certificates-2019.9.11  |       hecc5488_0         181 KB  conda-forge
        certifi-2019.6.16          |           py37_1         149 KB  conda-forge
        conda-4.7.12               |           py37_0         3.0 MB  conda-forge
        folium-0.5.0               |             py_0          45 KB  conda-forge
        openssl-1.1.1c             |       hfa6e2cd_0         4.7 MB  conda-forge
        vincent-0.4.4              |             py_1          28 KB  conda-forge
        ------------------------------------------------------------
                                               Total:         8.9 MB
    
    The following NEW packages will be INSTALLED:
    
      altair             conda-forge/win-64::altair-3.2.0-py37_0
      branca             conda-forge/noarch::branca-0.3.1-py_0
      folium             conda-forge/noarch::folium-0.5.0-py_0
      vincent            conda-forge/noarch::vincent-0.4.4-py_1
    
    The following packages will be UPDATED:
    
      ca-certificates     anaconda::ca-certificates-2019.8.28-0 --> conda-forge::ca-certificates-2019.9.11-hecc5488_0
    
    The following packages will be SUPERSEDED by a higher-priority channel:
    
      certifi                anaconda::certifi-2019.9.11-py37_0 --> conda-forge::certifi-2019.6.16-py37_1
      conda                                            anaconda --> conda-forge
      openssl                anaconda::openssl-1.1.1-he774522_0 --> conda-forge::openssl-1.1.1c-hfa6e2cd_0
    
    
    
    Downloading and Extracting Packages
    
    conda-4.7.12         | 3.0 MB    |            |   0% 
    conda-4.7.12         | 3.0 MB    |            |   1% 
    conda-4.7.12         | 3.0 MB    | ##5        |  26% 
    conda-4.7.12         | 3.0 MB    | #######2   |  73% 
    conda-4.7.12         | 3.0 MB    | ########## | 100% 
    
    openssl-1.1.1c       | 4.7 MB    |            |   0% 
    openssl-1.1.1c       | 4.7 MB    | #3         |  14% 
    openssl-1.1.1c       | 4.7 MB    | ####1      |  42% 
    openssl-1.1.1c       | 4.7 MB    | #######2   |  72% 
    openssl-1.1.1c       | 4.7 MB    | ########## | 100% 
    
    ca-certificates-2019 | 181 KB    |            |   0% 
    ca-certificates-2019 | 181 KB    | ########## | 100% 
    
    branca-0.3.1         | 25 KB     |            |   0% 
    branca-0.3.1         | 25 KB     | ########## | 100% 
    
    certifi-2019.6.16    | 149 KB    |            |   0% 
    certifi-2019.6.16    | 149 KB    | ########## | 100% 
    
    altair-3.2.0         | 749 KB    |            |   0% 
    altair-3.2.0         | 749 KB    | 2          |   2% 
    altair-3.2.0         | 749 KB    | ########## | 100% 
    
    folium-0.5.0         | 45 KB     |            |   0% 
    folium-0.5.0         | 45 KB     | ########## | 100% 
    
    vincent-0.4.4        | 28 KB     |            |   0% 
    vincent-0.4.4        | 28 KB     | ########## | 100% 
    Preparing transaction: ...working... done
    Verifying transaction: ...working... done
    Executing transaction: ...working... done
    

# Scrape the Wikipedia page and read the table of postal codes and to transform the data into a pandas dataframe 


```python
from bs4 import BeautifulSoup
import requests
import pandas as pd
```


```python
url='https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M'
source=requests.get(url).text
soup=BeautifulSoup(source,'lxml')
print(soup.prettify())
```

    <!DOCTYPE html>
    <html class="client-nojs" dir="ltr" lang="en">
     <head>
      <meta charset="utf-8"/>
      <title>
       List of postal codes of Canada: M - Wikipedia
      </title>
      <script>
       document.documentElement.className="client-js";RLCONF={"wgCanonicalNamespace":"","wgCanonicalSpecialPageName":!1,"wgNamespaceNumber":0,"wgPageName":"List_of_postal_codes_of_Canada:_M","wgTitle":"List of postal codes of Canada: M","wgCurRevisionId":920980179,"wgRevisionId":920980179,"wgArticleId":539066,"wgIsArticle":!0,"wgIsRedirect":!1,"wgAction":"view","wgUserName":null,"wgUserGroups":["*"],"wgCategories":["Communications in Ontario","Postal codes in Canada","Toronto","Ontario-related lists"],"wgBreakFrames":!1,"wgPageContentLanguage":"en","wgPageContentModel":"wikitext","wgSeparatorTransformTable":["",""],"wgDigitTransformTable":["",""],"wgDefaultDateFormat":"dmy","wgMonthNames":["","January","February","March","April","May","June","July","August","September","October","November","December"],"wgMonthNamesShort":["","Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"],"wgRelevantPageName":"List_of_postal_codes_of_Canada:_M","wgRelevantArticleId":539066,
    "wgRequestId":"XaKa3wpAAEYAAB8AEs0AAAAW","wgCSPNonce":!1,"wgIsProbablyEditable":!0,"wgRelevantPageIsProbablyEditable":!0,"wgRestrictionEdit":[],"wgRestrictionMove":[],"wgMediaViewerOnClick":!0,"wgMediaViewerEnabledByDefault":!0,"wgPopupsReferencePreviews":!1,"wgPopupsConflictsWithNavPopupGadget":!1,"wgVisualEditor":{"pageLanguageCode":"en","pageLanguageDir":"ltr","pageVariantFallbacks":"en"},"wgMFDisplayWikibaseDescriptions":{"search":!0,"nearby":!0,"watchlist":!0,"tagline":!1},"wgWMESchemaEditAttemptStepOversample":!1,"wgULSCurrentAutonym":"English","wgNoticeProject":"wikipedia","wgWikibaseItemId":"Q3248240","wgCentralAuthMobileDomain":!1,"wgEditSubmitButtonLabelPublish":!0};RLSTATE={"ext.globalCssJs.user.styles":"ready","site.styles":"ready","noscript":"ready","user.styles":"ready","ext.globalCssJs.user":"ready","user":"ready","user.options":"ready","user.tokens":"loading","ext.cite.styles":"ready","mediawiki.legacy.shared":"ready",
    "mediawiki.legacy.commonPrint":"ready","jquery.tablesorter.styles":"ready","wikibase.client.init":"ready","ext.visualEditor.desktopArticleTarget.noscript":"ready","ext.uls.interlanguage":"ready","ext.wikimediaBadges":"ready","ext.3d.styles":"ready","mediawiki.skinning.interface":"ready","skins.vector.styles":"ready"};RLPAGEMODULES=["ext.cite.ux-enhancements","ext.cite.tracking","site","mediawiki.page.startup","mediawiki.page.ready","jquery.tablesorter","mediawiki.searchSuggest","ext.gadget.teahouse","ext.gadget.ReferenceTooltips","ext.gadget.watchlist-notice","ext.gadget.DRN-wizard","ext.gadget.charinsert","ext.gadget.refToolbar","ext.gadget.extra-toolbar-buttons","ext.gadget.switcher","ext.centralauth.centralautologin","mmv.head","mmv.bootstrap.autostart","ext.popups","ext.visualEditor.desktopArticleTarget.init","ext.visualEditor.targetLoader","ext.eventLogging","ext.wikimediaEvents","ext.navigationTiming","ext.uls.compactlinks","ext.uls.interface","ext.cx.eventlogging.campaigns",
    "ext.quicksurveys.init","ext.centralNotice.geoIP","ext.centralNotice.startUp","skins.vector.js"];
      </script>
      <script>
       (RLQ=window.RLQ||[]).push(function(){mw.loader.implement("user.tokens@tffin",function($,jQuery,require,module){/*@nomin*/mw.user.tokens.set({"patrolToken":"+\\","watchToken":"+\\","csrfToken":"+\\"});
    });});
      </script>
      <link href="/w/load.php?lang=en&amp;modules=ext.3d.styles%7Cext.cite.styles%7Cext.uls.interlanguage%7Cext.visualEditor.desktopArticleTarget.noscript%7Cext.wikimediaBadges%7Cjquery.tablesorter.styles%7Cmediawiki.legacy.commonPrint%2Cshared%7Cmediawiki.skinning.interface%7Cskins.vector.styles%7Cwikibase.client.init&amp;only=styles&amp;skin=vector" rel="stylesheet"/>
      <script async="" src="/w/load.php?lang=en&amp;modules=startup&amp;only=scripts&amp;raw=1&amp;skin=vector">
      </script>
      <meta content="" name="ResourceLoaderDynamicStyles"/>
      <link href="/w/load.php?lang=en&amp;modules=site.styles&amp;only=styles&amp;skin=vector" rel="stylesheet"/>
      <meta content="MediaWiki 1.35.0-wmf.1" name="generator"/>
      <meta content="origin" name="referrer"/>
      <meta content="origin-when-crossorigin" name="referrer"/>
      <meta content="origin-when-cross-origin" name="referrer"/>
      <link href="android-app://org.wikipedia/http/en.m.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M" rel="alternate"/>
      <link href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=edit" rel="alternate" title="Edit this page" type="application/x-wiki"/>
      <link href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=edit" rel="edit" title="Edit this page"/>
      <link href="/static/apple-touch/wikipedia.png" rel="apple-touch-icon"/>
      <link href="/static/favicon/wikipedia.ico" rel="shortcut icon"/>
      <link href="/w/opensearch_desc.php" rel="search" title="Wikipedia (en)" type="application/opensearchdescription+xml"/>
      <link href="//en.wikipedia.org/w/api.php?action=rsd" rel="EditURI" type="application/rsd+xml"/>
      <link href="//creativecommons.org/licenses/by-sa/3.0/" rel="license"/>
      <link href="https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M" rel="canonical"/>
      <link href="//login.wikimedia.org" rel="dns-prefetch"/>
      <link href="//meta.wikimedia.org" rel="dns-prefetch"/>
      <!--[if lt IE 9]><script src="/w/resources/lib/html5shiv/html5shiv.js"></script><![endif]-->
     </head>
     <body class="mediawiki ltr sitedir-ltr mw-hide-empty-elt ns-0 ns-subject mw-editable page-List_of_postal_codes_of_Canada_M rootpage-List_of_postal_codes_of_Canada_M skin-vector action-view">
      <div class="noprint" id="mw-page-base">
      </div>
      <div class="noprint" id="mw-head-base">
      </div>
      <div class="mw-body" id="content" role="main">
       <a id="top">
       </a>
       <div class="mw-body-content" id="siteNotice">
        <!-- CentralNotice -->
       </div>
       <div class="mw-indicators mw-body-content">
       </div>
       <h1 class="firstHeading" id="firstHeading" lang="en">
        List of postal codes of Canada: M
       </h1>
       <div class="mw-body-content" id="bodyContent">
        <div class="noprint" id="siteSub">
         From Wikipedia, the free encyclopedia
        </div>
        <div id="contentSub">
        </div>
        <div id="jump-to-nav">
        </div>
        <a class="mw-jump-link" href="#mw-head">
         Jump to navigation
        </a>
        <a class="mw-jump-link" href="#p-search">
         Jump to search
        </a>
        <div class="mw-content-ltr" dir="ltr" id="mw-content-text" lang="en">
         <div class="mw-parser-output">
          <p>
           This is a list of
           <a href="/wiki/Postal_codes_in_Canada" title="Postal codes in Canada">
            postal codes in Canada
           </a>
           where the first letter is M. Postal codes beginning with M are located within the city of
           <a href="/wiki/Toronto" title="Toronto">
            Toronto
           </a>
           in the province of
           <a href="/wiki/Ontario" title="Ontario">
            Ontario
           </a>
           . Only the first three characters are listed, corresponding to the Forward Sortation Area.
          </p>
          <p>
           <a href="/wiki/Canada_Post" title="Canada Post">
            Canada Post
           </a>
           provides a free postal code look-up tool on its website,
           <sup class="reference" id="cite_ref-1">
            <a href="#cite_note-1">
             [1]
            </a>
           </sup>
           via its
           <a href="/wiki/Mobile_app" title="Mobile app">
            applications
           </a>
           for such
           <a class="mw-redirect" href="/wiki/Smartphones" title="Smartphones">
            smartphones
           </a>
           as the
           <a href="/wiki/IPhone" title="IPhone">
            iPhone
           </a>
           and
           <a href="/wiki/BlackBerry" title="BlackBerry">
            BlackBerry
           </a>
           ,
           <sup class="reference" id="cite_ref-2">
            <a href="#cite_note-2">
             [2]
            </a>
           </sup>
           and sells hard-copy directories and
           <a href="/wiki/CD-ROM" title="CD-ROM">
            CD-ROMs
           </a>
           . Many vendors also sell validation tools, which allow customers to properly match addresses and postal codes. Hard-copy directories can also be consulted in all post offices, and some libraries.
          </p>
          <h2>
           <span class="mw-headline" id="Toronto_-_FSAs">
            <a href="/wiki/Toronto" title="Toronto">
             Toronto
            </a>
            -
            <a href="/wiki/Postal_codes_in_Canada#Forward_sortation_areas" title="Postal codes in Canada">
             FSAs
            </a>
           </span>
           <span class="mw-editsection">
            <span class="mw-editsection-bracket">
             [
            </span>
            <a href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=edit&amp;section=1" title="Edit section: Toronto - FSAs">
             edit
            </a>
            <span class="mw-editsection-bracket">
             ]
            </span>
           </span>
          </h2>
          <p>
           Note: There are no rural FSAs in Toronto, hence no postal codes should start with M0, however, the postal code M0R 8T0 is assigned to an
           <a href="/wiki/Amazon_(company)" title="Amazon (company)">
            Amazon (company)
           </a>
           warehouse in Mississauga, suggesting that Canada Post may be allocating the M0 FSA for high volume addresses.
          </p>
          <table class="wikitable sortable">
           <tbody>
            <tr>
             <th>
              Postcode
             </th>
             <th>
              Borough
             </th>
             <th>
              Neighbourhood
             </th>
            </tr>
            <tr>
             <td>
              M1A
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M2A
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M3A
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Parkwoods" title="Parkwoods">
               Parkwoods
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M4A
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Victoria_Village" title="Victoria Village">
               Victoria Village
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5A
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Harbourfront_(Toronto)" title="Harbourfront (Toronto)">
               Harbourfront
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5A
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Regent_Park" title="Regent Park">
               Regent Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6A
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Lawrence_Heights" title="Lawrence Heights">
               Lawrence Heights
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6A
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Lawrence_Manor" title="Lawrence Manor">
               Lawrence Manor
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M7A
             </td>
             <td>
              <a href="/wiki/Queen%27s_Park_(Toronto)" title="Queen's Park (Toronto)">
               Queen's Park
              </a>
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8A
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9A
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Islington_Avenue" title="Islington Avenue">
               Islington Avenue
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1B
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Rouge,_Toronto" title="Rouge, Toronto">
               Rouge
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1B
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Malvern,_Toronto" title="Malvern, Toronto">
               Malvern
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2B
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M3B
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Don Mills North
             </td>
            </tr>
            <tr>
             <td>
              M4B
             </td>
             <td>
              <a href="/wiki/East_York" title="East York">
               East York
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Woodbine_Gardens" title="Woodbine Gardens">
               Woodbine Gardens
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M4B
             </td>
             <td>
              <a href="/wiki/East_York" title="East York">
               East York
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Parkview_Hill" title="Parkview Hill">
               Parkview Hill
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5B
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Ryerson
             </td>
            </tr>
            <tr>
             <td>
              M5B
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Garden District
             </td>
            </tr>
            <tr>
             <td>
              M6B
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Glencairn
             </td>
            </tr>
            <tr>
             <td>
              M7B
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8B
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9B
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Cloverdale
             </td>
            </tr>
            <tr>
             <td>
              M9B
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Islington,_Toronto" title="Islington, Toronto">
               Islington
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9B
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Martin Grove
             </td>
            </tr>
            <tr>
             <td>
              M9B
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/Princess_Gardens" title="Princess Gardens">
               Princess Gardens
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9B
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/West_Deane_Park" title="West Deane Park">
               West Deane Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1C
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Highland_Creek_(Toronto)" title="Highland Creek (Toronto)">
               Highland Creek
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1C
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Rouge_Hill" title="Rouge Hill">
               Rouge Hill
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1C
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Port_Union,_Toronto" title="Port Union, Toronto">
               Port Union
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2C
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M3C
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Flemingdon_Park" title="Flemingdon Park">
               Flemingdon Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M3C
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Don Mills South
             </td>
            </tr>
            <tr>
             <td>
              M4C
             </td>
             <td>
              <a href="/wiki/East_York" title="East York">
               East York
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Woodbine_Heights" title="Woodbine Heights">
               Woodbine Heights
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5C
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/St._James_Town" title="St. James Town">
               St. James Town
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6C
             </td>
             <td>
              York
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Humewood-Cedarvale" title="Humewood-Cedarvale">
               Humewood-Cedarvale
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M7C
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8C
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9C
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Bloordale Gardens
             </td>
            </tr>
            <tr>
             <td>
              M9C
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Eringate
             </td>
            </tr>
            <tr>
             <td>
              M9C
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/Markland_Wood" title="Markland Wood">
               Markland Wood
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9C
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Old Burnhamthorpe
             </td>
            </tr>
            <tr>
             <td>
              M1E
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              Guildwood
             </td>
            </tr>
            <tr>
             <td>
              M1E
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Morningside,_Toronto" title="Morningside, Toronto">
               Morningside
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1E
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/West_Hill,_Toronto" title="West Hill, Toronto">
               West Hill
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2E
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M3E
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M4E
             </td>
             <td>
              <a href="/wiki/East_Toronto" title="East Toronto">
               East Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/The_Beaches" title="The Beaches">
               The Beaches
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5E
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Berczy_Park" title="Berczy Park">
               Berczy Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6E
             </td>
             <td>
              York
             </td>
             <td>
              Caledonia-Fairbanks
             </td>
            </tr>
            <tr>
             <td>
              M7E
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8E
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9E
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M1G
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Woburn,_Toronto" title="Woburn, Toronto">
               Woburn
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2G
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M3G
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M4G
             </td>
             <td>
              <a href="/wiki/East_York" title="East York">
               East York
              </a>
             </td>
             <td>
              <a href="/wiki/Leaside" title="Leaside">
               Leaside
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5G
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Central Bay Street
             </td>
            </tr>
            <tr>
             <td>
              M6G
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Christie
             </td>
            </tr>
            <tr>
             <td>
              M7G
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8G
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9G
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M1H
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              Cedarbrae
             </td>
            </tr>
            <tr>
             <td>
              M2H
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Hillcrest_Village" title="Hillcrest Village">
               Hillcrest Village
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M3H
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Bathurst_Manor" title="Bathurst Manor">
               Bathurst Manor
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M3H
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Downsview North
             </td>
            </tr>
            <tr>
             <td>
              M3H
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Wilson_Heights,_Toronto" title="Wilson Heights, Toronto">
               Wilson Heights
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M4H
             </td>
             <td>
              <a href="/wiki/East_York" title="East York">
               East York
              </a>
             </td>
             <td>
              <a href="/wiki/Thorncliffe_Park" title="Thorncliffe Park">
               Thorncliffe Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5H
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Adelaide
             </td>
            </tr>
            <tr>
             <td>
              M5H
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              King
             </td>
            </tr>
            <tr>
             <td>
              M5H
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Richmond
             </td>
            </tr>
            <tr>
             <td>
              M6H
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Dovercourt_Village" title="Dovercourt Village">
               Dovercourt Village
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6H
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              Dufferin
             </td>
            </tr>
            <tr>
             <td>
              M7H
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8H
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9H
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M1J
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Scarborough_Village" title="Scarborough Village">
               Scarborough Village
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2J
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Fairview
             </td>
            </tr>
            <tr>
             <td>
              M2J
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Henry_Farm" title="Henry Farm">
               Henry Farm
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2J
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Oriole
             </td>
            </tr>
            <tr>
             <td>
              M3J
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Northwood_Park" title="Northwood Park">
               Northwood Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M3J
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/York_University" title="York University">
               York University
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M4J
             </td>
             <td>
              <a href="/wiki/East_York" title="East York">
               East York
              </a>
             </td>
             <td>
              <a href="/wiki/East_Toronto" title="East Toronto">
               East Toronto
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5J
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Harbourfront East
             </td>
            </tr>
            <tr>
             <td>
              M5J
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Toronto_Islands" title="Toronto Islands">
               Toronto Islands
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5J
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Union_Station_(Toronto)" title="Union Station (Toronto)">
               Union Station
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6J
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Little_Portugal,_Toronto" title="Little Portugal, Toronto">
               Little Portugal
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6J
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Trinity%E2%80%93Bellwoods" title="Trinity–Bellwoods">
               Trinity
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M7J
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8J
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9J
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M1K
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              East Birchmount Park
             </td>
            </tr>
            <tr>
             <td>
              M1K
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Ionview" title="Ionview">
               Ionview
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1K
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Kennedy_Park,_Toronto" title="Kennedy Park, Toronto">
               Kennedy Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2K
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Bayview_Village" title="Bayview Village">
               Bayview Village
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M3K
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/CFB_Toronto" title="CFB Toronto">
               CFB Toronto
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M3K
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Downsview East
             </td>
            </tr>
            <tr>
             <td>
              M4K
             </td>
             <td>
              <a href="/wiki/East_Toronto" title="East Toronto">
               East Toronto
              </a>
             </td>
             <td>
              The Danforth West
             </td>
            </tr>
            <tr>
             <td>
              M4K
             </td>
             <td>
              <a href="/wiki/East_Toronto" title="East Toronto">
               East Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Riverdale,_Toronto" title="Riverdale, Toronto">
               Riverdale
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5K
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Design_Exchange" title="Design Exchange">
               Design Exchange
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5K
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Toronto_Dominion_Centre" title="Toronto Dominion Centre">
               Toronto Dominion Centre
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6K
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              Brockton
             </td>
            </tr>
            <tr>
             <td>
              M6K
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Exhibition_Place" title="Exhibition Place">
               Exhibition Place
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6K
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Parkdale_Village" title="Parkdale Village">
               Parkdale Village
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M7K
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8K
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9K
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M1L
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Clairlea" title="Clairlea">
               Clairlea
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1L
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Golden_Mile,_Toronto" title="Golden Mile, Toronto">
               Golden Mile
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1L
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Oakridge,_Toronto" title="Oakridge, Toronto">
               Oakridge
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2L
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Silver Hills
             </td>
            </tr>
            <tr>
             <td>
              M2L
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/York_Mills" title="York Mills">
               York Mills
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M3L
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Downsview" title="Downsview">
               Downsview West
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M4L
             </td>
             <td>
              <a href="/wiki/East_Toronto" title="East Toronto">
               East Toronto
              </a>
             </td>
             <td>
              The Beaches West
             </td>
            </tr>
            <tr>
             <td>
              M4L
             </td>
             <td>
              <a href="/wiki/East_Toronto" title="East Toronto">
               East Toronto
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/India_Bazaar" title="India Bazaar">
               India Bazaar
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5L
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Commerce_Court" title="Commerce Court">
               Commerce Court
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5L
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Victoria Hotel
             </td>
            </tr>
            <tr>
             <td>
              M6L
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Downsview,_Toronto" title="Downsview, Toronto">
               Downsview
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6L
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              North Park
             </td>
            </tr>
            <tr>
             <td>
              M6L
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Upwood Park
             </td>
            </tr>
            <tr>
             <td>
              M7L
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8L
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9L
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Humber_Summit" title="Humber Summit">
               Humber Summit
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1M
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Cliffcrest" title="Cliffcrest">
               Cliffcrest
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1M
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Cliffside,_Toronto" title="Cliffside, Toronto">
               Cliffside
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1M
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              Scarborough Village West
             </td>
            </tr>
            <tr>
             <td>
              M2M
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Newtonbrook" title="Newtonbrook">
               Newtonbrook
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2M
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Willowdale,_Toronto" title="Willowdale, Toronto">
               Willowdale
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M3M
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Downsview Central
             </td>
            </tr>
            <tr>
             <td>
              M4M
             </td>
             <td>
              <a href="/wiki/East_Toronto" title="East Toronto">
               East Toronto
              </a>
             </td>
             <td>
              Studio District
             </td>
            </tr>
            <tr>
             <td>
              M5M
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a href="/wiki/Bedford_Park,_Toronto" title="Bedford Park, Toronto">
               Bedford Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5M
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Lawrence Manor East
             </td>
            </tr>
            <tr>
             <td>
              M6M
             </td>
             <td>
              <a href="/wiki/York,_Toronto" title="York, Toronto">
               York
              </a>
             </td>
             <td>
              Del Ray
             </td>
            </tr>
            <tr>
             <td>
              M6M
             </td>
             <td>
              <a href="/wiki/York,_Toronto" title="York, Toronto">
               York
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Keelesdale" title="Keelesdale">
               Keelesdale
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6M
             </td>
             <td>
              <a href="/wiki/York,_Toronto" title="York, Toronto">
               York
              </a>
             </td>
             <td>
              <a href="/wiki/Mount_Dennis" title="Mount Dennis">
               Mount Dennis
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6M
             </td>
             <td>
              <a href="/wiki/York,_Toronto" title="York, Toronto">
               York
              </a>
             </td>
             <td>
              <a href="/wiki/Silverthorn,_Toronto" title="Silverthorn, Toronto">
               Silverthorn
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M7M
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8M
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9M
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Emery,_Toronto" title="Emery, Toronto">
               Emery
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9M
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Humberlea" title="Humberlea">
               Humberlea
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1N
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Birch_Cliff" title="Birch Cliff">
               Birch Cliff
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1N
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              Cliffside West
             </td>
            </tr>
            <tr>
             <td>
              M2N
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Willowdale South
             </td>
            </tr>
            <tr>
             <td>
              M3N
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              Downsview Northwest
             </td>
            </tr>
            <tr>
             <td>
              M4N
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Lawrence_Park,_Toronto" title="Lawrence Park, Toronto">
               Lawrence Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5N
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              Roselawn
             </td>
            </tr>
            <tr>
             <td>
              M6N
             </td>
             <td>
              <a href="/wiki/York,_Toronto" title="York, Toronto">
               York
              </a>
             </td>
             <td>
              The Junction North
             </td>
            </tr>
            <tr>
             <td>
              M6N
             </td>
             <td>
              <a href="/wiki/York,_Toronto" title="York, Toronto">
               York
              </a>
             </td>
             <td>
              Runnymede
             </td>
            </tr>
            <tr>
             <td>
              M7N
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8N
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9N
             </td>
             <td>
              <a href="/wiki/York,_Toronto" title="York, Toronto">
               York
              </a>
             </td>
             <td>
              <a href="/wiki/Weston,_Toronto" title="Weston, Toronto">
               Weston
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1P
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Dorset_Park" title="Dorset Park">
               Dorset Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1P
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Scarborough_Town_Centre" title="Scarborough Town Centre">
               Scarborough Town Centre
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1P
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Wexford_Heights" title="Wexford Heights">
               Wexford Heights
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2P
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              York Mills West
             </td>
            </tr>
            <tr>
             <td>
              M3P
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M4P
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              Davisville North
             </td>
            </tr>
            <tr>
             <td>
              M5P
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Forest_Hill_North" title="Forest Hill North">
               Forest Hill North
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5P
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              Forest Hill West
             </td>
            </tr>
            <tr>
             <td>
              M6P
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/High_Park" title="High Park">
               High Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6P
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              The Junction South
             </td>
            </tr>
            <tr>
             <td>
              M7P
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8P
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9P
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Westmount
             </td>
            </tr>
            <tr>
             <td>
              M1R
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Maryvale,_Toronto" title="Maryvale, Toronto">
               Maryvale
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1R
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Wexford,_Toronto" title="Wexford, Toronto">
               Wexford
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2R
             </td>
             <td>
              <a href="/wiki/North_York" title="North York">
               North York
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Willowdale_West" title="Willowdale West">
               Willowdale West
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M3R
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M4R
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              North Toronto West
             </td>
            </tr>
            <tr>
             <td>
              M5R
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/The_Annex" title="The Annex">
               The Annex
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5R
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              North Midtown
             </td>
            </tr>
            <tr>
             <td>
              M5R
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Yorkville,_Toronto" title="Yorkville, Toronto">
               Yorkville
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6R
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Parkdale,_Toronto" title="Parkdale, Toronto">
               Parkdale
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6R
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Roncesvalles,_Toronto" title="Roncesvalles, Toronto">
               Roncesvalles
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M7R
             </td>
             <td>
              Mississauga
             </td>
             <td>
              Canada Post Gateway Processing Centre
             </td>
            </tr>
            <tr>
             <td>
              M8R
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9R
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/Kingsview_Village" title="Kingsview Village">
               Kingsview Village
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9R
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Martin Grove Gardens
             </td>
            </tr>
            <tr>
             <td>
              M9R
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Richview Gardens
             </td>
            </tr>
            <tr>
             <td>
              M9R
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              St. Phillips
             </td>
            </tr>
            <tr>
             <td>
              M1S
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Agincourt,_Toronto" title="Agincourt, Toronto">
               Agincourt
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2S
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M3S
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M4S
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              Davisville
             </td>
            </tr>
            <tr>
             <td>
              M5S
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Harbord
             </td>
            </tr>
            <tr>
             <td>
              M5S
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/University_of_Toronto" title="University of Toronto">
               University of Toronto
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6S
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Runnymede,_Toronto" title="Runnymede, Toronto">
               Runnymede
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6S
             </td>
             <td>
              <a href="/wiki/West_Toronto" title="West Toronto">
               West Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Swansea,_Toronto" title="Swansea, Toronto">
               Swansea
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M7S
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8S
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9S
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M1T
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              Clarks Corners
             </td>
            </tr>
            <tr>
             <td>
              M1T
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              Sullivan
             </td>
            </tr>
            <tr>
             <td>
              M1T
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Tam_O%27Shanter_%E2%80%93_Sullivan" title="Tam O'Shanter – Sullivan">
               Tam O'Shanter
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2T
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M3T
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M4T
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Moore_Park,_Toronto" title="Moore Park, Toronto">
               Moore Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M4T
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              Summerhill East
             </td>
            </tr>
            <tr>
             <td>
              M5T
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Chinatown,_Toronto" title="Chinatown, Toronto">
               Chinatown
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5T
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Grange_Park_(Toronto)" title="Grange Park (Toronto)">
               Grange Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5T
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Kensington_Market" title="Kensington Market">
               Kensington Market
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6T
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M7T
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8T
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M9T
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M1V
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Agincourt_North" title="Agincourt North">
               Agincourt North
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1V
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              L'Amoreaux East
             </td>
            </tr>
            <tr>
             <td>
              M1V
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a href="/wiki/Milliken,_Ontario" title="Milliken, Ontario">
               Milliken
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1V
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              Steeles East
             </td>
            </tr>
            <tr>
             <td>
              M2V
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M3V
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M4V
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Deer_Park,_Toronto" title="Deer Park, Toronto">
               Deer Park
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M4V
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              Forest Hill SE
             </td>
            </tr>
            <tr>
             <td>
              M4V
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Rathnelly" title="Rathnelly">
               Rathnelly
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M4V
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/South_Hill,_Toronto" title="South Hill, Toronto">
               South Hill
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M4V
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">
               Central Toronto
              </a>
             </td>
             <td>
              Summerhill West
             </td>
            </tr>
            <tr>
             <td>
              M5V
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/CN_Tower" title="CN Tower">
               CN Tower
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5V
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Bathurst Quay
             </td>
            </tr>
            <tr>
             <td>
              M5V
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Island airport
             </td>
            </tr>
            <tr>
             <td>
              M5V
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Harbourfront West
             </td>
            </tr>
            <tr>
             <td>
              M5V
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/King_and_Spadina" title="King and Spadina">
               King and Spadina
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5V
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Railway_Lands" title="Railway Lands">
               Railway Lands
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5V
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/South_Niagara" title="South Niagara">
               South Niagara
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6V
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M7V
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8V
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Humber Bay Shores
             </td>
            </tr>
            <tr>
             <td>
              M8V
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Mimico South
             </td>
            </tr>
            <tr>
             <td>
              M8V
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/New_Toronto" title="New Toronto">
               New Toronto
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9V
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Albion Gardens
             </td>
            </tr>
            <tr>
             <td>
              M9V
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Beaumond_Heights" title="Beaumond Heights">
               Beaumond Heights
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9V
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Humbergate
             </td>
            </tr>
            <tr>
             <td>
              M9V
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Mount_Olive-Silverstone-Jamestown" title="Mount Olive-Silverstone-Jamestown">
               Jamestown
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9V
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Mount_Olive-Silverstone-Jamestown" title="Mount Olive-Silverstone-Jamestown">
               Mount Olive
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9V
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Silverstone,_Toronto" title="Silverstone, Toronto">
               Silverstone
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9V
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/South_Steeles" title="South Steeles">
               South Steeles
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9V
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/Thistletown" title="Thistletown">
               Thistletown
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M1W
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              L'Amoreaux West
             </td>
            </tr>
            <tr>
             <td>
              M2W
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M3W
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M4W
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Rosedale,_Toronto" title="Rosedale, Toronto">
               Rosedale
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5W
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              Stn A PO Boxes 25 The Esplanade
             </td>
            </tr>
            <tr>
             <td>
              M6W
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M7W
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8W
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/Alderwood,_Toronto" title="Alderwood, Toronto">
               Alderwood
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M8W
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/Long_Branch,_Toronto" title="Long Branch, Toronto">
               Long Branch
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9W
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Northwest
             </td>
            </tr>
            <tr>
             <td>
              M1X
             </td>
             <td>
              <a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">
               Scarborough
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Upper_Rouge" title="Upper Rouge">
               Upper Rouge
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M2X
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M3X
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M4X
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Cabbagetown,_Toronto" title="Cabbagetown, Toronto">
               Cabbagetown
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M4X
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/St._James_Town" title="St. James Town">
               St. James Town
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5X
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/First_Canadian_Place" title="First Canadian Place">
               First Canadian Place
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5X
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Underground_city" title="Underground city">
               Underground city
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M6X
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M7X
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8X
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/The_Kingsway" title="The Kingsway">
               The Kingsway
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M8X
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Montgomery Road
             </td>
            </tr>
            <tr>
             <td>
              M8X
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Old Mill North
             </td>
            </tr>
            <tr>
             <td>
              M9X
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M1Y
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M2Y
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M3Y
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M4Y
             </td>
             <td>
              <a href="/wiki/Downtown_Toronto" title="Downtown Toronto">
               Downtown Toronto
              </a>
             </td>
             <td>
              <a href="/wiki/Church_and_Wellesley" title="Church and Wellesley">
               Church and Wellesley
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M5Y
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M6Y
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M7Y
             </td>
             <td>
              <a href="/wiki/East_Toronto" title="East Toronto">
               East Toronto
              </a>
             </td>
             <td>
              Business Reply Mail Processing Centre 969 Eastern
             </td>
            </tr>
            <tr>
             <td>
              M8Y
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/Humber_Bay" title="Humber Bay">
               Humber Bay
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M8Y
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              King's Mill Park
             </td>
            </tr>
            <tr>
             <td>
              M8Y
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Kingsway Park South East
             </td>
            </tr>
            <tr>
             <td>
              M8Y
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/Mimico" title="Mimico">
               Mimico NE
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M8Y
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/Old_Mill,_Toronto" title="Old Mill, Toronto">
               Old Mill South
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M8Y
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/The_Queensway" title="The Queensway">
               The Queensway East
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M8Y
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Fairmont_Royal_York_Hotel" title="Fairmont Royal York Hotel">
               Royal York South East
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M8Y
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a class="mw-redirect" href="/wiki/Sunnylea" title="Sunnylea">
               Sunnylea
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M9Y
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M1Z
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M2Z
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M3Z
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M4Z
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M5Z
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M6Z
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M7Z
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
            <tr>
             <td>
              M8Z
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Kingsway Park South West
             </td>
            </tr>
            <tr>
             <td>
              M8Z
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/Mimico" title="Mimico">
               Mimico NW
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M8Z
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              <a href="/wiki/The_Queensway" title="The Queensway">
               The Queensway West
              </a>
             </td>
            </tr>
            <tr>
             <td>
              M8Z
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              Royal York South West
             </td>
            </tr>
            <tr>
             <td>
              M8Z
             </td>
             <td>
              <a href="/wiki/Etobicoke" title="Etobicoke">
               Etobicoke
              </a>
             </td>
             <td>
              South of Bloor
             </td>
            </tr>
            <tr>
             <td>
              M9Z
             </td>
             <td>
              Not assigned
             </td>
             <td>
              Not assigned
             </td>
            </tr>
           </tbody>
          </table>
          <div>
           <table class="multicol" role="presentation" style="border-collapse: collapse; padding: 0; border: 0; background:transparent; width:100%;">
           </table>
           <h2>
            <span id="Most_populated_FSAs.5B3.5D">
            </span>
            <span class="mw-headline" id="Most_populated_FSAs[3]">
             Most populated FSAs
             <sup class="reference" id="cite_ref-statcan_3-0">
              <a href="#cite_note-statcan-3">
               [3]
              </a>
             </sup>
            </span>
            <span class="mw-editsection">
             <span class="mw-editsection-bracket">
              [
             </span>
             <a href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=edit&amp;section=2" title="Edit section: Most populated FSAs[3]">
              edit
             </a>
             <span class="mw-editsection-bracket">
              ]
             </span>
            </span>
           </h2>
           <ol>
            <li>
             M1B, 65,129
            </li>
            <li>
             M2N, 60,124
            </li>
            <li>
             M1V, 55,250
            </li>
            <li>
             M9V, 55,159
            </li>
            <li>
             M2J, 54,391
            </li>
           </ol>
           <p>
           </p>
           <table cellpadding="2" cellspacing="0" rules="all" style="width:100%; border-collapse:collapse; border:1px solid #ccc;">
            <tbody>
             <tr>
              <td>
              </td>
             </tr>
            </tbody>
           </table>
          </div>
          <p>
          </p>
          <h2>
           <span id="Least_populated_FSAs.5B3.5D">
           </span>
           <span class="mw-headline" id="Least_populated_FSAs[3]">
            Least populated FSAs
            <sup class="reference" id="cite_ref-statcan_3-1">
             <a href="#cite_note-statcan-3">
              [3]
             </a>
            </sup>
           </span>
           <span class="mw-editsection">
            <span class="mw-editsection-bracket">
             [
            </span>
            <a href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=edit&amp;section=3" title="Edit section: Least populated FSAs[3]">
             edit
            </a>
            <span class="mw-editsection-bracket">
             ]
            </span>
           </span>
          </h2>
          <ol>
           <li>
            M5K, 5
           </li>
           <li>
            M5L, 5
           </li>
           <li>
            M5W, 5
           </li>
           <li>
            M5X, 5
           </li>
           <li>
            M7A, 5
           </li>
          </ol>
          <p>
          </p>
          <h2>
           <span class="mw-headline" id="References">
            References
           </span>
           <span class="mw-editsection">
            <span class="mw-editsection-bracket">
             [
            </span>
            <a href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=edit&amp;section=4" title="Edit section: References">
             edit
            </a>
            <span class="mw-editsection-bracket">
             ]
            </span>
           </span>
          </h2>
          <div class="mw-references-wrap">
           <ol class="references">
            <li id="cite_note-1">
             <span class="mw-cite-backlink">
              <b>
               <a href="#cite_ref-1">
                ^
               </a>
              </b>
             </span>
             <span class="reference-text">
              <cite class="citation web">
               Canada Post.
               <a class="external text" href="https://www.canadapost.ca/cpotools/apps/fpc/personal/findByCity?execution=e2s1" rel="nofollow">
                "Canada Post - Find a Postal Code"
               </a>
               <span class="reference-accessdate">
                . Retrieved
                <span class="nowrap">
                 9 November
                </span>
                2008
               </span>
               .
              </cite>
              <span class="Z3988" title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Canada+Post+-+Find+a+Postal+Code&amp;rft.au=Canada+Post&amp;rft_id=https%3A%2F%2Fwww.canadapost.ca%2Fcpotools%2Fapps%2Ffpc%2Fpersonal%2FfindByCity%3Fexecution%3De2s1&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+postal+codes+of+Canada%3A+M">
              </span>
              <style data-mw-deduplicate="TemplateStyles:r886058088">
               .mw-parser-output cite.citation{font-style:inherit}.mw-parser-output .citation q{quotes:"\"""\"""'""'"}.mw-parser-output .citation .cs1-lock-free a{background:url("//upload.wikimedia.org/wikipedia/commons/thumb/6/65/Lock-green.svg/9px-Lock-green.svg.png")no-repeat;background-position:right .1em center}.mw-parser-output .citation .cs1-lock-limited a,.mw-parser-output .citation .cs1-lock-registration a{background:url("//upload.wikimedia.org/wikipedia/commons/thumb/d/d6/Lock-gray-alt-2.svg/9px-Lock-gray-alt-2.svg.png")no-repeat;background-position:right .1em center}.mw-parser-output .citation .cs1-lock-subscription a{background:url("//upload.wikimedia.org/wikipedia/commons/thumb/a/aa/Lock-red-alt-2.svg/9px-Lock-red-alt-2.svg.png")no-repeat;background-position:right .1em center}.mw-parser-output .cs1-subscription,.mw-parser-output .cs1-registration{color:#555}.mw-parser-output .cs1-subscription span,.mw-parser-output .cs1-registration span{border-bottom:1px dotted;cursor:help}.mw-parser-output .cs1-ws-icon a{background:url("//upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Wikisource-logo.svg/12px-Wikisource-logo.svg.png")no-repeat;background-position:right .1em center}.mw-parser-output code.cs1-code{color:inherit;background:inherit;border:inherit;padding:inherit}.mw-parser-output .cs1-hidden-error{display:none;font-size:100%}.mw-parser-output .cs1-visible-error{font-size:100%}.mw-parser-output .cs1-maint{display:none;color:#33aa33;margin-left:0.3em}.mw-parser-output .cs1-subscription,.mw-parser-output .cs1-registration,.mw-parser-output .cs1-format{font-size:95%}.mw-parser-output .cs1-kern-left,.mw-parser-output .cs1-kern-wl-left{padding-left:0.2em}.mw-parser-output .cs1-kern-right,.mw-parser-output .cs1-kern-wl-right{padding-right:0.2em}
              </style>
             </span>
            </li>
            <li id="cite_note-2">
             <span class="mw-cite-backlink">
              <b>
               <a href="#cite_ref-2">
                ^
               </a>
              </b>
             </span>
             <span class="reference-text">
              <cite class="citation web">
               <a class="external text" href="https://web.archive.org/web/20110519093024/http://www.canadapost.ca/cpo/mc/personal/tools/mobileapp/default.jsf" rel="nofollow">
                "Mobile Apps"
               </a>
               . Canada Post. Archived from
               <a class="external text" href="http://www.canadapost.ca/cpo/mc/personal/tools/mobileapp/default.jsf" rel="nofollow">
                the original
               </a>
               on 2011-05-19.
              </cite>
              <span class="Z3988" title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Mobile+Apps&amp;rft.pub=Canada+Post&amp;rft_id=http%3A%2F%2Fwww.canadapost.ca%2Fcpo%2Fmc%2Fpersonal%2Ftools%2Fmobileapp%2Fdefault.jsf&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+postal+codes+of+Canada%3A+M">
              </span>
              <link href="mw-data:TemplateStyles:r886058088" rel="mw-deduplicated-inline-style"/>
             </span>
            </li>
            <li id="cite_note-statcan-3">
             <span class="mw-cite-backlink">
              ^
              <a href="#cite_ref-statcan_3-0">
               <sup>
                <i>
                 <b>
                  a
                 </b>
                </i>
               </sup>
              </a>
              <a href="#cite_ref-statcan_3-1">
               <sup>
                <i>
                 <b>
                  b
                 </b>
                </i>
               </sup>
              </a>
             </span>
             <span class="reference-text">
              <cite class="citation web">
               <a class="external text" href="http://www12.statcan.ca/english/census06/data/popdwell/Table.cfm?T=1201&amp;SR=1&amp;S=0&amp;O=A&amp;RPP=9999&amp;PR=0&amp;CMA=0" rel="nofollow">
                "2006 Census of Population"
               </a>
               . 15 October 2008.
              </cite>
              <span class="Z3988" title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=2006+Census+of+Population&amp;rft.date=2008-10-15&amp;rft_id=http%3A%2F%2Fwww12.statcan.ca%2Fenglish%2Fcensus06%2Fdata%2Fpopdwell%2FTable.cfm%3FT%3D1201%26SR%3D1%26S%3D0%26O%3DA%26RPP%3D9999%26PR%3D0%26CMA%3D0&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+postal+codes+of+Canada%3A+M">
              </span>
              <link href="mw-data:TemplateStyles:r886058088" rel="mw-deduplicated-inline-style"/>
             </span>
            </li>
           </ol>
          </div>
          <table class="navbox">
           <tbody>
            <tr>
             <td style="width:36px; text-align:center">
              <a class="image" href="/wiki/File:Flag_of_Canada.svg" title="Flag of Canada">
               <img alt="Flag of Canada" data-file-height="600" data-file-width="1200" decoding="async" height="18" src="//upload.wikimedia.org/wikipedia/en/thumb/c/cf/Flag_of_Canada.svg/36px-Flag_of_Canada.svg.png" srcset="//upload.wikimedia.org/wikipedia/en/thumb/c/cf/Flag_of_Canada.svg/54px-Flag_of_Canada.svg.png 1.5x, //upload.wikimedia.org/wikipedia/en/thumb/c/cf/Flag_of_Canada.svg/72px-Flag_of_Canada.svg.png 2x" width="36"/>
              </a>
             </td>
             <th class="navbox-title" style="font-size:110%">
              <a href="/wiki/Postal_codes_in_Canada" title="Postal codes in Canada">
               Canadian postal codes
              </a>
             </th>
             <td style="width:36px; text-align:center">
              <a class="image" href="/wiki/File:Canadian_postal_district_map_(without_legends).svg">
               <img alt="Canadian postal district map (without legends).svg" data-file-height="846" data-file-width="1000" decoding="async" height="18" src="//upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Canadian_postal_district_map_%28without_legends%29.svg/21px-Canadian_postal_district_map_%28without_legends%29.svg.png" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Canadian_postal_district_map_%28without_legends%29.svg/32px-Canadian_postal_district_map_%28without_legends%29.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Canadian_postal_district_map_%28without_legends%29.svg/43px-Canadian_postal_district_map_%28without_legends%29.svg.png 2x" width="21"/>
              </a>
             </td>
            </tr>
            <tr>
             <td colspan="3" style="text-align:center; font-size: 100%;">
              <table cellspacing="0" style="background-color: #F8F8F8;" width="100%">
               <tbody>
                <tr>
                 <td style="text-align:center; border:1px solid #aaa;">
                  <a href="/wiki/Newfoundland_and_Labrador" title="Newfoundland and Labrador">
                   NL
                  </a>
                 </td>
                 <td style="text-align:center; border:1px solid #aaa;">
                  <a href="/wiki/Nova_Scotia" title="Nova Scotia">
                   NS
                  </a>
                 </td>
                 <td style="text-align:center; border:1px solid #aaa;">
                  <a href="/wiki/Prince_Edward_Island" title="Prince Edward Island">
                   PE
                  </a>
                 </td>
                 <td style="text-align:center; border:1px solid #aaa;">
                  <a href="/wiki/New_Brunswick" title="New Brunswick">
                   NB
                  </a>
                 </td>
                 <td colspan="3" style="text-align:center; border:1px solid #aaa;">
                  <a href="/wiki/Quebec" title="Quebec">
                   QC
                  </a>
                 </td>
                 <td colspan="5" style="text-align:center; border:1px solid #aaa;">
                  <a href="/wiki/Ontario" title="Ontario">
                   ON
                  </a>
                 </td>
                 <td style="text-align:center; border:1px solid #aaa;">
                  <a href="/wiki/Manitoba" title="Manitoba">
                   MB
                  </a>
                 </td>
                 <td style="text-align:center; border:1px solid #aaa;">
                  <a href="/wiki/Saskatchewan" title="Saskatchewan">
                   SK
                  </a>
                 </td>
                 <td style="text-align:center; border:1px solid #aaa;">
                  <a href="/wiki/Alberta" title="Alberta">
                   AB
                  </a>
                 </td>
                 <td style="text-align:center; border:1px solid #aaa;">
                  <a href="/wiki/British_Columbia" title="British Columbia">
                   BC
                  </a>
                 </td>
                 <td style="text-align:center; border:1px solid #aaa;">
                  <a href="/wiki/Nunavut" title="Nunavut">
                   NU
                  </a>
                  /
                  <a href="/wiki/Northwest_Territories" title="Northwest Territories">
                   NT
                  </a>
                 </td>
                 <td style="text-align:center; border:1px solid #aaa;">
                  <a href="/wiki/Yukon" title="Yukon">
                   YT
                  </a>
                 </td>
                </tr>
                <tr>
                 <td align="center" style="border: 1px solid #FF0000; background-color: #FFE0E0; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_A" title="List of postal codes of Canada: A">
                   A
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #FF4000; background-color: #FFE8E0; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_B" title="List of postal codes of Canada: B">
                   B
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #FF8000; background-color: #FFF0E0; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_C" title="List of postal codes of Canada: C">
                   C
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #FFC000; background-color: #FFF8E0; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_E" title="List of postal codes of Canada: E">
                   E
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #FFFF00; background-color: #FFFFE0; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_G" title="List of postal codes of Canada: G">
                   G
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #C0FF00; background-color: #F8FFE0; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_H" title="List of postal codes of Canada: H">
                   H
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #80FF00; background-color: #F0FFE0; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_J" title="List of postal codes of Canada: J">
                   J
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #00FF00; background-color: #E0FFE0; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_K" title="List of postal codes of Canada: K">
                   K
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #00FF80; background-color: #E0FFF0; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_L" title="List of postal codes of Canada: L">
                   L
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #E0FFF8; background-color: #00FFC0; font-size: 135%; color: black;" width="5%">
                  <a class="mw-selflink selflink">
                   M
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #00FFE0; background-color: #E0FFFC; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_N" title="List of postal codes of Canada: N">
                   N
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #00FFFF; background-color: #E0FFFF; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_P" title="List of postal codes of Canada: P">
                   P
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #00C0FF; background-color: #E0F8FF; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_R" title="List of postal codes of Canada: R">
                   R
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #0080FF; background-color: #E0F0FF; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_S" title="List of postal codes of Canada: S">
                   S
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #0040FF; background-color: #E0E8FF; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_T" title="List of postal codes of Canada: T">
                   T
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #0000FF; background-color: #E0E0FF; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_V" title="List of postal codes of Canada: V">
                   V
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #A000FF; background-color: #E8E0FF; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_X" title="List of postal codes of Canada: X">
                   X
                  </a>
                 </td>
                 <td align="center" style="border: 1px solid #FF00FF; background-color: #FFE0FF; font-size: 135%;" width="5%">
                  <a href="/wiki/List_of_postal_codes_of_Canada:_Y" title="List of postal codes of Canada: Y">
                   Y
                  </a>
                 </td>
                </tr>
               </tbody>
              </table>
             </td>
            </tr>
           </tbody>
          </table>
          <!-- 
    NewPP limit report
    Parsed by mw1265
    Cached time: 20191013031038
    Cache expiry: 2592000
    Dynamic content: false
    Complications: [vary‐revision‐sha1]
    CPU time usage: 0.156 seconds
    Real time usage: 0.193 seconds
    Preprocessor visited node count: 574/1000000
    Preprocessor generated node count: 0/1500000
    Post‐expand include size: 10232/2097152 bytes
    Template argument size: 13/2097152 bytes
    Highest expansion depth: 5/40
    Expensive parser function count: 0/500
    Unstrip recursion depth: 1/20
    Unstrip post‐expand size: 9025/5000000 bytes
    Number of Wikibase entities loaded: 0/400
    Lua time usage: 0.049/10.000 seconds
    Lua memory usage: 1.75 MB/50 MB
    -->
          <!--
    Transclusion expansion time report (%,ms,calls,template)
    100.00%  108.387      1 -total
     71.89%   77.915      3 Template:Cite_web
     13.42%   14.549      1 Template:Col-2
     11.73%   12.711      1 Template:Col-break
      4.01%    4.349      1 Template:Canadian_postal_codes
      2.99%    3.236      1 Template:Col-begin
      2.37%    2.568      2 Template:Col-end
    -->
          <!-- Saved in parser cache with key enwiki:pcache:idhash:539066-0!canonical and timestamp 20191013031038 and revision id 920980179
     -->
         </div>
         <noscript>
          <img alt="" height="1" src="//en.wikipedia.org/wiki/Special:CentralAutoLogin/start?type=1x1" style="border: none; position: absolute;" title="" width="1"/>
         </noscript>
        </div>
        <div class="printfooter">
         Retrieved from "
         <a dir="ltr" href="https://en.wikipedia.org/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;oldid=920980179">
          https://en.wikipedia.org/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;oldid=920980179
         </a>
         "
        </div>
        <div class="catlinks" data-mw="interface" id="catlinks">
         <div class="mw-normal-catlinks" id="mw-normal-catlinks">
          <a href="/wiki/Help:Category" title="Help:Category">
           Categories
          </a>
          :
          <ul>
           <li>
            <a href="/wiki/Category:Communications_in_Ontario" title="Category:Communications in Ontario">
             Communications in Ontario
            </a>
           </li>
           <li>
            <a href="/wiki/Category:Postal_codes_in_Canada" title="Category:Postal codes in Canada">
             Postal codes in Canada
            </a>
           </li>
           <li>
            <a href="/wiki/Category:Toronto" title="Category:Toronto">
             Toronto
            </a>
           </li>
           <li>
            <a href="/wiki/Category:Ontario-related_lists" title="Category:Ontario-related lists">
             Ontario-related lists
            </a>
           </li>
          </ul>
         </div>
        </div>
        <div class="visualClear">
        </div>
       </div>
      </div>
      <div id="mw-data-after-content">
       <div class="read-more-container">
       </div>
      </div>
      <div id="mw-navigation">
       <h2>
        Navigation menu
       </h2>
       <div id="mw-head">
        <div aria-labelledby="p-personal-label" id="p-personal" role="navigation">
         <h3 id="p-personal-label">
          Personal tools
         </h3>
         <ul>
          <li id="pt-anonuserpage">
           Not logged in
          </li>
          <li id="pt-anontalk">
           <a accesskey="n" href="/wiki/Special:MyTalk" title="Discussion about edits from this IP address [n]">
            Talk
           </a>
          </li>
          <li id="pt-anoncontribs">
           <a accesskey="y" href="/wiki/Special:MyContributions" title="A list of edits made from this IP address [y]">
            Contributions
           </a>
          </li>
          <li id="pt-createaccount">
           <a href="/w/index.php?title=Special:CreateAccount&amp;returnto=List+of+postal+codes+of+Canada%3A+M" title="You are encouraged to create an account and log in; however, it is not mandatory">
            Create account
           </a>
          </li>
          <li id="pt-login">
           <a accesskey="o" href="/w/index.php?title=Special:UserLogin&amp;returnto=List+of+postal+codes+of+Canada%3A+M" title="You're encouraged to log in; however, it's not mandatory. [o]">
            Log in
           </a>
          </li>
         </ul>
        </div>
        <div id="left-navigation">
         <div aria-labelledby="p-namespaces-label" class="vectorTabs" id="p-namespaces" role="navigation">
          <h3 id="p-namespaces-label">
           Namespaces
          </h3>
          <ul>
           <li class="selected" id="ca-nstab-main">
            <span>
             <a accesskey="c" href="/wiki/List_of_postal_codes_of_Canada:_M" title="View the content page [c]">
              Article
             </a>
            </span>
           </li>
           <li id="ca-talk">
            <span>
             <a accesskey="t" href="/wiki/Talk:List_of_postal_codes_of_Canada:_M" rel="discussion" title="Discussion about the content page [t]">
              Talk
             </a>
            </span>
           </li>
          </ul>
         </div>
         <div aria-labelledby="p-variants-label" class="vectorMenu emptyPortlet" id="p-variants" role="navigation">
          <input aria-labelledby="p-variants-label" class="vectorMenuCheckbox" type="checkbox"/>
          <h3 id="p-variants-label">
           <span>
            Variants
           </span>
          </h3>
          <ul class="menu">
          </ul>
         </div>
        </div>
        <div id="right-navigation">
         <div aria-labelledby="p-views-label" class="vectorTabs" id="p-views" role="navigation">
          <h3 id="p-views-label">
           Views
          </h3>
          <ul>
           <li class="collapsible selected" id="ca-view">
            <span>
             <a href="/wiki/List_of_postal_codes_of_Canada:_M">
              Read
             </a>
            </span>
           </li>
           <li class="collapsible" id="ca-edit">
            <span>
             <a accesskey="e" href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=edit" title="Edit this page [e]">
              Edit
             </a>
            </span>
           </li>
           <li class="collapsible" id="ca-history">
            <span>
             <a accesskey="h" href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=history" title="Past revisions of this page [h]">
              View history
             </a>
            </span>
           </li>
          </ul>
         </div>
         <div aria-labelledby="p-cactions-label" class="vectorMenu emptyPortlet" id="p-cactions" role="navigation">
          <input aria-labelledby="p-cactions-label" class="vectorMenuCheckbox" type="checkbox"/>
          <h3 id="p-cactions-label">
           <span>
            More
           </span>
          </h3>
          <ul class="menu">
          </ul>
         </div>
         <div id="p-search" role="search">
          <h3>
           <label for="searchInput">
            Search
           </label>
          </h3>
          <form action="/w/index.php" id="searchform">
           <div id="simpleSearch">
            <input accesskey="f" id="searchInput" name="search" placeholder="Search Wikipedia" title="Search Wikipedia [f]" type="search"/>
            <input name="title" type="hidden" value="Special:Search"/>
            <input class="searchButton mw-fallbackSearchButton" id="mw-searchButton" name="fulltext" title="Search Wikipedia for this text" type="submit" value="Search"/>
            <input class="searchButton" id="searchButton" name="go" title="Go to a page with this exact name if it exists" type="submit" value="Go"/>
           </div>
          </form>
         </div>
        </div>
       </div>
       <div id="mw-panel">
        <div id="p-logo" role="banner">
         <a class="mw-wiki-logo" href="/wiki/Main_Page" title="Visit the main page">
         </a>
        </div>
        <div aria-labelledby="p-navigation-label" class="portal" id="p-navigation" role="navigation">
         <h3 id="p-navigation-label">
          Navigation
         </h3>
         <div class="body">
          <ul>
           <li id="n-mainpage-description">
            <a accesskey="z" href="/wiki/Main_Page" title="Visit the main page [z]">
             Main page
            </a>
           </li>
           <li id="n-contents">
            <a href="/wiki/Portal:Contents" title="Guides to browsing Wikipedia">
             Contents
            </a>
           </li>
           <li id="n-featuredcontent">
            <a href="/wiki/Portal:Featured_content" title="Featured content – the best of Wikipedia">
             Featured content
            </a>
           </li>
           <li id="n-currentevents">
            <a href="/wiki/Portal:Current_events" title="Find background information on current events">
             Current events
            </a>
           </li>
           <li id="n-randompage">
            <a accesskey="x" href="/wiki/Special:Random" title="Load a random article [x]">
             Random article
            </a>
           </li>
           <li id="n-sitesupport">
            <a href="https://donate.wikimedia.org/wiki/Special:FundraiserRedirector?utm_source=donate&amp;utm_medium=sidebar&amp;utm_campaign=C13_en.wikipedia.org&amp;uselang=en" title="Support us">
             Donate to Wikipedia
            </a>
           </li>
           <li id="n-shoplink">
            <a href="//shop.wikimedia.org" title="Visit the Wikipedia store">
             Wikipedia store
            </a>
           </li>
          </ul>
         </div>
        </div>
        <div aria-labelledby="p-interaction-label" class="portal" id="p-interaction" role="navigation">
         <h3 id="p-interaction-label">
          Interaction
         </h3>
         <div class="body">
          <ul>
           <li id="n-help">
            <a href="/wiki/Help:Contents" title="Guidance on how to use and edit Wikipedia">
             Help
            </a>
           </li>
           <li id="n-aboutsite">
            <a href="/wiki/Wikipedia:About" title="Find out about Wikipedia">
             About Wikipedia
            </a>
           </li>
           <li id="n-portal">
            <a href="/wiki/Wikipedia:Community_portal" title="About the project, what you can do, where to find things">
             Community portal
            </a>
           </li>
           <li id="n-recentchanges">
            <a accesskey="r" href="/wiki/Special:RecentChanges" title="A list of recent changes in the wiki [r]">
             Recent changes
            </a>
           </li>
           <li id="n-contactpage">
            <a href="//en.wikipedia.org/wiki/Wikipedia:Contact_us" title="How to contact Wikipedia">
             Contact page
            </a>
           </li>
          </ul>
         </div>
        </div>
        <div aria-labelledby="p-tb-label" class="portal" id="p-tb" role="navigation">
         <h3 id="p-tb-label">
          Tools
         </h3>
         <div class="body">
          <ul>
           <li id="t-whatlinkshere">
            <a accesskey="j" href="/wiki/Special:WhatLinksHere/List_of_postal_codes_of_Canada:_M" title="List of all English Wikipedia pages containing links to this page [j]">
             What links here
            </a>
           </li>
           <li id="t-recentchangeslinked">
            <a accesskey="k" href="/wiki/Special:RecentChangesLinked/List_of_postal_codes_of_Canada:_M" rel="nofollow" title="Recent changes in pages linked from this page [k]">
             Related changes
            </a>
           </li>
           <li id="t-upload">
            <a accesskey="u" href="/wiki/Wikipedia:File_Upload_Wizard" title="Upload files [u]">
             Upload file
            </a>
           </li>
           <li id="t-specialpages">
            <a accesskey="q" href="/wiki/Special:SpecialPages" title="A list of all special pages [q]">
             Special pages
            </a>
           </li>
           <li id="t-permalink">
            <a href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;oldid=920980179" title="Permanent link to this revision of the page">
             Permanent link
            </a>
           </li>
           <li id="t-info">
            <a href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=info" title="More information about this page">
             Page information
            </a>
           </li>
           <li id="t-wikibase">
            <a accesskey="g" href="https://www.wikidata.org/wiki/Special:EntityPage/Q3248240" title="Link to connected data repository item [g]">
             Wikidata item
            </a>
           </li>
           <li id="t-cite">
            <a href="/w/index.php?title=Special:CiteThisPage&amp;page=List_of_postal_codes_of_Canada%3A_M&amp;id=920980179" title="Information on how to cite this page">
             Cite this page
            </a>
           </li>
          </ul>
         </div>
        </div>
        <div aria-labelledby="p-coll-print_export-label" class="portal" id="p-coll-print_export" role="navigation">
         <h3 id="p-coll-print_export-label">
          Print/export
         </h3>
         <div class="body">
          <ul>
           <li id="coll-create_a_book">
            <a href="/w/index.php?title=Special:Book&amp;bookcmd=book_creator&amp;referer=List+of+postal+codes+of+Canada%3A+M">
             Create a book
            </a>
           </li>
           <li id="coll-download-as-rl">
            <a href="/w/index.php?title=Special:ElectronPdf&amp;page=List+of+postal+codes+of+Canada%3A+M&amp;action=show-download-screen">
             Download as PDF
            </a>
           </li>
           <li id="t-print">
            <a accesskey="p" href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;printable=yes" title="Printable version of this page [p]">
             Printable version
            </a>
           </li>
          </ul>
         </div>
        </div>
        <div aria-labelledby="p-lang-label" class="portal" id="p-lang" role="navigation">
         <h3 id="p-lang-label">
          Languages
         </h3>
         <div class="body">
          <ul>
           <li class="interlanguage-link interwiki-fr">
            <a class="interlanguage-link-target" href="https://fr.wikipedia.org/wiki/Liste_des_codes_postaux_canadiens_d%C3%A9butant_par_M" hreflang="fr" lang="fr" title="Liste des codes postaux canadiens débutant par M – French">
             Français
            </a>
           </li>
          </ul>
          <div class="after-portlet after-portlet-lang">
           <span class="wb-langlinks-edit wb-langlinks-link">
            <a class="wbc-editpage" href="https://www.wikidata.org/wiki/Special:EntityPage/Q3248240#sitelinks-wikipedia" title="Edit interlanguage links">
             Edit links
            </a>
           </span>
          </div>
         </div>
        </div>
       </div>
      </div>
      <div id="footer" role="contentinfo">
       <ul id="footer-info">
        <li id="footer-info-lastmod">
         This page was last edited on 13 October 2019, at 03:10
         <span class="anonymous-show">
          (UTC)
         </span>
         .
        </li>
        <li id="footer-info-copyright">
         Text is available under the
         <a href="//en.wikipedia.org/wiki/Wikipedia:Text_of_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License" rel="license">
          Creative Commons Attribution-ShareAlike License
         </a>
         <a href="//creativecommons.org/licenses/by-sa/3.0/" rel="license" style="display:none;">
         </a>
         ;
    additional terms may apply.  By using this site, you agree to the
         <a href="//foundation.wikimedia.org/wiki/Terms_of_Use">
          Terms of Use
         </a>
         and
         <a href="//foundation.wikimedia.org/wiki/Privacy_policy">
          Privacy Policy
         </a>
         . Wikipedia® is a registered trademark of the
         <a href="//www.wikimediafoundation.org/">
          Wikimedia Foundation, Inc.
         </a>
         , a non-profit organization.
        </li>
       </ul>
       <ul id="footer-places">
        <li id="footer-places-privacy">
         <a class="extiw" href="https://foundation.wikimedia.org/wiki/Privacy_policy" title="wmf:Privacy policy">
          Privacy policy
         </a>
        </li>
        <li id="footer-places-about">
         <a href="/wiki/Wikipedia:About" title="Wikipedia:About">
          About Wikipedia
         </a>
        </li>
        <li id="footer-places-disclaimer">
         <a href="/wiki/Wikipedia:General_disclaimer" title="Wikipedia:General disclaimer">
          Disclaimers
         </a>
        </li>
        <li id="footer-places-contact">
         <a href="//en.wikipedia.org/wiki/Wikipedia:Contact_us">
          Contact Wikipedia
         </a>
        </li>
        <li id="footer-places-developers">
         <a href="https://www.mediawiki.org/wiki/Special:MyLanguage/How_to_contribute">
          Developers
         </a>
        </li>
        <li id="footer-places-cookiestatement">
         <a href="https://foundation.wikimedia.org/wiki/Cookie_statement">
          Cookie statement
         </a>
        </li>
        <li id="footer-places-mobileview">
         <a class="noprint stopMobileRedirectToggle" href="//en.m.wikipedia.org/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;mobileaction=toggle_view_mobile">
          Mobile view
         </a>
        </li>
       </ul>
       <ul class="noprint" id="footer-icons">
        <li id="footer-copyrightico">
         <a href="https://wikimediafoundation.org/">
          <img alt="Wikimedia Foundation" height="31" src="/static/images/wikimedia-button.png" srcset="/static/images/wikimedia-button-1.5x.png 1.5x, /static/images/wikimedia-button-2x.png 2x" width="88"/>
         </a>
        </li>
        <li id="footer-poweredbyico">
         <a href="https://www.mediawiki.org/">
          <img alt="Powered by MediaWiki" height="31" src="/static/images/poweredby_mediawiki_88x31.png" srcset="/static/images/poweredby_mediawiki_132x47.png 1.5x, /static/images/poweredby_mediawiki_176x62.png 2x" width="88"/>
         </a>
        </li>
       </ul>
       <div style="clear: both;">
       </div>
      </div>
      <script>
       (RLQ=window.RLQ||[]).push(function(){mw.config.set({"wgPageParseReport":{"limitreport":{"cputime":"0.156","walltime":"0.193","ppvisitednodes":{"value":574,"limit":1000000},"ppgeneratednodes":{"value":0,"limit":1500000},"postexpandincludesize":{"value":10232,"limit":2097152},"templateargumentsize":{"value":13,"limit":2097152},"expansiondepth":{"value":5,"limit":40},"expensivefunctioncount":{"value":0,"limit":500},"unstrip-depth":{"value":1,"limit":20},"unstrip-size":{"value":9025,"limit":5000000},"entityaccesscount":{"value":0,"limit":400},"timingprofile":["100.00%  108.387      1 -total"," 71.89%   77.915      3 Template:Cite_web"," 13.42%   14.549      1 Template:Col-2"," 11.73%   12.711      1 Template:Col-break","  4.01%    4.349      1 Template:Canadian_postal_codes","  2.99%    3.236      1 Template:Col-begin","  2.37%    2.568      2 Template:Col-end"]},"scribunto":{"limitreport-timeusage":{"value":"0.049","limit":"10.000"},"limitreport-memusage":{"value":1834786,"limit":52428800}},"cachereport":{"origin":"mw1265","timestamp":"20191013031038","ttl":2592000,"transientcontent":false}}});});
      </script>
      <script type="application/ld+json">
       {"@context":"https:\/\/schema.org","@type":"Article","name":"List of postal codes of Canada: M","url":"https:\/\/en.wikipedia.org\/wiki\/List_of_postal_codes_of_Canada:_M","sameAs":"http:\/\/www.wikidata.org\/entity\/Q3248240","mainEntity":"http:\/\/www.wikidata.org\/entity\/Q3248240","author":{"@type":"Organization","name":"Contributors to Wikimedia projects"},"publisher":{"@type":"Organization","name":"Wikimedia Foundation, Inc.","logo":{"@type":"ImageObject","url":"https:\/\/www.wikimedia.org\/static\/images\/wmf-hor-googpub.png"}},"datePublished":"2004-03-20T10:02:13Z","dateModified":"2019-10-13T03:10:35Z","headline":"Wikimedia list article"}
      </script>
      <script>
       (RLQ=window.RLQ||[]).push(function(){mw.config.set({"wgBackendResponseTime":107,"wgHostname":"mw1275"});});
      </script>
     </body>
    </html>
    
    


```python
table_page=soup.find('div',class_='mw-parser-output')
print(table_page)
```

    <div class="mw-parser-output"><p>This is a list of <a href="/wiki/Postal_codes_in_Canada" title="Postal codes in Canada">postal codes in Canada</a> where the first letter is M. Postal codes beginning with M are located within the city of <a href="/wiki/Toronto" title="Toronto">Toronto</a> in the province of <a href="/wiki/Ontario" title="Ontario">Ontario</a>. Only the first three characters are listed, corresponding to the Forward Sortation Area.
    </p><p><a href="/wiki/Canada_Post" title="Canada Post">Canada Post</a> provides a free postal code look-up tool on its website,<sup class="reference" id="cite_ref-1"><a href="#cite_note-1">[1]</a></sup> via its <a href="/wiki/Mobile_app" title="Mobile app">applications</a> for such <a class="mw-redirect" href="/wiki/Smartphones" title="Smartphones">smartphones</a> as the <a href="/wiki/IPhone" title="IPhone">iPhone</a> and <a href="/wiki/BlackBerry" title="BlackBerry">BlackBerry</a>,<sup class="reference" id="cite_ref-2"><a href="#cite_note-2">[2]</a></sup>  and sells hard-copy directories and <a href="/wiki/CD-ROM" title="CD-ROM">CD-ROMs</a>. Many vendors also sell validation tools, which allow customers to properly match addresses and postal codes. Hard-copy directories can also be consulted in all post offices, and some libraries.
    </p>
    <h2><span class="mw-headline" id="Toronto_-_FSAs"><a href="/wiki/Toronto" title="Toronto">Toronto</a> - <a href="/wiki/Postal_codes_in_Canada#Forward_sortation_areas" title="Postal codes in Canada">FSAs</a></span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=edit&amp;section=1" title="Edit section: Toronto - FSAs">edit</a><span class="mw-editsection-bracket">]</span></span></h2>
    <p>Note: There are no rural FSAs in Toronto, hence no postal codes should start with M0, however, the postal code M0R 8T0 is assigned to an <a href="/wiki/Amazon_(company)" title="Amazon (company)">Amazon (company)</a> warehouse in Mississauga, suggesting that Canada Post may be allocating the M0 FSA for high volume addresses.
    </p>
    <table class="wikitable sortable">
    <tbody><tr>
    <th>Postcode</th>
    <th>Borough</th>
    <th>Neighbourhood
    </th></tr>
    <tr>
    <td>M1A</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M2A</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M3A</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Parkwoods" title="Parkwoods">Parkwoods</a>
    </td></tr>
    <tr>
    <td>M4A</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Victoria_Village" title="Victoria Village">Victoria Village</a>
    </td></tr>
    <tr>
    <td>M5A</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Harbourfront_(Toronto)" title="Harbourfront (Toronto)">Harbourfront</a>
    </td></tr>
    <tr>
    <td>M5A</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Regent_Park" title="Regent Park">Regent Park</a>
    </td></tr>
    <tr>
    <td>M6A</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Lawrence_Heights" title="Lawrence Heights">Lawrence Heights</a>
    </td></tr>
    <tr>
    <td>M6A</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Lawrence_Manor" title="Lawrence Manor">Lawrence Manor</a>
    </td></tr>
    <tr>
    <td>M7A</td>
    <td><a href="/wiki/Queen%27s_Park_(Toronto)" title="Queen's Park (Toronto)">Queen's Park</a></td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8A</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9A</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a class="mw-redirect" href="/wiki/Islington_Avenue" title="Islington Avenue">Islington Avenue</a>
    </td></tr>
    <tr>
    <td>M1B</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Rouge,_Toronto" title="Rouge, Toronto">Rouge</a>
    </td></tr>
    <tr>
    <td>M1B</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Malvern,_Toronto" title="Malvern, Toronto">Malvern</a>
    </td></tr>
    <tr>
    <td>M2B</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M3B</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Don Mills North
    </td></tr>
    <tr>
    <td>M4B</td>
    <td><a href="/wiki/East_York" title="East York">East York</a></td>
    <td><a class="mw-redirect" href="/wiki/Woodbine_Gardens" title="Woodbine Gardens">Woodbine Gardens</a>
    </td></tr>
    <tr>
    <td>M4B</td>
    <td><a href="/wiki/East_York" title="East York">East York</a></td>
    <td><a class="mw-redirect" href="/wiki/Parkview_Hill" title="Parkview Hill">Parkview Hill</a>
    </td></tr>
    <tr>
    <td>M5B</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Ryerson
    </td></tr>
    <tr>
    <td>M5B</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Garden District
    </td></tr>
    <tr>
    <td>M6B</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Glencairn
    </td></tr>
    <tr>
    <td>M7B</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8B</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9B</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Cloverdale
    </td></tr>
    <tr>
    <td>M9B</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a class="mw-redirect" href="/wiki/Islington,_Toronto" title="Islington, Toronto">Islington</a>
    </td></tr>
    <tr>
    <td>M9B</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Martin Grove
    </td></tr>
    <tr>
    <td>M9B</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/Princess_Gardens" title="Princess Gardens">Princess Gardens</a>
    </td></tr>
    <tr>
    <td>M9B</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a class="mw-redirect" href="/wiki/West_Deane_Park" title="West Deane Park">West Deane Park</a>
    </td></tr>
    <tr>
    <td>M1C</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Highland_Creek_(Toronto)" title="Highland Creek (Toronto)">Highland Creek</a>
    </td></tr>
    <tr>
    <td>M1C</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a class="mw-redirect" href="/wiki/Rouge_Hill" title="Rouge Hill">Rouge Hill</a>
    </td></tr>
    <tr>
    <td>M1C</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Port_Union,_Toronto" title="Port Union, Toronto">Port Union</a>
    </td></tr>
    <tr>
    <td>M2C</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M3C</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Flemingdon_Park" title="Flemingdon Park">Flemingdon Park</a>
    </td></tr>
    <tr>
    <td>M3C</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Don Mills South
    </td></tr>
    <tr>
    <td>M4C</td>
    <td><a href="/wiki/East_York" title="East York">East York</a></td>
    <td><a class="mw-redirect" href="/wiki/Woodbine_Heights" title="Woodbine Heights">Woodbine Heights</a>
    </td></tr>
    <tr>
    <td>M5C</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/St._James_Town" title="St. James Town">St. James Town</a>
    </td></tr>
    <tr>
    <td>M6C</td>
    <td>York</td>
    <td><a class="mw-redirect" href="/wiki/Humewood-Cedarvale" title="Humewood-Cedarvale">Humewood-Cedarvale</a>
    </td></tr>
    <tr>
    <td>M7C</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8C</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9C</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Bloordale Gardens
    </td></tr>
    <tr>
    <td>M9C</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Eringate
    </td></tr>
    <tr>
    <td>M9C</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/Markland_Wood" title="Markland Wood">Markland Wood</a>
    </td></tr>
    <tr>
    <td>M9C</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Old Burnhamthorpe
    </td></tr>
    <tr>
    <td>M1E</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td>Guildwood
    </td></tr>
    <tr>
    <td>M1E</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Morningside,_Toronto" title="Morningside, Toronto">Morningside</a>
    </td></tr>
    <tr>
    <td>M1E</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/West_Hill,_Toronto" title="West Hill, Toronto">West Hill</a>
    </td></tr>
    <tr>
    <td>M2E</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M3E</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M4E</td>
    <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>
    <td><a href="/wiki/The_Beaches" title="The Beaches">The Beaches</a>
    </td></tr>
    <tr>
    <td>M5E</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Berczy_Park" title="Berczy Park">Berczy Park</a>
    </td></tr>
    <tr>
    <td>M6E</td>
    <td>York</td>
    <td>Caledonia-Fairbanks
    </td></tr>
    <tr>
    <td>M7E</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8E</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9E</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M1G</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Woburn,_Toronto" title="Woburn, Toronto">Woburn</a>
    </td></tr>
    <tr>
    <td>M2G</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M3G</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M4G</td>
    <td><a href="/wiki/East_York" title="East York">East York</a></td>
    <td><a href="/wiki/Leaside" title="Leaside">Leaside</a>
    </td></tr>
    <tr>
    <td>M5G</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Central Bay Street
    </td></tr>
    <tr>
    <td>M6G</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Christie
    </td></tr>
    <tr>
    <td>M7G</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8G</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9G</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M1H</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td>Cedarbrae
    </td></tr>
    <tr>
    <td>M2H</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Hillcrest_Village" title="Hillcrest Village">Hillcrest Village</a>
    </td></tr>
    <tr>
    <td>M3H</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Bathurst_Manor" title="Bathurst Manor">Bathurst Manor</a>
    </td></tr>
    <tr>
    <td>M3H</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Downsview North
    </td></tr>
    <tr>
    <td>M3H</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a class="mw-redirect" href="/wiki/Wilson_Heights,_Toronto" title="Wilson Heights, Toronto">Wilson Heights</a>
    </td></tr>
    <tr>
    <td>M4H</td>
    <td><a href="/wiki/East_York" title="East York">East York</a></td>
    <td><a href="/wiki/Thorncliffe_Park" title="Thorncliffe Park">Thorncliffe Park</a>
    </td></tr>
    <tr>
    <td>M5H</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Adelaide
    </td></tr>
    <tr>
    <td>M5H</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>King
    </td></tr>
    <tr>
    <td>M5H</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Richmond
    </td></tr>
    <tr>
    <td>M6H</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td><a class="mw-redirect" href="/wiki/Dovercourt_Village" title="Dovercourt Village">Dovercourt Village</a>
    </td></tr>
    <tr>
    <td>M6H</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td>Dufferin
    </td></tr>
    <tr>
    <td>M7H</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8H</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9H</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M1J</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Scarborough_Village" title="Scarborough Village">Scarborough Village</a>
    </td></tr>
    <tr>
    <td>M2J</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Fairview
    </td></tr>
    <tr>
    <td>M2J</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Henry_Farm" title="Henry Farm">Henry Farm</a>
    </td></tr>
    <tr>
    <td>M2J</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Oriole
    </td></tr>
    <tr>
    <td>M3J</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a class="mw-redirect" href="/wiki/Northwood_Park" title="Northwood Park">Northwood Park</a>
    </td></tr>
    <tr>
    <td>M3J</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/York_University" title="York University">York University</a>
    </td></tr>
    <tr>
    <td>M4J</td>
    <td><a href="/wiki/East_York" title="East York">East York</a></td>
    <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a>
    </td></tr>
    <tr>
    <td>M5J</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Harbourfront East
    </td></tr>
    <tr>
    <td>M5J</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Toronto_Islands" title="Toronto Islands">Toronto Islands</a>
    </td></tr>
    <tr>
    <td>M5J</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Union_Station_(Toronto)" title="Union Station (Toronto)">Union Station</a>
    </td></tr>
    <tr>
    <td>M6J</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td><a href="/wiki/Little_Portugal,_Toronto" title="Little Portugal, Toronto">Little Portugal</a>
    </td></tr>
    <tr>
    <td>M6J</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td><a href="/wiki/Trinity%E2%80%93Bellwoods" title="Trinity–Bellwoods">Trinity</a>
    </td></tr>
    <tr>
    <td>M7J</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8J</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9J</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M1K</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td>East Birchmount Park
    </td></tr>
    <tr>
    <td>M1K</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Ionview" title="Ionview">Ionview</a>
    </td></tr>
    <tr>
    <td>M1K</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a class="mw-redirect" href="/wiki/Kennedy_Park,_Toronto" title="Kennedy Park, Toronto">Kennedy Park</a>
    </td></tr>
    <tr>
    <td>M2K</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Bayview_Village" title="Bayview Village">Bayview Village</a>
    </td></tr>
    <tr>
    <td>M3K</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/CFB_Toronto" title="CFB Toronto">CFB Toronto</a>
    </td></tr>
    <tr>
    <td>M3K</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Downsview East
    </td></tr>
    <tr>
    <td>M4K</td>
    <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>
    <td>The Danforth West
    </td></tr>
    <tr>
    <td>M4K</td>
    <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>
    <td><a href="/wiki/Riverdale,_Toronto" title="Riverdale, Toronto">Riverdale</a>
    </td></tr>
    <tr>
    <td>M5K</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Design_Exchange" title="Design Exchange">Design Exchange</a>
    </td></tr>
    <tr>
    <td>M5K</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a class="mw-redirect" href="/wiki/Toronto_Dominion_Centre" title="Toronto Dominion Centre">Toronto Dominion Centre</a>
    </td></tr>
    <tr>
    <td>M6K</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td>Brockton
    </td></tr>
    <tr>
    <td>M6K</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td><a href="/wiki/Exhibition_Place" title="Exhibition Place">Exhibition Place</a>
    </td></tr>
    <tr>
    <td>M6K</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td><a class="mw-redirect" href="/wiki/Parkdale_Village" title="Parkdale Village">Parkdale Village</a>
    </td></tr>
    <tr>
    <td>M7K</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8K</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9K</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M1L</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Clairlea" title="Clairlea">Clairlea</a>
    </td></tr>
    <tr>
    <td>M1L</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Golden_Mile,_Toronto" title="Golden Mile, Toronto">Golden Mile</a>
    </td></tr>
    <tr>
    <td>M1L</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Oakridge,_Toronto" title="Oakridge, Toronto">Oakridge</a>
    </td></tr>
    <tr>
    <td>M2L</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Silver Hills
    </td></tr>
    <tr>
    <td>M2L</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/York_Mills" title="York Mills">York Mills</a>
    </td></tr>
    <tr>
    <td>M3L</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Downsview" title="Downsview">Downsview West</a>
    </td></tr>
    <tr>
    <td>M4L</td>
    <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>
    <td>The Beaches West
    </td></tr>
    <tr>
    <td>M4L</td>
    <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>
    <td><a class="mw-redirect" href="/wiki/India_Bazaar" title="India Bazaar">India Bazaar</a>
    </td></tr>
    <tr>
    <td>M5L</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Commerce_Court" title="Commerce Court">Commerce Court</a>
    </td></tr>
    <tr>
    <td>M5L</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Victoria Hotel
    </td></tr>
    <tr>
    <td>M6L</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a class="mw-redirect" href="/wiki/Downsview,_Toronto" title="Downsview, Toronto">Downsview</a>
    </td></tr>
    <tr>
    <td>M6L</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>North Park
    </td></tr>
    <tr>
    <td>M6L</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Upwood Park
    </td></tr>
    <tr>
    <td>M7L</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8L</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9L</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Humber_Summit" title="Humber Summit">Humber Summit</a>
    </td></tr>
    <tr>
    <td>M1M</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Cliffcrest" title="Cliffcrest">Cliffcrest</a>
    </td></tr>
    <tr>
    <td>M1M</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Cliffside,_Toronto" title="Cliffside, Toronto">Cliffside</a>
    </td></tr>
    <tr>
    <td>M1M</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td>Scarborough Village West
    </td></tr>
    <tr>
    <td>M2M</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Newtonbrook" title="Newtonbrook">Newtonbrook</a>
    </td></tr>
    <tr>
    <td>M2M</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Willowdale,_Toronto" title="Willowdale, Toronto">Willowdale</a>
    </td></tr>
    <tr>
    <td>M3M</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Downsview Central
    </td></tr>
    <tr>
    <td>M4M</td>
    <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>
    <td>Studio District
    </td></tr>
    <tr>
    <td>M5M</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a href="/wiki/Bedford_Park,_Toronto" title="Bedford Park, Toronto">Bedford Park</a>
    </td></tr>
    <tr>
    <td>M5M</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Lawrence Manor East
    </td></tr>
    <tr>
    <td>M6M</td>
    <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>
    <td>Del Ray
    </td></tr>
    <tr>
    <td>M6M</td>
    <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>
    <td><a class="mw-redirect" href="/wiki/Keelesdale" title="Keelesdale">Keelesdale</a>
    </td></tr>
    <tr>
    <td>M6M</td>
    <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>
    <td><a href="/wiki/Mount_Dennis" title="Mount Dennis">Mount Dennis</a>
    </td></tr>
    <tr>
    <td>M6M</td>
    <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>
    <td><a href="/wiki/Silverthorn,_Toronto" title="Silverthorn, Toronto">Silverthorn</a>
    </td></tr>
    <tr>
    <td>M7M</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8M</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9M</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a class="mw-redirect" href="/wiki/Emery,_Toronto" title="Emery, Toronto">Emery</a>
    </td></tr>
    <tr>
    <td>M9M</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a class="mw-redirect" href="/wiki/Humberlea" title="Humberlea">Humberlea</a>
    </td></tr>
    <tr>
    <td>M1N</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Birch_Cliff" title="Birch Cliff">Birch Cliff</a>
    </td></tr>
    <tr>
    <td>M1N</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td>Cliffside West
    </td></tr>
    <tr>
    <td>M2N</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Willowdale South
    </td></tr>
    <tr>
    <td>M3N</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>Downsview Northwest
    </td></tr>
    <tr>
    <td>M4N</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td><a href="/wiki/Lawrence_Park,_Toronto" title="Lawrence Park, Toronto">Lawrence Park</a>
    </td></tr>
    <tr>
    <td>M5N</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td>Roselawn
    </td></tr>
    <tr>
    <td>M6N</td>
    <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>
    <td>The Junction North
    </td></tr>
    <tr>
    <td>M6N</td>
    <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>
    <td>Runnymede
    </td></tr>
    <tr>
    <td>M7N</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8N</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9N</td>
    <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>
    <td><a href="/wiki/Weston,_Toronto" title="Weston, Toronto">Weston</a>
    </td></tr>
    <tr>
    <td>M1P</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Dorset_Park" title="Dorset Park">Dorset Park</a>
    </td></tr>
    <tr>
    <td>M1P</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Scarborough_Town_Centre" title="Scarborough Town Centre">Scarborough Town Centre</a>
    </td></tr>
    <tr>
    <td>M1P</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a class="mw-redirect" href="/wiki/Wexford_Heights" title="Wexford Heights">Wexford Heights</a>
    </td></tr>
    <tr>
    <td>M2P</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td>York Mills West
    </td></tr>
    <tr>
    <td>M3P</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M4P</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td>Davisville North
    </td></tr>
    <tr>
    <td>M5P</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td><a class="mw-redirect" href="/wiki/Forest_Hill_North" title="Forest Hill North">Forest Hill North</a>
    </td></tr>
    <tr>
    <td>M5P</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td>Forest Hill West
    </td></tr>
    <tr>
    <td>M6P</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td><a href="/wiki/High_Park" title="High Park">High Park</a>
    </td></tr>
    <tr>
    <td>M6P</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td>The Junction South
    </td></tr>
    <tr>
    <td>M7P</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8P</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9P</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Westmount
    </td></tr>
    <tr>
    <td>M1R</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Maryvale,_Toronto" title="Maryvale, Toronto">Maryvale</a>
    </td></tr>
    <tr>
    <td>M1R</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Wexford,_Toronto" title="Wexford, Toronto">Wexford</a>
    </td></tr>
    <tr>
    <td>M2R</td>
    <td><a href="/wiki/North_York" title="North York">North York</a></td>
    <td><a class="mw-redirect" href="/wiki/Willowdale_West" title="Willowdale West">Willowdale West</a>
    </td></tr>
    <tr>
    <td>M3R</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M4R</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td>North Toronto West
    </td></tr>
    <tr>
    <td>M5R</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td><a href="/wiki/The_Annex" title="The Annex">The Annex</a>
    </td></tr>
    <tr>
    <td>M5R</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td>North Midtown
    </td></tr>
    <tr>
    <td>M5R</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td><a href="/wiki/Yorkville,_Toronto" title="Yorkville, Toronto">Yorkville</a>
    </td></tr>
    <tr>
    <td>M6R</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td><a href="/wiki/Parkdale,_Toronto" title="Parkdale, Toronto">Parkdale</a>
    </td></tr>
    <tr>
    <td>M6R</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td><a href="/wiki/Roncesvalles,_Toronto" title="Roncesvalles, Toronto">Roncesvalles</a>
    </td></tr>
    <tr>
    <td>M7R</td>
    <td>Mississauga</td>
    <td>Canada Post Gateway Processing Centre
    </td></tr>
    <tr>
    <td>M8R</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9R</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/Kingsview_Village" title="Kingsview Village">Kingsview Village</a>
    </td></tr>
    <tr>
    <td>M9R</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Martin Grove Gardens
    </td></tr>
    <tr>
    <td>M9R</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Richview Gardens
    </td></tr>
    <tr>
    <td>M9R</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>St. Phillips
    </td></tr>
    <tr>
    <td>M1S</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Agincourt,_Toronto" title="Agincourt, Toronto">Agincourt</a>
    </td></tr>
    <tr>
    <td>M2S</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M3S</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M4S</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td>Davisville
    </td></tr>
    <tr>
    <td>M5S</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Harbord
    </td></tr>
    <tr>
    <td>M5S</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/University_of_Toronto" title="University of Toronto">University of Toronto</a>
    </td></tr>
    <tr>
    <td>M6S</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td><a href="/wiki/Runnymede,_Toronto" title="Runnymede, Toronto">Runnymede</a>
    </td></tr>
    <tr>
    <td>M6S</td>
    <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>
    <td><a href="/wiki/Swansea,_Toronto" title="Swansea, Toronto">Swansea</a>
    </td></tr>
    <tr>
    <td>M7S</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8S</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9S</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M1T</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td>Clarks Corners
    </td></tr>
    <tr>
    <td>M1T</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td>Sullivan
    </td></tr>
    <tr>
    <td>M1T</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Tam_O%27Shanter_%E2%80%93_Sullivan" title="Tam O'Shanter – Sullivan">Tam O'Shanter</a>
    </td></tr>
    <tr>
    <td>M2T</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M3T</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M4T</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td><a href="/wiki/Moore_Park,_Toronto" title="Moore Park, Toronto">Moore Park</a>
    </td></tr>
    <tr>
    <td>M4T</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td>Summerhill East
    </td></tr>
    <tr>
    <td>M5T</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Chinatown,_Toronto" title="Chinatown, Toronto">Chinatown</a>
    </td></tr>
    <tr>
    <td>M5T</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Grange_Park_(Toronto)" title="Grange Park (Toronto)">Grange Park</a>
    </td></tr>
    <tr>
    <td>M5T</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Kensington_Market" title="Kensington Market">Kensington Market</a>
    </td></tr>
    <tr>
    <td>M6T</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M7T</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8T</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M9T</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M1V</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a class="mw-redirect" href="/wiki/Agincourt_North" title="Agincourt North">Agincourt North</a>
    </td></tr>
    <tr>
    <td>M1V</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td>L'Amoreaux East
    </td></tr>
    <tr>
    <td>M1V</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a href="/wiki/Milliken,_Ontario" title="Milliken, Ontario">Milliken</a>
    </td></tr>
    <tr>
    <td>M1V</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td>Steeles East
    </td></tr>
    <tr>
    <td>M2V</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M3V</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M4V</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td><a href="/wiki/Deer_Park,_Toronto" title="Deer Park, Toronto">Deer Park</a>
    </td></tr>
    <tr>
    <td>M4V</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td>Forest Hill SE
    </td></tr>
    <tr>
    <td>M4V</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td><a class="mw-redirect" href="/wiki/Rathnelly" title="Rathnelly">Rathnelly</a>
    </td></tr>
    <tr>
    <td>M4V</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td><a href="/wiki/South_Hill,_Toronto" title="South Hill, Toronto">South Hill</a>
    </td></tr>
    <tr>
    <td>M4V</td>
    <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>
    <td>Summerhill West
    </td></tr>
    <tr>
    <td>M5V</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/CN_Tower" title="CN Tower">CN Tower</a>
    </td></tr>
    <tr>
    <td>M5V</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Bathurst Quay
    </td></tr>
    <tr>
    <td>M5V</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Island airport
    </td></tr>
    <tr>
    <td>M5V</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Harbourfront West
    </td></tr>
    <tr>
    <td>M5V</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a class="mw-redirect" href="/wiki/King_and_Spadina" title="King and Spadina">King and Spadina</a>
    </td></tr>
    <tr>
    <td>M5V</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Railway_Lands" title="Railway Lands">Railway Lands</a>
    </td></tr>
    <tr>
    <td>M5V</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a class="mw-redirect" href="/wiki/South_Niagara" title="South Niagara">South Niagara</a>
    </td></tr>
    <tr>
    <td>M6V</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M7V</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8V</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Humber Bay Shores
    </td></tr>
    <tr>
    <td>M8V</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Mimico South
    </td></tr>
    <tr>
    <td>M8V</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/New_Toronto" title="New Toronto">New Toronto</a>
    </td></tr>
    <tr>
    <td>M9V</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Albion Gardens
    </td></tr>
    <tr>
    <td>M9V</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a class="mw-redirect" href="/wiki/Beaumond_Heights" title="Beaumond Heights">Beaumond Heights</a>
    </td></tr>
    <tr>
    <td>M9V</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Humbergate
    </td></tr>
    <tr>
    <td>M9V</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a class="mw-redirect" href="/wiki/Mount_Olive-Silverstone-Jamestown" title="Mount Olive-Silverstone-Jamestown">Jamestown</a>
    </td></tr>
    <tr>
    <td>M9V</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a class="mw-redirect" href="/wiki/Mount_Olive-Silverstone-Jamestown" title="Mount Olive-Silverstone-Jamestown">Mount Olive</a>
    </td></tr>
    <tr>
    <td>M9V</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a class="mw-redirect" href="/wiki/Silverstone,_Toronto" title="Silverstone, Toronto">Silverstone</a>
    </td></tr>
    <tr>
    <td>M9V</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a class="mw-redirect" href="/wiki/South_Steeles" title="South Steeles">South Steeles</a>
    </td></tr>
    <tr>
    <td>M9V</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/Thistletown" title="Thistletown">Thistletown</a>
    </td></tr>
    <tr>
    <td>M1W</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td>L'Amoreaux West
    </td></tr>
    <tr>
    <td>M2W</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M3W</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M4W</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Rosedale,_Toronto" title="Rosedale, Toronto">Rosedale</a>
    </td></tr>
    <tr>
    <td>M5W</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td>Stn A PO Boxes 25 The Esplanade
    </td></tr>
    <tr>
    <td>M6W</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M7W</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8W</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/Alderwood,_Toronto" title="Alderwood, Toronto">Alderwood</a>
    </td></tr>
    <tr>
    <td>M8W</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/Long_Branch,_Toronto" title="Long Branch, Toronto">Long Branch</a>
    </td></tr>
    <tr>
    <td>M9W</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Northwest
    </td></tr>
    <tr>
    <td>M1X</td>
    <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>
    <td><a class="mw-redirect" href="/wiki/Upper_Rouge" title="Upper Rouge">Upper Rouge</a>
    </td></tr>
    <tr>
    <td>M2X</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M3X</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M4X</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Cabbagetown,_Toronto" title="Cabbagetown, Toronto">Cabbagetown</a>
    </td></tr>
    <tr>
    <td>M4X</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/St._James_Town" title="St. James Town">St. James Town</a>
    </td></tr>
    <tr>
    <td>M5X</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/First_Canadian_Place" title="First Canadian Place">First Canadian Place</a>
    </td></tr>
    <tr>
    <td>M5X</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Underground_city" title="Underground city">Underground city</a>
    </td></tr>
    <tr>
    <td>M6X</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M7X</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8X</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/The_Kingsway" title="The Kingsway">The Kingsway</a>
    </td></tr>
    <tr>
    <td>M8X</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Montgomery Road
    </td></tr>
    <tr>
    <td>M8X</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Old Mill North
    </td></tr>
    <tr>
    <td>M9X</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M1Y</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M2Y</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M3Y</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M4Y</td>
    <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>
    <td><a href="/wiki/Church_and_Wellesley" title="Church and Wellesley">Church and Wellesley</a>
    </td></tr>
    <tr>
    <td>M5Y</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M6Y</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M7Y</td>
    <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>
    <td>Business Reply Mail Processing Centre 969 Eastern
    </td></tr>
    <tr>
    <td>M8Y</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/Humber_Bay" title="Humber Bay">Humber Bay</a>
    </td></tr>
    <tr>
    <td>M8Y</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>King's Mill Park
    </td></tr>
    <tr>
    <td>M8Y</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Kingsway Park South East
    </td></tr>
    <tr>
    <td>M8Y</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/Mimico" title="Mimico">Mimico NE</a>
    </td></tr>
    <tr>
    <td>M8Y</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/Old_Mill,_Toronto" title="Old Mill, Toronto">Old Mill South</a>
    </td></tr>
    <tr>
    <td>M8Y</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/The_Queensway" title="The Queensway">The Queensway East</a>
    </td></tr>
    <tr>
    <td>M8Y</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a class="mw-redirect" href="/wiki/Fairmont_Royal_York_Hotel" title="Fairmont Royal York Hotel">Royal York South East</a>
    </td></tr>
    <tr>
    <td>M8Y</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a class="mw-redirect" href="/wiki/Sunnylea" title="Sunnylea">Sunnylea</a>
    </td></tr>
    <tr>
    <td>M9Y</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M1Z</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M2Z</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M3Z</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M4Z</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M5Z</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M6Z</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M7Z</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    <tr>
    <td>M8Z</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Kingsway Park South West
    </td></tr>
    <tr>
    <td>M8Z</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/Mimico" title="Mimico">Mimico NW</a>
    </td></tr>
    <tr>
    <td>M8Z</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td><a href="/wiki/The_Queensway" title="The Queensway">The Queensway West</a>
    </td></tr>
    <tr>
    <td>M8Z</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>Royal York South West
    </td></tr>
    <tr>
    <td>M8Z</td>
    <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>
    <td>South of Bloor
    </td></tr>
    <tr>
    <td>M9Z</td>
    <td>Not assigned</td>
    <td>Not assigned
    </td></tr>
    </tbody></table>
    <div>
    <table class="multicol" role="presentation" style="border-collapse: collapse; padding: 0; border: 0; background:transparent; width:100%;">
    </table><h2><span id="Most_populated_FSAs.5B3.5D"></span><span class="mw-headline" id="Most_populated_FSAs[3]">Most populated FSAs<sup class="reference" id="cite_ref-statcan_3-0"><a href="#cite_note-statcan-3">[3]</a></sup></span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=edit&amp;section=2" title="Edit section: Most populated FSAs[3]">edit</a><span class="mw-editsection-bracket">]</span></span></h2><ol><li>M1B, 65,129</li>
    <li>M2N, 60,124</li>
    <li>M1V, 55,250</li>
    <li>M9V, 55,159</li>
    <li>M2J, 54,391</li></ol><p>
    </p><table cellpadding="2" cellspacing="0" rules="all" style="width:100%; border-collapse:collapse; border:1px solid #ccc;">
    <tbody><tr><td></td></tr></tbody></table></div>
    <p>
    </p>
    <h2><span id="Least_populated_FSAs.5B3.5D"></span><span class="mw-headline" id="Least_populated_FSAs[3]">Least populated FSAs<sup class="reference" id="cite_ref-statcan_3-1"><a href="#cite_note-statcan-3">[3]</a></sup></span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=edit&amp;section=3" title="Edit section: Least populated FSAs[3]">edit</a><span class="mw-editsection-bracket">]</span></span></h2>
    <ol><li>M5K, 5</li>
    <li>M5L, 5</li>
    <li>M5W, 5</li>
    <li>M5X, 5</li>
    <li>M7A, 5</li></ol>
    <p>
    </p>
    <h2><span class="mw-headline" id="References">References</span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="/w/index.php?title=List_of_postal_codes_of_Canada:_M&amp;action=edit&amp;section=4" title="Edit section: References">edit</a><span class="mw-editsection-bracket">]</span></span></h2>
    <div class="mw-references-wrap"><ol class="references">
    <li id="cite_note-1"><span class="mw-cite-backlink"><b><a href="#cite_ref-1">^</a></b></span> <span class="reference-text">
    <cite class="citation web">Canada Post. <a class="external text" href="https://www.canadapost.ca/cpotools/apps/fpc/personal/findByCity?execution=e2s1" rel="nofollow">"Canada Post - Find a Postal Code"</a><span class="reference-accessdate">. Retrieved <span class="nowrap">9 November</span> 2008</span>.</cite><span class="Z3988" title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Canada+Post+-+Find+a+Postal+Code&amp;rft.au=Canada+Post&amp;rft_id=https%3A%2F%2Fwww.canadapost.ca%2Fcpotools%2Fapps%2Ffpc%2Fpersonal%2FfindByCity%3Fexecution%3De2s1&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+postal+codes+of+Canada%3A+M"></span><style data-mw-deduplicate="TemplateStyles:r886058088">.mw-parser-output cite.citation{font-style:inherit}.mw-parser-output .citation q{quotes:"\"""\"""'""'"}.mw-parser-output .citation .cs1-lock-free a{background:url("//upload.wikimedia.org/wikipedia/commons/thumb/6/65/Lock-green.svg/9px-Lock-green.svg.png")no-repeat;background-position:right .1em center}.mw-parser-output .citation .cs1-lock-limited a,.mw-parser-output .citation .cs1-lock-registration a{background:url("//upload.wikimedia.org/wikipedia/commons/thumb/d/d6/Lock-gray-alt-2.svg/9px-Lock-gray-alt-2.svg.png")no-repeat;background-position:right .1em center}.mw-parser-output .citation .cs1-lock-subscription a{background:url("//upload.wikimedia.org/wikipedia/commons/thumb/a/aa/Lock-red-alt-2.svg/9px-Lock-red-alt-2.svg.png")no-repeat;background-position:right .1em center}.mw-parser-output .cs1-subscription,.mw-parser-output .cs1-registration{color:#555}.mw-parser-output .cs1-subscription span,.mw-parser-output .cs1-registration span{border-bottom:1px dotted;cursor:help}.mw-parser-output .cs1-ws-icon a{background:url("//upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Wikisource-logo.svg/12px-Wikisource-logo.svg.png")no-repeat;background-position:right .1em center}.mw-parser-output code.cs1-code{color:inherit;background:inherit;border:inherit;padding:inherit}.mw-parser-output .cs1-hidden-error{display:none;font-size:100%}.mw-parser-output .cs1-visible-error{font-size:100%}.mw-parser-output .cs1-maint{display:none;color:#33aa33;margin-left:0.3em}.mw-parser-output .cs1-subscription,.mw-parser-output .cs1-registration,.mw-parser-output .cs1-format{font-size:95%}.mw-parser-output .cs1-kern-left,.mw-parser-output .cs1-kern-wl-left{padding-left:0.2em}.mw-parser-output .cs1-kern-right,.mw-parser-output .cs1-kern-wl-right{padding-right:0.2em}</style></span>
    </li>
    <li id="cite_note-2"><span class="mw-cite-backlink"><b><a href="#cite_ref-2">^</a></b></span> <span class="reference-text"><cite class="citation web"><a class="external text" href="https://web.archive.org/web/20110519093024/http://www.canadapost.ca/cpo/mc/personal/tools/mobileapp/default.jsf" rel="nofollow">"Mobile Apps"</a>. Canada Post. Archived from <a class="external text" href="http://www.canadapost.ca/cpo/mc/personal/tools/mobileapp/default.jsf" rel="nofollow">the original</a> on 2011-05-19.</cite><span class="Z3988" title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=Mobile+Apps&amp;rft.pub=Canada+Post&amp;rft_id=http%3A%2F%2Fwww.canadapost.ca%2Fcpo%2Fmc%2Fpersonal%2Ftools%2Fmobileapp%2Fdefault.jsf&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+postal+codes+of+Canada%3A+M"></span><link href="mw-data:TemplateStyles:r886058088" rel="mw-deduplicated-inline-style"/></span>
    </li>
    <li id="cite_note-statcan-3"><span class="mw-cite-backlink">^ <a href="#cite_ref-statcan_3-0"><sup><i><b>a</b></i></sup></a> <a href="#cite_ref-statcan_3-1"><sup><i><b>b</b></i></sup></a></span> <span class="reference-text"><cite class="citation web"><a class="external text" href="http://www12.statcan.ca/english/census06/data/popdwell/Table.cfm?T=1201&amp;SR=1&amp;S=0&amp;O=A&amp;RPP=9999&amp;PR=0&amp;CMA=0" rel="nofollow">"2006 Census of Population"</a>. 15 October 2008.</cite><span class="Z3988" title="ctx_ver=Z39.88-2004&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=unknown&amp;rft.btitle=2006+Census+of+Population&amp;rft.date=2008-10-15&amp;rft_id=http%3A%2F%2Fwww12.statcan.ca%2Fenglish%2Fcensus06%2Fdata%2Fpopdwell%2FTable.cfm%3FT%3D1201%26SR%3D1%26S%3D0%26O%3DA%26RPP%3D9999%26PR%3D0%26CMA%3D0&amp;rfr_id=info%3Asid%2Fen.wikipedia.org%3AList+of+postal+codes+of+Canada%3A+M"></span><link href="mw-data:TemplateStyles:r886058088" rel="mw-deduplicated-inline-style"/></span>
    </li>
    </ol></div>
    <table class="navbox">
    <tbody><tr>
    <td style="width:36px; text-align:center"><a class="image" href="/wiki/File:Flag_of_Canada.svg" title="Flag of Canada"><img alt="Flag of Canada" data-file-height="600" data-file-width="1200" decoding="async" height="18" src="//upload.wikimedia.org/wikipedia/en/thumb/c/cf/Flag_of_Canada.svg/36px-Flag_of_Canada.svg.png" srcset="//upload.wikimedia.org/wikipedia/en/thumb/c/cf/Flag_of_Canada.svg/54px-Flag_of_Canada.svg.png 1.5x, //upload.wikimedia.org/wikipedia/en/thumb/c/cf/Flag_of_Canada.svg/72px-Flag_of_Canada.svg.png 2x" width="36"/></a>
    </td>
    <th class="navbox-title" style="font-size:110%"><a href="/wiki/Postal_codes_in_Canada" title="Postal codes in Canada">Canadian postal codes</a>
    </th>
    <td style="width:36px; text-align:center"><a class="image" href="/wiki/File:Canadian_postal_district_map_(without_legends).svg"><img alt="Canadian postal district map (without legends).svg" data-file-height="846" data-file-width="1000" decoding="async" height="18" src="//upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Canadian_postal_district_map_%28without_legends%29.svg/21px-Canadian_postal_district_map_%28without_legends%29.svg.png" srcset="//upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Canadian_postal_district_map_%28without_legends%29.svg/32px-Canadian_postal_district_map_%28without_legends%29.svg.png 1.5x, //upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Canadian_postal_district_map_%28without_legends%29.svg/43px-Canadian_postal_district_map_%28without_legends%29.svg.png 2x" width="21"/></a>
    </td></tr>
    <tr>
    <td colspan="3" style="text-align:center; font-size: 100%;">
    <table cellspacing="0" style="background-color: #F8F8F8;" width="100%">
    <tbody><tr>
    <td style="text-align:center; border:1px solid #aaa;"><a href="/wiki/Newfoundland_and_Labrador" title="Newfoundland and Labrador">NL</a>
    </td>
    <td style="text-align:center; border:1px solid #aaa;"><a href="/wiki/Nova_Scotia" title="Nova Scotia">NS</a>
    </td>
    <td style="text-align:center; border:1px solid #aaa;"><a href="/wiki/Prince_Edward_Island" title="Prince Edward Island">PE</a>
    </td>
    <td style="text-align:center; border:1px solid #aaa;"><a href="/wiki/New_Brunswick" title="New Brunswick">NB</a>
    </td>
    <td colspan="3" style="text-align:center; border:1px solid #aaa;"><a href="/wiki/Quebec" title="Quebec">QC</a>
    </td>
    <td colspan="5" style="text-align:center; border:1px solid #aaa;"><a href="/wiki/Ontario" title="Ontario">ON</a>
    </td>
    <td style="text-align:center; border:1px solid #aaa;"><a href="/wiki/Manitoba" title="Manitoba">MB</a>
    </td>
    <td style="text-align:center; border:1px solid #aaa;"><a href="/wiki/Saskatchewan" title="Saskatchewan">SK</a>
    </td>
    <td style="text-align:center; border:1px solid #aaa;"><a href="/wiki/Alberta" title="Alberta">AB</a>
    </td>
    <td style="text-align:center; border:1px solid #aaa;"><a href="/wiki/British_Columbia" title="British Columbia">BC</a>
    </td>
    <td style="text-align:center; border:1px solid #aaa;"><a href="/wiki/Nunavut" title="Nunavut">NU</a>/<a href="/wiki/Northwest_Territories" title="Northwest Territories">NT</a>
    </td>
    <td style="text-align:center; border:1px solid #aaa;"><a href="/wiki/Yukon" title="Yukon">YT</a>
    </td></tr>
    <tr>
    <td align="center" style="border: 1px solid #FF0000; background-color: #FFE0E0; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_A" title="List of postal codes of Canada: A">A</a>
    </td>
    <td align="center" style="border: 1px solid #FF4000; background-color: #FFE8E0; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_B" title="List of postal codes of Canada: B">B</a>
    </td>
    <td align="center" style="border: 1px solid #FF8000; background-color: #FFF0E0; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_C" title="List of postal codes of Canada: C">C</a>
    </td>
    <td align="center" style="border: 1px solid #FFC000; background-color: #FFF8E0; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_E" title="List of postal codes of Canada: E">E</a>
    </td>
    <td align="center" style="border: 1px solid #FFFF00; background-color: #FFFFE0; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_G" title="List of postal codes of Canada: G">G</a>
    </td>
    <td align="center" style="border: 1px solid #C0FF00; background-color: #F8FFE0; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_H" title="List of postal codes of Canada: H">H</a>
    </td>
    <td align="center" style="border: 1px solid #80FF00; background-color: #F0FFE0; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_J" title="List of postal codes of Canada: J">J</a>
    </td>
    <td align="center" style="border: 1px solid #00FF00; background-color: #E0FFE0; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_K" title="List of postal codes of Canada: K">K</a>
    </td>
    <td align="center" style="border: 1px solid #00FF80; background-color: #E0FFF0; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_L" title="List of postal codes of Canada: L">L</a>
    </td>
    <td align="center" style="border: 1px solid #E0FFF8; background-color: #00FFC0; font-size: 135%; color: black;" width="5%"><a class="mw-selflink selflink">M</a>
    </td>
    <td align="center" style="border: 1px solid #00FFE0; background-color: #E0FFFC; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_N" title="List of postal codes of Canada: N">N</a>
    </td>
    <td align="center" style="border: 1px solid #00FFFF; background-color: #E0FFFF; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_P" title="List of postal codes of Canada: P">P</a>
    </td>
    <td align="center" style="border: 1px solid #00C0FF; background-color: #E0F8FF; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_R" title="List of postal codes of Canada: R">R</a>
    </td>
    <td align="center" style="border: 1px solid #0080FF; background-color: #E0F0FF; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_S" title="List of postal codes of Canada: S">S</a>
    </td>
    <td align="center" style="border: 1px solid #0040FF; background-color: #E0E8FF; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_T" title="List of postal codes of Canada: T">T</a>
    </td>
    <td align="center" style="border: 1px solid #0000FF; background-color: #E0E0FF; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_V" title="List of postal codes of Canada: V">V</a>
    </td>
    <td align="center" style="border: 1px solid #A000FF; background-color: #E8E0FF; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_X" title="List of postal codes of Canada: X">X</a>
    </td>
    <td align="center" style="border: 1px solid #FF00FF; background-color: #FFE0FF; font-size: 135%;" width="5%"><a href="/wiki/List_of_postal_codes_of_Canada:_Y" title="List of postal codes of Canada: Y">Y</a>
    </td></tr></tbody></table>
    </td></tr></tbody></table>
    <!-- 
    NewPP limit report
    Parsed by mw1265
    Cached time: 20191013031038
    Cache expiry: 2592000
    Dynamic content: false
    Complications: [vary‐revision‐sha1]
    CPU time usage: 0.156 seconds
    Real time usage: 0.193 seconds
    Preprocessor visited node count: 574/1000000
    Preprocessor generated node count: 0/1500000
    Post‐expand include size: 10232/2097152 bytes
    Template argument size: 13/2097152 bytes
    Highest expansion depth: 5/40
    Expensive parser function count: 0/500
    Unstrip recursion depth: 1/20
    Unstrip post‐expand size: 9025/5000000 bytes
    Number of Wikibase entities loaded: 0/400
    Lua time usage: 0.049/10.000 seconds
    Lua memory usage: 1.75 MB/50 MB
    -->
    <!--
    Transclusion expansion time report (%,ms,calls,template)
    100.00%  108.387      1 -total
     71.89%   77.915      3 Template:Cite_web
     13.42%   14.549      1 Template:Col-2
     11.73%   12.711      1 Template:Col-break
      4.01%    4.349      1 Template:Canadian_postal_codes
      2.99%    3.236      1 Template:Col-begin
      2.37%    2.568      2 Template:Col-end
    -->
    <!-- Saved in parser cache with key enwiki:pcache:idhash:539066-0!canonical and timestamp 20191013031038 and revision id 920980179
     -->
    </div>
    


```python
header_items=table_page.table.tr.text
header_items=header_items.split('\n')[1:4]
header_items
```




    ['Postcode', 'Borough', 'Neighbourhood']




```python
table_value=table_page.table.tbody
table_value=table_value.find_all('td')
print(table_value)
```

    [<td>M1A</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M2A</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M3A</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Parkwoods" title="Parkwoods">Parkwoods</a>
    </td>, <td>M4A</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Victoria_Village" title="Victoria Village">Victoria Village</a>
    </td>, <td>M5A</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Harbourfront_(Toronto)" title="Harbourfront (Toronto)">Harbourfront</a>
    </td>, <td>M5A</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Regent_Park" title="Regent Park">Regent Park</a>
    </td>, <td>M6A</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Lawrence_Heights" title="Lawrence Heights">Lawrence Heights</a>
    </td>, <td>M6A</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Lawrence_Manor" title="Lawrence Manor">Lawrence Manor</a>
    </td>, <td>M7A</td>, <td><a href="/wiki/Queen%27s_Park_(Toronto)" title="Queen's Park (Toronto)">Queen's Park</a></td>, <td>Not assigned
    </td>, <td>M8A</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9A</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a class="mw-redirect" href="/wiki/Islington_Avenue" title="Islington Avenue">Islington Avenue</a>
    </td>, <td>M1B</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Rouge,_Toronto" title="Rouge, Toronto">Rouge</a>
    </td>, <td>M1B</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Malvern,_Toronto" title="Malvern, Toronto">Malvern</a>
    </td>, <td>M2B</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M3B</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Don Mills North
    </td>, <td>M4B</td>, <td><a href="/wiki/East_York" title="East York">East York</a></td>, <td><a class="mw-redirect" href="/wiki/Woodbine_Gardens" title="Woodbine Gardens">Woodbine Gardens</a>
    </td>, <td>M4B</td>, <td><a href="/wiki/East_York" title="East York">East York</a></td>, <td><a class="mw-redirect" href="/wiki/Parkview_Hill" title="Parkview Hill">Parkview Hill</a>
    </td>, <td>M5B</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Ryerson
    </td>, <td>M5B</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Garden District
    </td>, <td>M6B</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Glencairn
    </td>, <td>M7B</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8B</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9B</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Cloverdale
    </td>, <td>M9B</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a class="mw-redirect" href="/wiki/Islington,_Toronto" title="Islington, Toronto">Islington</a>
    </td>, <td>M9B</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Martin Grove
    </td>, <td>M9B</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/Princess_Gardens" title="Princess Gardens">Princess Gardens</a>
    </td>, <td>M9B</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a class="mw-redirect" href="/wiki/West_Deane_Park" title="West Deane Park">West Deane Park</a>
    </td>, <td>M1C</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Highland_Creek_(Toronto)" title="Highland Creek (Toronto)">Highland Creek</a>
    </td>, <td>M1C</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a class="mw-redirect" href="/wiki/Rouge_Hill" title="Rouge Hill">Rouge Hill</a>
    </td>, <td>M1C</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Port_Union,_Toronto" title="Port Union, Toronto">Port Union</a>
    </td>, <td>M2C</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M3C</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Flemingdon_Park" title="Flemingdon Park">Flemingdon Park</a>
    </td>, <td>M3C</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Don Mills South
    </td>, <td>M4C</td>, <td><a href="/wiki/East_York" title="East York">East York</a></td>, <td><a class="mw-redirect" href="/wiki/Woodbine_Heights" title="Woodbine Heights">Woodbine Heights</a>
    </td>, <td>M5C</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/St._James_Town" title="St. James Town">St. James Town</a>
    </td>, <td>M6C</td>, <td>York</td>, <td><a class="mw-redirect" href="/wiki/Humewood-Cedarvale" title="Humewood-Cedarvale">Humewood-Cedarvale</a>
    </td>, <td>M7C</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8C</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9C</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Bloordale Gardens
    </td>, <td>M9C</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Eringate
    </td>, <td>M9C</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/Markland_Wood" title="Markland Wood">Markland Wood</a>
    </td>, <td>M9C</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Old Burnhamthorpe
    </td>, <td>M1E</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td>Guildwood
    </td>, <td>M1E</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Morningside,_Toronto" title="Morningside, Toronto">Morningside</a>
    </td>, <td>M1E</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/West_Hill,_Toronto" title="West Hill, Toronto">West Hill</a>
    </td>, <td>M2E</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M3E</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M4E</td>, <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>, <td><a href="/wiki/The_Beaches" title="The Beaches">The Beaches</a>
    </td>, <td>M5E</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Berczy_Park" title="Berczy Park">Berczy Park</a>
    </td>, <td>M6E</td>, <td>York</td>, <td>Caledonia-Fairbanks
    </td>, <td>M7E</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8E</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9E</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M1G</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Woburn,_Toronto" title="Woburn, Toronto">Woburn</a>
    </td>, <td>M2G</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M3G</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M4G</td>, <td><a href="/wiki/East_York" title="East York">East York</a></td>, <td><a href="/wiki/Leaside" title="Leaside">Leaside</a>
    </td>, <td>M5G</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Central Bay Street
    </td>, <td>M6G</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Christie
    </td>, <td>M7G</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8G</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9G</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M1H</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td>Cedarbrae
    </td>, <td>M2H</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Hillcrest_Village" title="Hillcrest Village">Hillcrest Village</a>
    </td>, <td>M3H</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Bathurst_Manor" title="Bathurst Manor">Bathurst Manor</a>
    </td>, <td>M3H</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Downsview North
    </td>, <td>M3H</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a class="mw-redirect" href="/wiki/Wilson_Heights,_Toronto" title="Wilson Heights, Toronto">Wilson Heights</a>
    </td>, <td>M4H</td>, <td><a href="/wiki/East_York" title="East York">East York</a></td>, <td><a href="/wiki/Thorncliffe_Park" title="Thorncliffe Park">Thorncliffe Park</a>
    </td>, <td>M5H</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Adelaide
    </td>, <td>M5H</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>King
    </td>, <td>M5H</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Richmond
    </td>, <td>M6H</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td><a class="mw-redirect" href="/wiki/Dovercourt_Village" title="Dovercourt Village">Dovercourt Village</a>
    </td>, <td>M6H</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td>Dufferin
    </td>, <td>M7H</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8H</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9H</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M1J</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Scarborough_Village" title="Scarborough Village">Scarborough Village</a>
    </td>, <td>M2J</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Fairview
    </td>, <td>M2J</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Henry_Farm" title="Henry Farm">Henry Farm</a>
    </td>, <td>M2J</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Oriole
    </td>, <td>M3J</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a class="mw-redirect" href="/wiki/Northwood_Park" title="Northwood Park">Northwood Park</a>
    </td>, <td>M3J</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/York_University" title="York University">York University</a>
    </td>, <td>M4J</td>, <td><a href="/wiki/East_York" title="East York">East York</a></td>, <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a>
    </td>, <td>M5J</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Harbourfront East
    </td>, <td>M5J</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Toronto_Islands" title="Toronto Islands">Toronto Islands</a>
    </td>, <td>M5J</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Union_Station_(Toronto)" title="Union Station (Toronto)">Union Station</a>
    </td>, <td>M6J</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td><a href="/wiki/Little_Portugal,_Toronto" title="Little Portugal, Toronto">Little Portugal</a>
    </td>, <td>M6J</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td><a href="/wiki/Trinity%E2%80%93Bellwoods" title="Trinity–Bellwoods">Trinity</a>
    </td>, <td>M7J</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8J</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9J</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M1K</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td>East Birchmount Park
    </td>, <td>M1K</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Ionview" title="Ionview">Ionview</a>
    </td>, <td>M1K</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a class="mw-redirect" href="/wiki/Kennedy_Park,_Toronto" title="Kennedy Park, Toronto">Kennedy Park</a>
    </td>, <td>M2K</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Bayview_Village" title="Bayview Village">Bayview Village</a>
    </td>, <td>M3K</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/CFB_Toronto" title="CFB Toronto">CFB Toronto</a>
    </td>, <td>M3K</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Downsview East
    </td>, <td>M4K</td>, <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>, <td>The Danforth West
    </td>, <td>M4K</td>, <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>, <td><a href="/wiki/Riverdale,_Toronto" title="Riverdale, Toronto">Riverdale</a>
    </td>, <td>M5K</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Design_Exchange" title="Design Exchange">Design Exchange</a>
    </td>, <td>M5K</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a class="mw-redirect" href="/wiki/Toronto_Dominion_Centre" title="Toronto Dominion Centre">Toronto Dominion Centre</a>
    </td>, <td>M6K</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td>Brockton
    </td>, <td>M6K</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td><a href="/wiki/Exhibition_Place" title="Exhibition Place">Exhibition Place</a>
    </td>, <td>M6K</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td><a class="mw-redirect" href="/wiki/Parkdale_Village" title="Parkdale Village">Parkdale Village</a>
    </td>, <td>M7K</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8K</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9K</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M1L</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Clairlea" title="Clairlea">Clairlea</a>
    </td>, <td>M1L</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Golden_Mile,_Toronto" title="Golden Mile, Toronto">Golden Mile</a>
    </td>, <td>M1L</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Oakridge,_Toronto" title="Oakridge, Toronto">Oakridge</a>
    </td>, <td>M2L</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Silver Hills
    </td>, <td>M2L</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/York_Mills" title="York Mills">York Mills</a>
    </td>, <td>M3L</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Downsview" title="Downsview">Downsview West</a>
    </td>, <td>M4L</td>, <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>, <td>The Beaches West
    </td>, <td>M4L</td>, <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>, <td><a class="mw-redirect" href="/wiki/India_Bazaar" title="India Bazaar">India Bazaar</a>
    </td>, <td>M5L</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Commerce_Court" title="Commerce Court">Commerce Court</a>
    </td>, <td>M5L</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Victoria Hotel
    </td>, <td>M6L</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a class="mw-redirect" href="/wiki/Downsview,_Toronto" title="Downsview, Toronto">Downsview</a>
    </td>, <td>M6L</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>North Park
    </td>, <td>M6L</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Upwood Park
    </td>, <td>M7L</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8L</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9L</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Humber_Summit" title="Humber Summit">Humber Summit</a>
    </td>, <td>M1M</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Cliffcrest" title="Cliffcrest">Cliffcrest</a>
    </td>, <td>M1M</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Cliffside,_Toronto" title="Cliffside, Toronto">Cliffside</a>
    </td>, <td>M1M</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td>Scarborough Village West
    </td>, <td>M2M</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Newtonbrook" title="Newtonbrook">Newtonbrook</a>
    </td>, <td>M2M</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Willowdale,_Toronto" title="Willowdale, Toronto">Willowdale</a>
    </td>, <td>M3M</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Downsview Central
    </td>, <td>M4M</td>, <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>, <td>Studio District
    </td>, <td>M5M</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a href="/wiki/Bedford_Park,_Toronto" title="Bedford Park, Toronto">Bedford Park</a>
    </td>, <td>M5M</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Lawrence Manor East
    </td>, <td>M6M</td>, <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>, <td>Del Ray
    </td>, <td>M6M</td>, <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>, <td><a class="mw-redirect" href="/wiki/Keelesdale" title="Keelesdale">Keelesdale</a>
    </td>, <td>M6M</td>, <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>, <td><a href="/wiki/Mount_Dennis" title="Mount Dennis">Mount Dennis</a>
    </td>, <td>M6M</td>, <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>, <td><a href="/wiki/Silverthorn,_Toronto" title="Silverthorn, Toronto">Silverthorn</a>
    </td>, <td>M7M</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8M</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9M</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a class="mw-redirect" href="/wiki/Emery,_Toronto" title="Emery, Toronto">Emery</a>
    </td>, <td>M9M</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a class="mw-redirect" href="/wiki/Humberlea" title="Humberlea">Humberlea</a>
    </td>, <td>M1N</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Birch_Cliff" title="Birch Cliff">Birch Cliff</a>
    </td>, <td>M1N</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td>Cliffside West
    </td>, <td>M2N</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Willowdale South
    </td>, <td>M3N</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>Downsview Northwest
    </td>, <td>M4N</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td><a href="/wiki/Lawrence_Park,_Toronto" title="Lawrence Park, Toronto">Lawrence Park</a>
    </td>, <td>M5N</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td>Roselawn
    </td>, <td>M6N</td>, <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>, <td>The Junction North
    </td>, <td>M6N</td>, <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>, <td>Runnymede
    </td>, <td>M7N</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8N</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9N</td>, <td><a href="/wiki/York,_Toronto" title="York, Toronto">York</a></td>, <td><a href="/wiki/Weston,_Toronto" title="Weston, Toronto">Weston</a>
    </td>, <td>M1P</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Dorset_Park" title="Dorset Park">Dorset Park</a>
    </td>, <td>M1P</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Scarborough_Town_Centre" title="Scarborough Town Centre">Scarborough Town Centre</a>
    </td>, <td>M1P</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a class="mw-redirect" href="/wiki/Wexford_Heights" title="Wexford Heights">Wexford Heights</a>
    </td>, <td>M2P</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td>York Mills West
    </td>, <td>M3P</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M4P</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td>Davisville North
    </td>, <td>M5P</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td><a class="mw-redirect" href="/wiki/Forest_Hill_North" title="Forest Hill North">Forest Hill North</a>
    </td>, <td>M5P</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td>Forest Hill West
    </td>, <td>M6P</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td><a href="/wiki/High_Park" title="High Park">High Park</a>
    </td>, <td>M6P</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td>The Junction South
    </td>, <td>M7P</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8P</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9P</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Westmount
    </td>, <td>M1R</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Maryvale,_Toronto" title="Maryvale, Toronto">Maryvale</a>
    </td>, <td>M1R</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Wexford,_Toronto" title="Wexford, Toronto">Wexford</a>
    </td>, <td>M2R</td>, <td><a href="/wiki/North_York" title="North York">North York</a></td>, <td><a class="mw-redirect" href="/wiki/Willowdale_West" title="Willowdale West">Willowdale West</a>
    </td>, <td>M3R</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M4R</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td>North Toronto West
    </td>, <td>M5R</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td><a href="/wiki/The_Annex" title="The Annex">The Annex</a>
    </td>, <td>M5R</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td>North Midtown
    </td>, <td>M5R</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td><a href="/wiki/Yorkville,_Toronto" title="Yorkville, Toronto">Yorkville</a>
    </td>, <td>M6R</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td><a href="/wiki/Parkdale,_Toronto" title="Parkdale, Toronto">Parkdale</a>
    </td>, <td>M6R</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td><a href="/wiki/Roncesvalles,_Toronto" title="Roncesvalles, Toronto">Roncesvalles</a>
    </td>, <td>M7R</td>, <td>Mississauga</td>, <td>Canada Post Gateway Processing Centre
    </td>, <td>M8R</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9R</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/Kingsview_Village" title="Kingsview Village">Kingsview Village</a>
    </td>, <td>M9R</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Martin Grove Gardens
    </td>, <td>M9R</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Richview Gardens
    </td>, <td>M9R</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>St. Phillips
    </td>, <td>M1S</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Agincourt,_Toronto" title="Agincourt, Toronto">Agincourt</a>
    </td>, <td>M2S</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M3S</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M4S</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td>Davisville
    </td>, <td>M5S</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Harbord
    </td>, <td>M5S</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/University_of_Toronto" title="University of Toronto">University of Toronto</a>
    </td>, <td>M6S</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td><a href="/wiki/Runnymede,_Toronto" title="Runnymede, Toronto">Runnymede</a>
    </td>, <td>M6S</td>, <td><a href="/wiki/West_Toronto" title="West Toronto">West Toronto</a></td>, <td><a href="/wiki/Swansea,_Toronto" title="Swansea, Toronto">Swansea</a>
    </td>, <td>M7S</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8S</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9S</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M1T</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td>Clarks Corners
    </td>, <td>M1T</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td>Sullivan
    </td>, <td>M1T</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Tam_O%27Shanter_%E2%80%93_Sullivan" title="Tam O'Shanter – Sullivan">Tam O'Shanter</a>
    </td>, <td>M2T</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M3T</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M4T</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td><a href="/wiki/Moore_Park,_Toronto" title="Moore Park, Toronto">Moore Park</a>
    </td>, <td>M4T</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td>Summerhill East
    </td>, <td>M5T</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Chinatown,_Toronto" title="Chinatown, Toronto">Chinatown</a>
    </td>, <td>M5T</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Grange_Park_(Toronto)" title="Grange Park (Toronto)">Grange Park</a>
    </td>, <td>M5T</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Kensington_Market" title="Kensington Market">Kensington Market</a>
    </td>, <td>M6T</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M7T</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8T</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M9T</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M1V</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a class="mw-redirect" href="/wiki/Agincourt_North" title="Agincourt North">Agincourt North</a>
    </td>, <td>M1V</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td>L'Amoreaux East
    </td>, <td>M1V</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a href="/wiki/Milliken,_Ontario" title="Milliken, Ontario">Milliken</a>
    </td>, <td>M1V</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td>Steeles East
    </td>, <td>M2V</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M3V</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M4V</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td><a href="/wiki/Deer_Park,_Toronto" title="Deer Park, Toronto">Deer Park</a>
    </td>, <td>M4V</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td>Forest Hill SE
    </td>, <td>M4V</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td><a class="mw-redirect" href="/wiki/Rathnelly" title="Rathnelly">Rathnelly</a>
    </td>, <td>M4V</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td><a href="/wiki/South_Hill,_Toronto" title="South Hill, Toronto">South Hill</a>
    </td>, <td>M4V</td>, <td><a class="mw-redirect" href="/wiki/Central_Toronto" title="Central Toronto">Central Toronto</a></td>, <td>Summerhill West
    </td>, <td>M5V</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/CN_Tower" title="CN Tower">CN Tower</a>
    </td>, <td>M5V</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Bathurst Quay
    </td>, <td>M5V</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Island airport
    </td>, <td>M5V</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Harbourfront West
    </td>, <td>M5V</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a class="mw-redirect" href="/wiki/King_and_Spadina" title="King and Spadina">King and Spadina</a>
    </td>, <td>M5V</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Railway_Lands" title="Railway Lands">Railway Lands</a>
    </td>, <td>M5V</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a class="mw-redirect" href="/wiki/South_Niagara" title="South Niagara">South Niagara</a>
    </td>, <td>M6V</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M7V</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8V</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Humber Bay Shores
    </td>, <td>M8V</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Mimico South
    </td>, <td>M8V</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/New_Toronto" title="New Toronto">New Toronto</a>
    </td>, <td>M9V</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Albion Gardens
    </td>, <td>M9V</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a class="mw-redirect" href="/wiki/Beaumond_Heights" title="Beaumond Heights">Beaumond Heights</a>
    </td>, <td>M9V</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Humbergate
    </td>, <td>M9V</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a class="mw-redirect" href="/wiki/Mount_Olive-Silverstone-Jamestown" title="Mount Olive-Silverstone-Jamestown">Jamestown</a>
    </td>, <td>M9V</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a class="mw-redirect" href="/wiki/Mount_Olive-Silverstone-Jamestown" title="Mount Olive-Silverstone-Jamestown">Mount Olive</a>
    </td>, <td>M9V</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a class="mw-redirect" href="/wiki/Silverstone,_Toronto" title="Silverstone, Toronto">Silverstone</a>
    </td>, <td>M9V</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a class="mw-redirect" href="/wiki/South_Steeles" title="South Steeles">South Steeles</a>
    </td>, <td>M9V</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/Thistletown" title="Thistletown">Thistletown</a>
    </td>, <td>M1W</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td>L'Amoreaux West
    </td>, <td>M2W</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M3W</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M4W</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Rosedale,_Toronto" title="Rosedale, Toronto">Rosedale</a>
    </td>, <td>M5W</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td>Stn A PO Boxes 25 The Esplanade
    </td>, <td>M6W</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M7W</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8W</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/Alderwood,_Toronto" title="Alderwood, Toronto">Alderwood</a>
    </td>, <td>M8W</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/Long_Branch,_Toronto" title="Long Branch, Toronto">Long Branch</a>
    </td>, <td>M9W</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Northwest
    </td>, <td>M1X</td>, <td><a href="/wiki/Scarborough,_Toronto" title="Scarborough, Toronto">Scarborough</a></td>, <td><a class="mw-redirect" href="/wiki/Upper_Rouge" title="Upper Rouge">Upper Rouge</a>
    </td>, <td>M2X</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M3X</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M4X</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Cabbagetown,_Toronto" title="Cabbagetown, Toronto">Cabbagetown</a>
    </td>, <td>M4X</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/St._James_Town" title="St. James Town">St. James Town</a>
    </td>, <td>M5X</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/First_Canadian_Place" title="First Canadian Place">First Canadian Place</a>
    </td>, <td>M5X</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Underground_city" title="Underground city">Underground city</a>
    </td>, <td>M6X</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M7X</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8X</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/The_Kingsway" title="The Kingsway">The Kingsway</a>
    </td>, <td>M8X</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Montgomery Road
    </td>, <td>M8X</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Old Mill North
    </td>, <td>M9X</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M1Y</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M2Y</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M3Y</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M4Y</td>, <td><a href="/wiki/Downtown_Toronto" title="Downtown Toronto">Downtown Toronto</a></td>, <td><a href="/wiki/Church_and_Wellesley" title="Church and Wellesley">Church and Wellesley</a>
    </td>, <td>M5Y</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M6Y</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M7Y</td>, <td><a href="/wiki/East_Toronto" title="East Toronto">East Toronto</a></td>, <td>Business Reply Mail Processing Centre 969 Eastern
    </td>, <td>M8Y</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/Humber_Bay" title="Humber Bay">Humber Bay</a>
    </td>, <td>M8Y</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>King's Mill Park
    </td>, <td>M8Y</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Kingsway Park South East
    </td>, <td>M8Y</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/Mimico" title="Mimico">Mimico NE</a>
    </td>, <td>M8Y</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/Old_Mill,_Toronto" title="Old Mill, Toronto">Old Mill South</a>
    </td>, <td>M8Y</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/The_Queensway" title="The Queensway">The Queensway East</a>
    </td>, <td>M8Y</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a class="mw-redirect" href="/wiki/Fairmont_Royal_York_Hotel" title="Fairmont Royal York Hotel">Royal York South East</a>
    </td>, <td>M8Y</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a class="mw-redirect" href="/wiki/Sunnylea" title="Sunnylea">Sunnylea</a>
    </td>, <td>M9Y</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M1Z</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M2Z</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M3Z</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M4Z</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M5Z</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M6Z</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M7Z</td>, <td>Not assigned</td>, <td>Not assigned
    </td>, <td>M8Z</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Kingsway Park South West
    </td>, <td>M8Z</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/Mimico" title="Mimico">Mimico NW</a>
    </td>, <td>M8Z</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td><a href="/wiki/The_Queensway" title="The Queensway">The Queensway West</a>
    </td>, <td>M8Z</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>Royal York South West
    </td>, <td>M8Z</td>, <td><a href="/wiki/Etobicoke" title="Etobicoke">Etobicoke</a></td>, <td>South of Bloor
    </td>, <td>M9Z</td>, <td>Not assigned</td>, <td>Not assigned
    </td>]
    


```python
Pos=[]
Bor=[]
Nei=[]
for n in range(0,len(table_value),3):
    Pos.append(table_value[n].text)
    Bor.append(table_value[n+1].text)
    Nei.append(table_value[n+2].text)
```


```python
for n in range(len(Nei)):
    Nei[n]=Nei[n][:-1]
Nei
```




    ['Not assigned',
     'Not assigned',
     'Parkwoods',
     'Victoria Village',
     'Harbourfront',
     'Regent Park',
     'Lawrence Heights',
     'Lawrence Manor',
     'Not assigned',
     'Not assigned',
     'Islington Avenue',
     'Rouge',
     'Malvern',
     'Not assigned',
     'Don Mills North',
     'Woodbine Gardens',
     'Parkview Hill',
     'Ryerson',
     'Garden District',
     'Glencairn',
     'Not assigned',
     'Not assigned',
     'Cloverdale',
     'Islington',
     'Martin Grove',
     'Princess Gardens',
     'West Deane Park',
     'Highland Creek',
     'Rouge Hill',
     'Port Union',
     'Not assigned',
     'Flemingdon Park',
     'Don Mills South',
     'Woodbine Heights',
     'St. James Town',
     'Humewood-Cedarvale',
     'Not assigned',
     'Not assigned',
     'Bloordale Gardens',
     'Eringate',
     'Markland Wood',
     'Old Burnhamthorpe',
     'Guildwood',
     'Morningside',
     'West Hill',
     'Not assigned',
     'Not assigned',
     'The Beaches',
     'Berczy Park',
     'Caledonia-Fairbanks',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Woburn',
     'Not assigned',
     'Not assigned',
     'Leaside',
     'Central Bay Street',
     'Christie',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Cedarbrae',
     'Hillcrest Village',
     'Bathurst Manor',
     'Downsview North',
     'Wilson Heights',
     'Thorncliffe Park',
     'Adelaide',
     'King',
     'Richmond',
     'Dovercourt Village',
     'Dufferin',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Scarborough Village',
     'Fairview',
     'Henry Farm',
     'Oriole',
     'Northwood Park',
     'York University',
     'East Toronto',
     'Harbourfront East',
     'Toronto Islands',
     'Union Station',
     'Little Portugal',
     'Trinity',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'East Birchmount Park',
     'Ionview',
     'Kennedy Park',
     'Bayview Village',
     'CFB Toronto',
     'Downsview East',
     'The Danforth West',
     'Riverdale',
     'Design Exchange',
     'Toronto Dominion Centre',
     'Brockton',
     'Exhibition Place',
     'Parkdale Village',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Clairlea',
     'Golden Mile',
     'Oakridge',
     'Silver Hills',
     'York Mills',
     'Downsview West',
     'The Beaches West',
     'India Bazaar',
     'Commerce Court',
     'Victoria Hotel',
     'Downsview',
     'North Park',
     'Upwood Park',
     'Not assigned',
     'Not assigned',
     'Humber Summit',
     'Cliffcrest',
     'Cliffside',
     'Scarborough Village West',
     'Newtonbrook',
     'Willowdale',
     'Downsview Central',
     'Studio District',
     'Bedford Park',
     'Lawrence Manor East',
     'Del Ray',
     'Keelesdale',
     'Mount Dennis',
     'Silverthorn',
     'Not assigned',
     'Not assigned',
     'Emery',
     'Humberlea',
     'Birch Cliff',
     'Cliffside West',
     'Willowdale South',
     'Downsview Northwest',
     'Lawrence Park',
     'Roselawn',
     'The Junction North',
     'Runnymede',
     'Not assigned',
     'Not assigned',
     'Weston',
     'Dorset Park',
     'Scarborough Town Centre',
     'Wexford Heights',
     'York Mills West',
     'Not assigned',
     'Davisville North',
     'Forest Hill North',
     'Forest Hill West',
     'High Park',
     'The Junction South',
     'Not assigned',
     'Not assigned',
     'Westmount',
     'Maryvale',
     'Wexford',
     'Willowdale West',
     'Not assigned',
     'North Toronto West',
     'The Annex',
     'North Midtown',
     'Yorkville',
     'Parkdale',
     'Roncesvalles',
     'Canada Post Gateway Processing Centre',
     'Not assigned',
     'Kingsview Village',
     'Martin Grove Gardens',
     'Richview Gardens',
     'St. Phillips',
     'Agincourt',
     'Not assigned',
     'Not assigned',
     'Davisville',
     'Harbord',
     'University of Toronto',
     'Runnymede',
     'Swansea',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Clarks Corners',
     'Sullivan',
     "Tam O'Shanter",
     'Not assigned',
     'Not assigned',
     'Moore Park',
     'Summerhill East',
     'Chinatown',
     'Grange Park',
     'Kensington Market',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Agincourt North',
     "L'Amoreaux East",
     'Milliken',
     'Steeles East',
     'Not assigned',
     'Not assigned',
     'Deer Park',
     'Forest Hill SE',
     'Rathnelly',
     'South Hill',
     'Summerhill West',
     'CN Tower',
     'Bathurst Quay',
     'Island airport',
     'Harbourfront West',
     'King and Spadina',
     'Railway Lands',
     'South Niagara',
     'Not assigned',
     'Not assigned',
     'Humber Bay Shores',
     'Mimico South',
     'New Toronto',
     'Albion Gardens',
     'Beaumond Heights',
     'Humbergate',
     'Jamestown',
     'Mount Olive',
     'Silverstone',
     'South Steeles',
     'Thistletown',
     "L'Amoreaux West",
     'Not assigned',
     'Not assigned',
     'Rosedale',
     'Stn A PO Boxes 25 The Esplanade',
     'Not assigned',
     'Not assigned',
     'Alderwood',
     'Long Branch',
     'Northwest',
     'Upper Rouge',
     'Not assigned',
     'Not assigned',
     'Cabbagetown',
     'St. James Town',
     'First Canadian Place',
     'Underground city',
     'Not assigned',
     'Not assigned',
     'The Kingsway',
     'Montgomery Road',
     'Old Mill North',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Church and Wellesley',
     'Not assigned',
     'Not assigned',
     'Business Reply Mail Processing Centre 969 Eastern',
     'Humber Bay',
     "King's Mill Park",
     'Kingsway Park South East',
     'Mimico NE',
     'Old Mill South',
     'The Queensway East',
     'Royal York South East',
     'Sunnylea',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Kingsway Park South West',
     'Mimico NW',
     'The Queensway West',
     'Royal York South West',
     'South of Bloor',
     'Not assigned']




```python
for i in range(len(Nei)):
    if Nei[i]=='Not assigned':
        Nei[i]=Bor[i]
Nei
```




    ['Not assigned',
     'Not assigned',
     'Parkwoods',
     'Victoria Village',
     'Harbourfront',
     'Regent Park',
     'Lawrence Heights',
     'Lawrence Manor',
     "Queen's Park",
     'Not assigned',
     'Islington Avenue',
     'Rouge',
     'Malvern',
     'Not assigned',
     'Don Mills North',
     'Woodbine Gardens',
     'Parkview Hill',
     'Ryerson',
     'Garden District',
     'Glencairn',
     'Not assigned',
     'Not assigned',
     'Cloverdale',
     'Islington',
     'Martin Grove',
     'Princess Gardens',
     'West Deane Park',
     'Highland Creek',
     'Rouge Hill',
     'Port Union',
     'Not assigned',
     'Flemingdon Park',
     'Don Mills South',
     'Woodbine Heights',
     'St. James Town',
     'Humewood-Cedarvale',
     'Not assigned',
     'Not assigned',
     'Bloordale Gardens',
     'Eringate',
     'Markland Wood',
     'Old Burnhamthorpe',
     'Guildwood',
     'Morningside',
     'West Hill',
     'Not assigned',
     'Not assigned',
     'The Beaches',
     'Berczy Park',
     'Caledonia-Fairbanks',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Woburn',
     'Not assigned',
     'Not assigned',
     'Leaside',
     'Central Bay Street',
     'Christie',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Cedarbrae',
     'Hillcrest Village',
     'Bathurst Manor',
     'Downsview North',
     'Wilson Heights',
     'Thorncliffe Park',
     'Adelaide',
     'King',
     'Richmond',
     'Dovercourt Village',
     'Dufferin',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Scarborough Village',
     'Fairview',
     'Henry Farm',
     'Oriole',
     'Northwood Park',
     'York University',
     'East Toronto',
     'Harbourfront East',
     'Toronto Islands',
     'Union Station',
     'Little Portugal',
     'Trinity',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'East Birchmount Park',
     'Ionview',
     'Kennedy Park',
     'Bayview Village',
     'CFB Toronto',
     'Downsview East',
     'The Danforth West',
     'Riverdale',
     'Design Exchange',
     'Toronto Dominion Centre',
     'Brockton',
     'Exhibition Place',
     'Parkdale Village',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Clairlea',
     'Golden Mile',
     'Oakridge',
     'Silver Hills',
     'York Mills',
     'Downsview West',
     'The Beaches West',
     'India Bazaar',
     'Commerce Court',
     'Victoria Hotel',
     'Downsview',
     'North Park',
     'Upwood Park',
     'Not assigned',
     'Not assigned',
     'Humber Summit',
     'Cliffcrest',
     'Cliffside',
     'Scarborough Village West',
     'Newtonbrook',
     'Willowdale',
     'Downsview Central',
     'Studio District',
     'Bedford Park',
     'Lawrence Manor East',
     'Del Ray',
     'Keelesdale',
     'Mount Dennis',
     'Silverthorn',
     'Not assigned',
     'Not assigned',
     'Emery',
     'Humberlea',
     'Birch Cliff',
     'Cliffside West',
     'Willowdale South',
     'Downsview Northwest',
     'Lawrence Park',
     'Roselawn',
     'The Junction North',
     'Runnymede',
     'Not assigned',
     'Not assigned',
     'Weston',
     'Dorset Park',
     'Scarborough Town Centre',
     'Wexford Heights',
     'York Mills West',
     'Not assigned',
     'Davisville North',
     'Forest Hill North',
     'Forest Hill West',
     'High Park',
     'The Junction South',
     'Not assigned',
     'Not assigned',
     'Westmount',
     'Maryvale',
     'Wexford',
     'Willowdale West',
     'Not assigned',
     'North Toronto West',
     'The Annex',
     'North Midtown',
     'Yorkville',
     'Parkdale',
     'Roncesvalles',
     'Canada Post Gateway Processing Centre',
     'Not assigned',
     'Kingsview Village',
     'Martin Grove Gardens',
     'Richview Gardens',
     'St. Phillips',
     'Agincourt',
     'Not assigned',
     'Not assigned',
     'Davisville',
     'Harbord',
     'University of Toronto',
     'Runnymede',
     'Swansea',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Clarks Corners',
     'Sullivan',
     "Tam O'Shanter",
     'Not assigned',
     'Not assigned',
     'Moore Park',
     'Summerhill East',
     'Chinatown',
     'Grange Park',
     'Kensington Market',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Agincourt North',
     "L'Amoreaux East",
     'Milliken',
     'Steeles East',
     'Not assigned',
     'Not assigned',
     'Deer Park',
     'Forest Hill SE',
     'Rathnelly',
     'South Hill',
     'Summerhill West',
     'CN Tower',
     'Bathurst Quay',
     'Island airport',
     'Harbourfront West',
     'King and Spadina',
     'Railway Lands',
     'South Niagara',
     'Not assigned',
     'Not assigned',
     'Humber Bay Shores',
     'Mimico South',
     'New Toronto',
     'Albion Gardens',
     'Beaumond Heights',
     'Humbergate',
     'Jamestown',
     'Mount Olive',
     'Silverstone',
     'South Steeles',
     'Thistletown',
     "L'Amoreaux West",
     'Not assigned',
     'Not assigned',
     'Rosedale',
     'Stn A PO Boxes 25 The Esplanade',
     'Not assigned',
     'Not assigned',
     'Alderwood',
     'Long Branch',
     'Northwest',
     'Upper Rouge',
     'Not assigned',
     'Not assigned',
     'Cabbagetown',
     'St. James Town',
     'First Canadian Place',
     'Underground city',
     'Not assigned',
     'Not assigned',
     'The Kingsway',
     'Montgomery Road',
     'Old Mill North',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Church and Wellesley',
     'Not assigned',
     'Not assigned',
     'Business Reply Mail Processing Centre 969 Eastern',
     'Humber Bay',
     "King's Mill Park",
     'Kingsway Park South East',
     'Mimico NE',
     'Old Mill South',
     'The Queensway East',
     'Royal York South East',
     'Sunnylea',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Not assigned',
     'Kingsway Park South West',
     'Mimico NW',
     'The Queensway West',
     'Royal York South West',
     'South of Bloor',
     'Not assigned']




```python
final_array=[]
for pos, bor,nei in zip(Pos,Bor,Nei):
    final_array.append({header_items[0]:pos,header_items[1]:bor,header_items[2]:nei})
```


```python
import pandas as pd
df= pd.DataFrame(final_array)
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Borough</th>
      <th>Neighbourhood</th>
      <th>Postcode</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M1A</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M2A</td>
    </tr>
    <tr>
      <th>2</th>
      <td>North York</td>
      <td>Parkwoods</td>
      <td>M3A</td>
    </tr>
    <tr>
      <th>3</th>
      <td>North York</td>
      <td>Victoria Village</td>
      <td>M4A</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Downtown Toronto</td>
      <td>Harbourfront</td>
      <td>M5A</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Downtown Toronto</td>
      <td>Regent Park</td>
      <td>M5A</td>
    </tr>
    <tr>
      <th>6</th>
      <td>North York</td>
      <td>Lawrence Heights</td>
      <td>M6A</td>
    </tr>
    <tr>
      <th>7</th>
      <td>North York</td>
      <td>Lawrence Manor</td>
      <td>M6A</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Queen's Park</td>
      <td>Queen's Park</td>
      <td>M7A</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M8A</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Etobicoke</td>
      <td>Islington Avenue</td>
      <td>M9A</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Scarborough</td>
      <td>Rouge</td>
      <td>M1B</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Scarborough</td>
      <td>Malvern</td>
      <td>M1B</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M2B</td>
    </tr>
    <tr>
      <th>14</th>
      <td>North York</td>
      <td>Don Mills North</td>
      <td>M3B</td>
    </tr>
    <tr>
      <th>15</th>
      <td>East York</td>
      <td>Woodbine Gardens</td>
      <td>M4B</td>
    </tr>
    <tr>
      <th>16</th>
      <td>East York</td>
      <td>Parkview Hill</td>
      <td>M4B</td>
    </tr>
    <tr>
      <th>17</th>
      <td>Downtown Toronto</td>
      <td>Ryerson</td>
      <td>M5B</td>
    </tr>
    <tr>
      <th>18</th>
      <td>Downtown Toronto</td>
      <td>Garden District</td>
      <td>M5B</td>
    </tr>
    <tr>
      <th>19</th>
      <td>North York</td>
      <td>Glencairn</td>
      <td>M6B</td>
    </tr>
    <tr>
      <th>20</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M7B</td>
    </tr>
    <tr>
      <th>21</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M8B</td>
    </tr>
    <tr>
      <th>22</th>
      <td>Etobicoke</td>
      <td>Cloverdale</td>
      <td>M9B</td>
    </tr>
    <tr>
      <th>23</th>
      <td>Etobicoke</td>
      <td>Islington</td>
      <td>M9B</td>
    </tr>
    <tr>
      <th>24</th>
      <td>Etobicoke</td>
      <td>Martin Grove</td>
      <td>M9B</td>
    </tr>
    <tr>
      <th>25</th>
      <td>Etobicoke</td>
      <td>Princess Gardens</td>
      <td>M9B</td>
    </tr>
    <tr>
      <th>26</th>
      <td>Etobicoke</td>
      <td>West Deane Park</td>
      <td>M9B</td>
    </tr>
    <tr>
      <th>27</th>
      <td>Scarborough</td>
      <td>Highland Creek</td>
      <td>M1C</td>
    </tr>
    <tr>
      <th>28</th>
      <td>Scarborough</td>
      <td>Rouge Hill</td>
      <td>M1C</td>
    </tr>
    <tr>
      <th>29</th>
      <td>Scarborough</td>
      <td>Port Union</td>
      <td>M1C</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>258</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M9X</td>
    </tr>
    <tr>
      <th>259</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M1Y</td>
    </tr>
    <tr>
      <th>260</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M2Y</td>
    </tr>
    <tr>
      <th>261</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M3Y</td>
    </tr>
    <tr>
      <th>262</th>
      <td>Downtown Toronto</td>
      <td>Church and Wellesley</td>
      <td>M4Y</td>
    </tr>
    <tr>
      <th>263</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M5Y</td>
    </tr>
    <tr>
      <th>264</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M6Y</td>
    </tr>
    <tr>
      <th>265</th>
      <td>East Toronto</td>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>M7Y</td>
    </tr>
    <tr>
      <th>266</th>
      <td>Etobicoke</td>
      <td>Humber Bay</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>267</th>
      <td>Etobicoke</td>
      <td>King's Mill Park</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>268</th>
      <td>Etobicoke</td>
      <td>Kingsway Park South East</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>269</th>
      <td>Etobicoke</td>
      <td>Mimico NE</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>270</th>
      <td>Etobicoke</td>
      <td>Old Mill South</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>271</th>
      <td>Etobicoke</td>
      <td>The Queensway East</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>272</th>
      <td>Etobicoke</td>
      <td>Royal York South East</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>273</th>
      <td>Etobicoke</td>
      <td>Sunnylea</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>274</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M9Y</td>
    </tr>
    <tr>
      <th>275</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M1Z</td>
    </tr>
    <tr>
      <th>276</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M2Z</td>
    </tr>
    <tr>
      <th>277</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M3Z</td>
    </tr>
    <tr>
      <th>278</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M4Z</td>
    </tr>
    <tr>
      <th>279</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M5Z</td>
    </tr>
    <tr>
      <th>280</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M6Z</td>
    </tr>
    <tr>
      <th>281</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M7Z</td>
    </tr>
    <tr>
      <th>282</th>
      <td>Etobicoke</td>
      <td>Kingsway Park South West</td>
      <td>M8Z</td>
    </tr>
    <tr>
      <th>283</th>
      <td>Etobicoke</td>
      <td>Mimico NW</td>
      <td>M8Z</td>
    </tr>
    <tr>
      <th>284</th>
      <td>Etobicoke</td>
      <td>The Queensway West</td>
      <td>M8Z</td>
    </tr>
    <tr>
      <th>285</th>
      <td>Etobicoke</td>
      <td>Royal York South West</td>
      <td>M8Z</td>
    </tr>
    <tr>
      <th>286</th>
      <td>Etobicoke</td>
      <td>South of Bloor</td>
      <td>M8Z</td>
    </tr>
    <tr>
      <th>287</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M9Z</td>
    </tr>
  </tbody>
</table>
<p>288 rows × 3 columns</p>
</div>




```python
df.rename(columns={'Postcode':'PostalCode','Neighbourhood':'Neighborhood'},inplace=True)
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Borough</th>
      <th>Neighborhood</th>
      <th>PostalCode</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M1A</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M2A</td>
    </tr>
    <tr>
      <th>2</th>
      <td>North York</td>
      <td>Parkwoods</td>
      <td>M3A</td>
    </tr>
    <tr>
      <th>3</th>
      <td>North York</td>
      <td>Victoria Village</td>
      <td>M4A</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Downtown Toronto</td>
      <td>Harbourfront</td>
      <td>M5A</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Downtown Toronto</td>
      <td>Regent Park</td>
      <td>M5A</td>
    </tr>
    <tr>
      <th>6</th>
      <td>North York</td>
      <td>Lawrence Heights</td>
      <td>M6A</td>
    </tr>
    <tr>
      <th>7</th>
      <td>North York</td>
      <td>Lawrence Manor</td>
      <td>M6A</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Queen's Park</td>
      <td>Queen's Park</td>
      <td>M7A</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M8A</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Etobicoke</td>
      <td>Islington Avenue</td>
      <td>M9A</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Scarborough</td>
      <td>Rouge</td>
      <td>M1B</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Scarborough</td>
      <td>Malvern</td>
      <td>M1B</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M2B</td>
    </tr>
    <tr>
      <th>14</th>
      <td>North York</td>
      <td>Don Mills North</td>
      <td>M3B</td>
    </tr>
    <tr>
      <th>15</th>
      <td>East York</td>
      <td>Woodbine Gardens</td>
      <td>M4B</td>
    </tr>
    <tr>
      <th>16</th>
      <td>East York</td>
      <td>Parkview Hill</td>
      <td>M4B</td>
    </tr>
    <tr>
      <th>17</th>
      <td>Downtown Toronto</td>
      <td>Ryerson</td>
      <td>M5B</td>
    </tr>
    <tr>
      <th>18</th>
      <td>Downtown Toronto</td>
      <td>Garden District</td>
      <td>M5B</td>
    </tr>
    <tr>
      <th>19</th>
      <td>North York</td>
      <td>Glencairn</td>
      <td>M6B</td>
    </tr>
    <tr>
      <th>20</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M7B</td>
    </tr>
    <tr>
      <th>21</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M8B</td>
    </tr>
    <tr>
      <th>22</th>
      <td>Etobicoke</td>
      <td>Cloverdale</td>
      <td>M9B</td>
    </tr>
    <tr>
      <th>23</th>
      <td>Etobicoke</td>
      <td>Islington</td>
      <td>M9B</td>
    </tr>
    <tr>
      <th>24</th>
      <td>Etobicoke</td>
      <td>Martin Grove</td>
      <td>M9B</td>
    </tr>
    <tr>
      <th>25</th>
      <td>Etobicoke</td>
      <td>Princess Gardens</td>
      <td>M9B</td>
    </tr>
    <tr>
      <th>26</th>
      <td>Etobicoke</td>
      <td>West Deane Park</td>
      <td>M9B</td>
    </tr>
    <tr>
      <th>27</th>
      <td>Scarborough</td>
      <td>Highland Creek</td>
      <td>M1C</td>
    </tr>
    <tr>
      <th>28</th>
      <td>Scarborough</td>
      <td>Rouge Hill</td>
      <td>M1C</td>
    </tr>
    <tr>
      <th>29</th>
      <td>Scarborough</td>
      <td>Port Union</td>
      <td>M1C</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>258</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M9X</td>
    </tr>
    <tr>
      <th>259</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M1Y</td>
    </tr>
    <tr>
      <th>260</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M2Y</td>
    </tr>
    <tr>
      <th>261</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M3Y</td>
    </tr>
    <tr>
      <th>262</th>
      <td>Downtown Toronto</td>
      <td>Church and Wellesley</td>
      <td>M4Y</td>
    </tr>
    <tr>
      <th>263</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M5Y</td>
    </tr>
    <tr>
      <th>264</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M6Y</td>
    </tr>
    <tr>
      <th>265</th>
      <td>East Toronto</td>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>M7Y</td>
    </tr>
    <tr>
      <th>266</th>
      <td>Etobicoke</td>
      <td>Humber Bay</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>267</th>
      <td>Etobicoke</td>
      <td>King's Mill Park</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>268</th>
      <td>Etobicoke</td>
      <td>Kingsway Park South East</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>269</th>
      <td>Etobicoke</td>
      <td>Mimico NE</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>270</th>
      <td>Etobicoke</td>
      <td>Old Mill South</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>271</th>
      <td>Etobicoke</td>
      <td>The Queensway East</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>272</th>
      <td>Etobicoke</td>
      <td>Royal York South East</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>273</th>
      <td>Etobicoke</td>
      <td>Sunnylea</td>
      <td>M8Y</td>
    </tr>
    <tr>
      <th>274</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M9Y</td>
    </tr>
    <tr>
      <th>275</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M1Z</td>
    </tr>
    <tr>
      <th>276</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M2Z</td>
    </tr>
    <tr>
      <th>277</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M3Z</td>
    </tr>
    <tr>
      <th>278</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M4Z</td>
    </tr>
    <tr>
      <th>279</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M5Z</td>
    </tr>
    <tr>
      <th>280</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M6Z</td>
    </tr>
    <tr>
      <th>281</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M7Z</td>
    </tr>
    <tr>
      <th>282</th>
      <td>Etobicoke</td>
      <td>Kingsway Park South West</td>
      <td>M8Z</td>
    </tr>
    <tr>
      <th>283</th>
      <td>Etobicoke</td>
      <td>Mimico NW</td>
      <td>M8Z</td>
    </tr>
    <tr>
      <th>284</th>
      <td>Etobicoke</td>
      <td>The Queensway West</td>
      <td>M8Z</td>
    </tr>
    <tr>
      <th>285</th>
      <td>Etobicoke</td>
      <td>Royal York South West</td>
      <td>M8Z</td>
    </tr>
    <tr>
      <th>286</th>
      <td>Etobicoke</td>
      <td>South of Bloor</td>
      <td>M8Z</td>
    </tr>
    <tr>
      <th>287</th>
      <td>Not assigned</td>
      <td>Not assigned</td>
      <td>M9Z</td>
    </tr>
  </tbody>
</table>
<p>288 rows × 3 columns</p>
</div>




```python
df=df[['PostalCode','Borough','Neighborhood']]
df=df[df['Borough']!='Not assigned']
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>PostalCode</th>
      <th>Borough</th>
      <th>Neighborhood</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2</th>
      <td>M3A</td>
      <td>North York</td>
      <td>Parkwoods</td>
    </tr>
    <tr>
      <th>3</th>
      <td>M4A</td>
      <td>North York</td>
      <td>Victoria Village</td>
    </tr>
    <tr>
      <th>4</th>
      <td>M5A</td>
      <td>Downtown Toronto</td>
      <td>Harbourfront</td>
    </tr>
    <tr>
      <th>5</th>
      <td>M5A</td>
      <td>Downtown Toronto</td>
      <td>Regent Park</td>
    </tr>
    <tr>
      <th>6</th>
      <td>M6A</td>
      <td>North York</td>
      <td>Lawrence Heights</td>
    </tr>
    <tr>
      <th>7</th>
      <td>M6A</td>
      <td>North York</td>
      <td>Lawrence Manor</td>
    </tr>
    <tr>
      <th>8</th>
      <td>M7A</td>
      <td>Queen's Park</td>
      <td>Queen's Park</td>
    </tr>
    <tr>
      <th>10</th>
      <td>M9A</td>
      <td>Etobicoke</td>
      <td>Islington Avenue</td>
    </tr>
    <tr>
      <th>11</th>
      <td>M1B</td>
      <td>Scarborough</td>
      <td>Rouge</td>
    </tr>
    <tr>
      <th>12</th>
      <td>M1B</td>
      <td>Scarborough</td>
      <td>Malvern</td>
    </tr>
    <tr>
      <th>14</th>
      <td>M3B</td>
      <td>North York</td>
      <td>Don Mills North</td>
    </tr>
    <tr>
      <th>15</th>
      <td>M4B</td>
      <td>East York</td>
      <td>Woodbine Gardens</td>
    </tr>
    <tr>
      <th>16</th>
      <td>M4B</td>
      <td>East York</td>
      <td>Parkview Hill</td>
    </tr>
    <tr>
      <th>17</th>
      <td>M5B</td>
      <td>Downtown Toronto</td>
      <td>Ryerson</td>
    </tr>
    <tr>
      <th>18</th>
      <td>M5B</td>
      <td>Downtown Toronto</td>
      <td>Garden District</td>
    </tr>
    <tr>
      <th>19</th>
      <td>M6B</td>
      <td>North York</td>
      <td>Glencairn</td>
    </tr>
    <tr>
      <th>22</th>
      <td>M9B</td>
      <td>Etobicoke</td>
      <td>Cloverdale</td>
    </tr>
    <tr>
      <th>23</th>
      <td>M9B</td>
      <td>Etobicoke</td>
      <td>Islington</td>
    </tr>
    <tr>
      <th>24</th>
      <td>M9B</td>
      <td>Etobicoke</td>
      <td>Martin Grove</td>
    </tr>
    <tr>
      <th>25</th>
      <td>M9B</td>
      <td>Etobicoke</td>
      <td>Princess Gardens</td>
    </tr>
    <tr>
      <th>26</th>
      <td>M9B</td>
      <td>Etobicoke</td>
      <td>West Deane Park</td>
    </tr>
    <tr>
      <th>27</th>
      <td>M1C</td>
      <td>Scarborough</td>
      <td>Highland Creek</td>
    </tr>
    <tr>
      <th>28</th>
      <td>M1C</td>
      <td>Scarborough</td>
      <td>Rouge Hill</td>
    </tr>
    <tr>
      <th>29</th>
      <td>M1C</td>
      <td>Scarborough</td>
      <td>Port Union</td>
    </tr>
    <tr>
      <th>31</th>
      <td>M3C</td>
      <td>North York</td>
      <td>Flemingdon Park</td>
    </tr>
    <tr>
      <th>32</th>
      <td>M3C</td>
      <td>North York</td>
      <td>Don Mills South</td>
    </tr>
    <tr>
      <th>33</th>
      <td>M4C</td>
      <td>East York</td>
      <td>Woodbine Heights</td>
    </tr>
    <tr>
      <th>34</th>
      <td>M5C</td>
      <td>Downtown Toronto</td>
      <td>St. James Town</td>
    </tr>
    <tr>
      <th>35</th>
      <td>M6C</td>
      <td>York</td>
      <td>Humewood-Cedarvale</td>
    </tr>
    <tr>
      <th>38</th>
      <td>M9C</td>
      <td>Etobicoke</td>
      <td>Bloordale Gardens</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>235</th>
      <td>M9V</td>
      <td>Etobicoke</td>
      <td>Thistletown</td>
    </tr>
    <tr>
      <th>236</th>
      <td>M1W</td>
      <td>Scarborough</td>
      <td>L'Amoreaux West</td>
    </tr>
    <tr>
      <th>239</th>
      <td>M4W</td>
      <td>Downtown Toronto</td>
      <td>Rosedale</td>
    </tr>
    <tr>
      <th>240</th>
      <td>M5W</td>
      <td>Downtown Toronto</td>
      <td>Stn A PO Boxes 25 The Esplanade</td>
    </tr>
    <tr>
      <th>243</th>
      <td>M8W</td>
      <td>Etobicoke</td>
      <td>Alderwood</td>
    </tr>
    <tr>
      <th>244</th>
      <td>M8W</td>
      <td>Etobicoke</td>
      <td>Long Branch</td>
    </tr>
    <tr>
      <th>245</th>
      <td>M9W</td>
      <td>Etobicoke</td>
      <td>Northwest</td>
    </tr>
    <tr>
      <th>246</th>
      <td>M1X</td>
      <td>Scarborough</td>
      <td>Upper Rouge</td>
    </tr>
    <tr>
      <th>249</th>
      <td>M4X</td>
      <td>Downtown Toronto</td>
      <td>Cabbagetown</td>
    </tr>
    <tr>
      <th>250</th>
      <td>M4X</td>
      <td>Downtown Toronto</td>
      <td>St. James Town</td>
    </tr>
    <tr>
      <th>251</th>
      <td>M5X</td>
      <td>Downtown Toronto</td>
      <td>First Canadian Place</td>
    </tr>
    <tr>
      <th>252</th>
      <td>M5X</td>
      <td>Downtown Toronto</td>
      <td>Underground city</td>
    </tr>
    <tr>
      <th>255</th>
      <td>M8X</td>
      <td>Etobicoke</td>
      <td>The Kingsway</td>
    </tr>
    <tr>
      <th>256</th>
      <td>M8X</td>
      <td>Etobicoke</td>
      <td>Montgomery Road</td>
    </tr>
    <tr>
      <th>257</th>
      <td>M8X</td>
      <td>Etobicoke</td>
      <td>Old Mill North</td>
    </tr>
    <tr>
      <th>262</th>
      <td>M4Y</td>
      <td>Downtown Toronto</td>
      <td>Church and Wellesley</td>
    </tr>
    <tr>
      <th>265</th>
      <td>M7Y</td>
      <td>East Toronto</td>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
    </tr>
    <tr>
      <th>266</th>
      <td>M8Y</td>
      <td>Etobicoke</td>
      <td>Humber Bay</td>
    </tr>
    <tr>
      <th>267</th>
      <td>M8Y</td>
      <td>Etobicoke</td>
      <td>King's Mill Park</td>
    </tr>
    <tr>
      <th>268</th>
      <td>M8Y</td>
      <td>Etobicoke</td>
      <td>Kingsway Park South East</td>
    </tr>
    <tr>
      <th>269</th>
      <td>M8Y</td>
      <td>Etobicoke</td>
      <td>Mimico NE</td>
    </tr>
    <tr>
      <th>270</th>
      <td>M8Y</td>
      <td>Etobicoke</td>
      <td>Old Mill South</td>
    </tr>
    <tr>
      <th>271</th>
      <td>M8Y</td>
      <td>Etobicoke</td>
      <td>The Queensway East</td>
    </tr>
    <tr>
      <th>272</th>
      <td>M8Y</td>
      <td>Etobicoke</td>
      <td>Royal York South East</td>
    </tr>
    <tr>
      <th>273</th>
      <td>M8Y</td>
      <td>Etobicoke</td>
      <td>Sunnylea</td>
    </tr>
    <tr>
      <th>282</th>
      <td>M8Z</td>
      <td>Etobicoke</td>
      <td>Kingsway Park South West</td>
    </tr>
    <tr>
      <th>283</th>
      <td>M8Z</td>
      <td>Etobicoke</td>
      <td>Mimico NW</td>
    </tr>
    <tr>
      <th>284</th>
      <td>M8Z</td>
      <td>Etobicoke</td>
      <td>The Queensway West</td>
    </tr>
    <tr>
      <th>285</th>
      <td>M8Z</td>
      <td>Etobicoke</td>
      <td>Royal York South West</td>
    </tr>
    <tr>
      <th>286</th>
      <td>M8Z</td>
      <td>Etobicoke</td>
      <td>South of Bloor</td>
    </tr>
  </tbody>
</table>
<p>211 rows × 3 columns</p>
</div>




```python
def combine(df):
    return ','.join(df.values)
df2=df.groupby(['PostalCode','Borough'])['Neighborhood'].apply(combine)
df2=df2.to_frame()
df2.reset_index(inplace=True)
df2
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>PostalCode</th>
      <th>Borough</th>
      <th>Neighborhood</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>M1B</td>
      <td>Scarborough</td>
      <td>Rouge,Malvern</td>
    </tr>
    <tr>
      <th>1</th>
      <td>M1C</td>
      <td>Scarborough</td>
      <td>Highland Creek,Rouge Hill,Port Union</td>
    </tr>
    <tr>
      <th>2</th>
      <td>M1E</td>
      <td>Scarborough</td>
      <td>Guildwood,Morningside,West Hill</td>
    </tr>
    <tr>
      <th>3</th>
      <td>M1G</td>
      <td>Scarborough</td>
      <td>Woburn</td>
    </tr>
    <tr>
      <th>4</th>
      <td>M1H</td>
      <td>Scarborough</td>
      <td>Cedarbrae</td>
    </tr>
    <tr>
      <th>5</th>
      <td>M1J</td>
      <td>Scarborough</td>
      <td>Scarborough Village</td>
    </tr>
    <tr>
      <th>6</th>
      <td>M1K</td>
      <td>Scarborough</td>
      <td>East Birchmount Park,Ionview,Kennedy Park</td>
    </tr>
    <tr>
      <th>7</th>
      <td>M1L</td>
      <td>Scarborough</td>
      <td>Clairlea,Golden Mile,Oakridge</td>
    </tr>
    <tr>
      <th>8</th>
      <td>M1M</td>
      <td>Scarborough</td>
      <td>Cliffcrest,Cliffside,Scarborough Village West</td>
    </tr>
    <tr>
      <th>9</th>
      <td>M1N</td>
      <td>Scarborough</td>
      <td>Birch Cliff,Cliffside West</td>
    </tr>
    <tr>
      <th>10</th>
      <td>M1P</td>
      <td>Scarborough</td>
      <td>Dorset Park,Scarborough Town Centre,Wexford He...</td>
    </tr>
    <tr>
      <th>11</th>
      <td>M1R</td>
      <td>Scarborough</td>
      <td>Maryvale,Wexford</td>
    </tr>
    <tr>
      <th>12</th>
      <td>M1S</td>
      <td>Scarborough</td>
      <td>Agincourt</td>
    </tr>
    <tr>
      <th>13</th>
      <td>M1T</td>
      <td>Scarborough</td>
      <td>Clarks Corners,Sullivan,Tam O'Shanter</td>
    </tr>
    <tr>
      <th>14</th>
      <td>M1V</td>
      <td>Scarborough</td>
      <td>Agincourt North,L'Amoreaux East,Milliken,Steel...</td>
    </tr>
    <tr>
      <th>15</th>
      <td>M1W</td>
      <td>Scarborough</td>
      <td>L'Amoreaux West</td>
    </tr>
    <tr>
      <th>16</th>
      <td>M1X</td>
      <td>Scarborough</td>
      <td>Upper Rouge</td>
    </tr>
    <tr>
      <th>17</th>
      <td>M2H</td>
      <td>North York</td>
      <td>Hillcrest Village</td>
    </tr>
    <tr>
      <th>18</th>
      <td>M2J</td>
      <td>North York</td>
      <td>Fairview,Henry Farm,Oriole</td>
    </tr>
    <tr>
      <th>19</th>
      <td>M2K</td>
      <td>North York</td>
      <td>Bayview Village</td>
    </tr>
    <tr>
      <th>20</th>
      <td>M2L</td>
      <td>North York</td>
      <td>Silver Hills,York Mills</td>
    </tr>
    <tr>
      <th>21</th>
      <td>M2M</td>
      <td>North York</td>
      <td>Newtonbrook,Willowdale</td>
    </tr>
    <tr>
      <th>22</th>
      <td>M2N</td>
      <td>North York</td>
      <td>Willowdale South</td>
    </tr>
    <tr>
      <th>23</th>
      <td>M2P</td>
      <td>North York</td>
      <td>York Mills West</td>
    </tr>
    <tr>
      <th>24</th>
      <td>M2R</td>
      <td>North York</td>
      <td>Willowdale West</td>
    </tr>
    <tr>
      <th>25</th>
      <td>M3A</td>
      <td>North York</td>
      <td>Parkwoods</td>
    </tr>
    <tr>
      <th>26</th>
      <td>M3B</td>
      <td>North York</td>
      <td>Don Mills North</td>
    </tr>
    <tr>
      <th>27</th>
      <td>M3C</td>
      <td>North York</td>
      <td>Flemingdon Park,Don Mills South</td>
    </tr>
    <tr>
      <th>28</th>
      <td>M3H</td>
      <td>North York</td>
      <td>Bathurst Manor,Downsview North,Wilson Heights</td>
    </tr>
    <tr>
      <th>29</th>
      <td>M3J</td>
      <td>North York</td>
      <td>Northwood Park,York University</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>73</th>
      <td>M6C</td>
      <td>York</td>
      <td>Humewood-Cedarvale</td>
    </tr>
    <tr>
      <th>74</th>
      <td>M6E</td>
      <td>York</td>
      <td>Caledonia-Fairbanks</td>
    </tr>
    <tr>
      <th>75</th>
      <td>M6G</td>
      <td>Downtown Toronto</td>
      <td>Christie</td>
    </tr>
    <tr>
      <th>76</th>
      <td>M6H</td>
      <td>West Toronto</td>
      <td>Dovercourt Village,Dufferin</td>
    </tr>
    <tr>
      <th>77</th>
      <td>M6J</td>
      <td>West Toronto</td>
      <td>Little Portugal,Trinity</td>
    </tr>
    <tr>
      <th>78</th>
      <td>M6K</td>
      <td>West Toronto</td>
      <td>Brockton,Exhibition Place,Parkdale Village</td>
    </tr>
    <tr>
      <th>79</th>
      <td>M6L</td>
      <td>North York</td>
      <td>Downsview,North Park,Upwood Park</td>
    </tr>
    <tr>
      <th>80</th>
      <td>M6M</td>
      <td>York</td>
      <td>Del Ray,Keelesdale,Mount Dennis,Silverthorn</td>
    </tr>
    <tr>
      <th>81</th>
      <td>M6N</td>
      <td>York</td>
      <td>The Junction North,Runnymede</td>
    </tr>
    <tr>
      <th>82</th>
      <td>M6P</td>
      <td>West Toronto</td>
      <td>High Park,The Junction South</td>
    </tr>
    <tr>
      <th>83</th>
      <td>M6R</td>
      <td>West Toronto</td>
      <td>Parkdale,Roncesvalles</td>
    </tr>
    <tr>
      <th>84</th>
      <td>M6S</td>
      <td>West Toronto</td>
      <td>Runnymede,Swansea</td>
    </tr>
    <tr>
      <th>85</th>
      <td>M7A</td>
      <td>Queen's Park</td>
      <td>Queen's Park</td>
    </tr>
    <tr>
      <th>86</th>
      <td>M7R</td>
      <td>Mississauga</td>
      <td>Canada Post Gateway Processing Centre</td>
    </tr>
    <tr>
      <th>87</th>
      <td>M7Y</td>
      <td>East Toronto</td>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
    </tr>
    <tr>
      <th>88</th>
      <td>M8V</td>
      <td>Etobicoke</td>
      <td>Humber Bay Shores,Mimico South,New Toronto</td>
    </tr>
    <tr>
      <th>89</th>
      <td>M8W</td>
      <td>Etobicoke</td>
      <td>Alderwood,Long Branch</td>
    </tr>
    <tr>
      <th>90</th>
      <td>M8X</td>
      <td>Etobicoke</td>
      <td>The Kingsway,Montgomery Road,Old Mill North</td>
    </tr>
    <tr>
      <th>91</th>
      <td>M8Y</td>
      <td>Etobicoke</td>
      <td>Humber Bay,King's Mill Park,Kingsway Park Sout...</td>
    </tr>
    <tr>
      <th>92</th>
      <td>M8Z</td>
      <td>Etobicoke</td>
      <td>Kingsway Park South West,Mimico NW,The Queensw...</td>
    </tr>
    <tr>
      <th>93</th>
      <td>M9A</td>
      <td>Etobicoke</td>
      <td>Islington Avenue</td>
    </tr>
    <tr>
      <th>94</th>
      <td>M9B</td>
      <td>Etobicoke</td>
      <td>Cloverdale,Islington,Martin Grove,Princess Gar...</td>
    </tr>
    <tr>
      <th>95</th>
      <td>M9C</td>
      <td>Etobicoke</td>
      <td>Bloordale Gardens,Eringate,Markland Wood,Old B...</td>
    </tr>
    <tr>
      <th>96</th>
      <td>M9L</td>
      <td>North York</td>
      <td>Humber Summit</td>
    </tr>
    <tr>
      <th>97</th>
      <td>M9M</td>
      <td>North York</td>
      <td>Emery,Humberlea</td>
    </tr>
    <tr>
      <th>98</th>
      <td>M9N</td>
      <td>York</td>
      <td>Weston</td>
    </tr>
    <tr>
      <th>99</th>
      <td>M9P</td>
      <td>Etobicoke</td>
      <td>Westmount</td>
    </tr>
    <tr>
      <th>100</th>
      <td>M9R</td>
      <td>Etobicoke</td>
      <td>Kingsview Village,Martin Grove Gardens,Richvie...</td>
    </tr>
    <tr>
      <th>101</th>
      <td>M9V</td>
      <td>Etobicoke</td>
      <td>Albion Gardens,Beaumond Heights,Humbergate,Jam...</td>
    </tr>
    <tr>
      <th>102</th>
      <td>M9W</td>
      <td>Etobicoke</td>
      <td>Northwest</td>
    </tr>
  </tbody>
</table>
<p>103 rows × 3 columns</p>
</div>




```python
df2.shape
```




    (103, 3)



The table of postal codes contains 103 distinct rows.

# Use the Geocoder csv file to create a new dataframe with latitude and longitude:


```python
df_cd=pd.read_csv('https://cocl.us/Geospatial_data')
df_cd.rename(columns={'Postal Code':'PostalCode'},inplace=True)
df_cd
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>PostalCode</th>
      <th>Latitude</th>
      <th>Longitude</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>M1B</td>
      <td>43.806686</td>
      <td>-79.194353</td>
    </tr>
    <tr>
      <th>1</th>
      <td>M1C</td>
      <td>43.784535</td>
      <td>-79.160497</td>
    </tr>
    <tr>
      <th>2</th>
      <td>M1E</td>
      <td>43.763573</td>
      <td>-79.188711</td>
    </tr>
    <tr>
      <th>3</th>
      <td>M1G</td>
      <td>43.770992</td>
      <td>-79.216917</td>
    </tr>
    <tr>
      <th>4</th>
      <td>M1H</td>
      <td>43.773136</td>
      <td>-79.239476</td>
    </tr>
    <tr>
      <th>5</th>
      <td>M1J</td>
      <td>43.744734</td>
      <td>-79.239476</td>
    </tr>
    <tr>
      <th>6</th>
      <td>M1K</td>
      <td>43.727929</td>
      <td>-79.262029</td>
    </tr>
    <tr>
      <th>7</th>
      <td>M1L</td>
      <td>43.711112</td>
      <td>-79.284577</td>
    </tr>
    <tr>
      <th>8</th>
      <td>M1M</td>
      <td>43.716316</td>
      <td>-79.239476</td>
    </tr>
    <tr>
      <th>9</th>
      <td>M1N</td>
      <td>43.692657</td>
      <td>-79.264848</td>
    </tr>
    <tr>
      <th>10</th>
      <td>M1P</td>
      <td>43.757410</td>
      <td>-79.273304</td>
    </tr>
    <tr>
      <th>11</th>
      <td>M1R</td>
      <td>43.750072</td>
      <td>-79.295849</td>
    </tr>
    <tr>
      <th>12</th>
      <td>M1S</td>
      <td>43.794200</td>
      <td>-79.262029</td>
    </tr>
    <tr>
      <th>13</th>
      <td>M1T</td>
      <td>43.781638</td>
      <td>-79.304302</td>
    </tr>
    <tr>
      <th>14</th>
      <td>M1V</td>
      <td>43.815252</td>
      <td>-79.284577</td>
    </tr>
    <tr>
      <th>15</th>
      <td>M1W</td>
      <td>43.799525</td>
      <td>-79.318389</td>
    </tr>
    <tr>
      <th>16</th>
      <td>M1X</td>
      <td>43.836125</td>
      <td>-79.205636</td>
    </tr>
    <tr>
      <th>17</th>
      <td>M2H</td>
      <td>43.803762</td>
      <td>-79.363452</td>
    </tr>
    <tr>
      <th>18</th>
      <td>M2J</td>
      <td>43.778517</td>
      <td>-79.346556</td>
    </tr>
    <tr>
      <th>19</th>
      <td>M2K</td>
      <td>43.786947</td>
      <td>-79.385975</td>
    </tr>
    <tr>
      <th>20</th>
      <td>M2L</td>
      <td>43.757490</td>
      <td>-79.374714</td>
    </tr>
    <tr>
      <th>21</th>
      <td>M2M</td>
      <td>43.789053</td>
      <td>-79.408493</td>
    </tr>
    <tr>
      <th>22</th>
      <td>M2N</td>
      <td>43.770120</td>
      <td>-79.408493</td>
    </tr>
    <tr>
      <th>23</th>
      <td>M2P</td>
      <td>43.752758</td>
      <td>-79.400049</td>
    </tr>
    <tr>
      <th>24</th>
      <td>M2R</td>
      <td>43.782736</td>
      <td>-79.442259</td>
    </tr>
    <tr>
      <th>25</th>
      <td>M3A</td>
      <td>43.753259</td>
      <td>-79.329656</td>
    </tr>
    <tr>
      <th>26</th>
      <td>M3B</td>
      <td>43.745906</td>
      <td>-79.352188</td>
    </tr>
    <tr>
      <th>27</th>
      <td>M3C</td>
      <td>43.725900</td>
      <td>-79.340923</td>
    </tr>
    <tr>
      <th>28</th>
      <td>M3H</td>
      <td>43.754328</td>
      <td>-79.442259</td>
    </tr>
    <tr>
      <th>29</th>
      <td>M3J</td>
      <td>43.767980</td>
      <td>-79.487262</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>73</th>
      <td>M6C</td>
      <td>43.693781</td>
      <td>-79.428191</td>
    </tr>
    <tr>
      <th>74</th>
      <td>M6E</td>
      <td>43.689026</td>
      <td>-79.453512</td>
    </tr>
    <tr>
      <th>75</th>
      <td>M6G</td>
      <td>43.669542</td>
      <td>-79.422564</td>
    </tr>
    <tr>
      <th>76</th>
      <td>M6H</td>
      <td>43.669005</td>
      <td>-79.442259</td>
    </tr>
    <tr>
      <th>77</th>
      <td>M6J</td>
      <td>43.647927</td>
      <td>-79.419750</td>
    </tr>
    <tr>
      <th>78</th>
      <td>M6K</td>
      <td>43.636847</td>
      <td>-79.428191</td>
    </tr>
    <tr>
      <th>79</th>
      <td>M6L</td>
      <td>43.713756</td>
      <td>-79.490074</td>
    </tr>
    <tr>
      <th>80</th>
      <td>M6M</td>
      <td>43.691116</td>
      <td>-79.476013</td>
    </tr>
    <tr>
      <th>81</th>
      <td>M6N</td>
      <td>43.673185</td>
      <td>-79.487262</td>
    </tr>
    <tr>
      <th>82</th>
      <td>M6P</td>
      <td>43.661608</td>
      <td>-79.464763</td>
    </tr>
    <tr>
      <th>83</th>
      <td>M6R</td>
      <td>43.648960</td>
      <td>-79.456325</td>
    </tr>
    <tr>
      <th>84</th>
      <td>M6S</td>
      <td>43.651571</td>
      <td>-79.484450</td>
    </tr>
    <tr>
      <th>85</th>
      <td>M7A</td>
      <td>43.662301</td>
      <td>-79.389494</td>
    </tr>
    <tr>
      <th>86</th>
      <td>M7R</td>
      <td>43.636966</td>
      <td>-79.615819</td>
    </tr>
    <tr>
      <th>87</th>
      <td>M7Y</td>
      <td>43.662744</td>
      <td>-79.321558</td>
    </tr>
    <tr>
      <th>88</th>
      <td>M8V</td>
      <td>43.605647</td>
      <td>-79.501321</td>
    </tr>
    <tr>
      <th>89</th>
      <td>M8W</td>
      <td>43.602414</td>
      <td>-79.543484</td>
    </tr>
    <tr>
      <th>90</th>
      <td>M8X</td>
      <td>43.653654</td>
      <td>-79.506944</td>
    </tr>
    <tr>
      <th>91</th>
      <td>M8Y</td>
      <td>43.636258</td>
      <td>-79.498509</td>
    </tr>
    <tr>
      <th>92</th>
      <td>M8Z</td>
      <td>43.628841</td>
      <td>-79.520999</td>
    </tr>
    <tr>
      <th>93</th>
      <td>M9A</td>
      <td>43.667856</td>
      <td>-79.532242</td>
    </tr>
    <tr>
      <th>94</th>
      <td>M9B</td>
      <td>43.650943</td>
      <td>-79.554724</td>
    </tr>
    <tr>
      <th>95</th>
      <td>M9C</td>
      <td>43.643515</td>
      <td>-79.577201</td>
    </tr>
    <tr>
      <th>96</th>
      <td>M9L</td>
      <td>43.756303</td>
      <td>-79.565963</td>
    </tr>
    <tr>
      <th>97</th>
      <td>M9M</td>
      <td>43.724766</td>
      <td>-79.532242</td>
    </tr>
    <tr>
      <th>98</th>
      <td>M9N</td>
      <td>43.706876</td>
      <td>-79.518188</td>
    </tr>
    <tr>
      <th>99</th>
      <td>M9P</td>
      <td>43.696319</td>
      <td>-79.532242</td>
    </tr>
    <tr>
      <th>100</th>
      <td>M9R</td>
      <td>43.688905</td>
      <td>-79.554724</td>
    </tr>
    <tr>
      <th>101</th>
      <td>M9V</td>
      <td>43.739416</td>
      <td>-79.588437</td>
    </tr>
    <tr>
      <th>102</th>
      <td>M9W</td>
      <td>43.706748</td>
      <td>-79.594054</td>
    </tr>
  </tbody>
</table>
<p>103 rows × 3 columns</p>
</div>




```python
df_final=pd.merge(df_cd,df2,on='PostalCode')
df_final=df_final[['PostalCode','Borough','Neighborhood','Latitude','Longitude']]
df_final
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>PostalCode</th>
      <th>Borough</th>
      <th>Neighborhood</th>
      <th>Latitude</th>
      <th>Longitude</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>M1B</td>
      <td>Scarborough</td>
      <td>Rouge,Malvern</td>
      <td>43.806686</td>
      <td>-79.194353</td>
    </tr>
    <tr>
      <th>1</th>
      <td>M1C</td>
      <td>Scarborough</td>
      <td>Highland Creek,Rouge Hill,Port Union</td>
      <td>43.784535</td>
      <td>-79.160497</td>
    </tr>
    <tr>
      <th>2</th>
      <td>M1E</td>
      <td>Scarborough</td>
      <td>Guildwood,Morningside,West Hill</td>
      <td>43.763573</td>
      <td>-79.188711</td>
    </tr>
    <tr>
      <th>3</th>
      <td>M1G</td>
      <td>Scarborough</td>
      <td>Woburn</td>
      <td>43.770992</td>
      <td>-79.216917</td>
    </tr>
    <tr>
      <th>4</th>
      <td>M1H</td>
      <td>Scarborough</td>
      <td>Cedarbrae</td>
      <td>43.773136</td>
      <td>-79.239476</td>
    </tr>
    <tr>
      <th>5</th>
      <td>M1J</td>
      <td>Scarborough</td>
      <td>Scarborough Village</td>
      <td>43.744734</td>
      <td>-79.239476</td>
    </tr>
    <tr>
      <th>6</th>
      <td>M1K</td>
      <td>Scarborough</td>
      <td>East Birchmount Park,Ionview,Kennedy Park</td>
      <td>43.727929</td>
      <td>-79.262029</td>
    </tr>
    <tr>
      <th>7</th>
      <td>M1L</td>
      <td>Scarborough</td>
      <td>Clairlea,Golden Mile,Oakridge</td>
      <td>43.711112</td>
      <td>-79.284577</td>
    </tr>
    <tr>
      <th>8</th>
      <td>M1M</td>
      <td>Scarborough</td>
      <td>Cliffcrest,Cliffside,Scarborough Village West</td>
      <td>43.716316</td>
      <td>-79.239476</td>
    </tr>
    <tr>
      <th>9</th>
      <td>M1N</td>
      <td>Scarborough</td>
      <td>Birch Cliff,Cliffside West</td>
      <td>43.692657</td>
      <td>-79.264848</td>
    </tr>
    <tr>
      <th>10</th>
      <td>M1P</td>
      <td>Scarborough</td>
      <td>Dorset Park,Scarborough Town Centre,Wexford He...</td>
      <td>43.757410</td>
      <td>-79.273304</td>
    </tr>
    <tr>
      <th>11</th>
      <td>M1R</td>
      <td>Scarborough</td>
      <td>Maryvale,Wexford</td>
      <td>43.750072</td>
      <td>-79.295849</td>
    </tr>
    <tr>
      <th>12</th>
      <td>M1S</td>
      <td>Scarborough</td>
      <td>Agincourt</td>
      <td>43.794200</td>
      <td>-79.262029</td>
    </tr>
    <tr>
      <th>13</th>
      <td>M1T</td>
      <td>Scarborough</td>
      <td>Clarks Corners,Sullivan,Tam O'Shanter</td>
      <td>43.781638</td>
      <td>-79.304302</td>
    </tr>
    <tr>
      <th>14</th>
      <td>M1V</td>
      <td>Scarborough</td>
      <td>Agincourt North,L'Amoreaux East,Milliken,Steel...</td>
      <td>43.815252</td>
      <td>-79.284577</td>
    </tr>
    <tr>
      <th>15</th>
      <td>M1W</td>
      <td>Scarborough</td>
      <td>L'Amoreaux West</td>
      <td>43.799525</td>
      <td>-79.318389</td>
    </tr>
    <tr>
      <th>16</th>
      <td>M1X</td>
      <td>Scarborough</td>
      <td>Upper Rouge</td>
      <td>43.836125</td>
      <td>-79.205636</td>
    </tr>
    <tr>
      <th>17</th>
      <td>M2H</td>
      <td>North York</td>
      <td>Hillcrest Village</td>
      <td>43.803762</td>
      <td>-79.363452</td>
    </tr>
    <tr>
      <th>18</th>
      <td>M2J</td>
      <td>North York</td>
      <td>Fairview,Henry Farm,Oriole</td>
      <td>43.778517</td>
      <td>-79.346556</td>
    </tr>
    <tr>
      <th>19</th>
      <td>M2K</td>
      <td>North York</td>
      <td>Bayview Village</td>
      <td>43.786947</td>
      <td>-79.385975</td>
    </tr>
    <tr>
      <th>20</th>
      <td>M2L</td>
      <td>North York</td>
      <td>Silver Hills,York Mills</td>
      <td>43.757490</td>
      <td>-79.374714</td>
    </tr>
    <tr>
      <th>21</th>
      <td>M2M</td>
      <td>North York</td>
      <td>Newtonbrook,Willowdale</td>
      <td>43.789053</td>
      <td>-79.408493</td>
    </tr>
    <tr>
      <th>22</th>
      <td>M2N</td>
      <td>North York</td>
      <td>Willowdale South</td>
      <td>43.770120</td>
      <td>-79.408493</td>
    </tr>
    <tr>
      <th>23</th>
      <td>M2P</td>
      <td>North York</td>
      <td>York Mills West</td>
      <td>43.752758</td>
      <td>-79.400049</td>
    </tr>
    <tr>
      <th>24</th>
      <td>M2R</td>
      <td>North York</td>
      <td>Willowdale West</td>
      <td>43.782736</td>
      <td>-79.442259</td>
    </tr>
    <tr>
      <th>25</th>
      <td>M3A</td>
      <td>North York</td>
      <td>Parkwoods</td>
      <td>43.753259</td>
      <td>-79.329656</td>
    </tr>
    <tr>
      <th>26</th>
      <td>M3B</td>
      <td>North York</td>
      <td>Don Mills North</td>
      <td>43.745906</td>
      <td>-79.352188</td>
    </tr>
    <tr>
      <th>27</th>
      <td>M3C</td>
      <td>North York</td>
      <td>Flemingdon Park,Don Mills South</td>
      <td>43.725900</td>
      <td>-79.340923</td>
    </tr>
    <tr>
      <th>28</th>
      <td>M3H</td>
      <td>North York</td>
      <td>Bathurst Manor,Downsview North,Wilson Heights</td>
      <td>43.754328</td>
      <td>-79.442259</td>
    </tr>
    <tr>
      <th>29</th>
      <td>M3J</td>
      <td>North York</td>
      <td>Northwood Park,York University</td>
      <td>43.767980</td>
      <td>-79.487262</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>73</th>
      <td>M6C</td>
      <td>York</td>
      <td>Humewood-Cedarvale</td>
      <td>43.693781</td>
      <td>-79.428191</td>
    </tr>
    <tr>
      <th>74</th>
      <td>M6E</td>
      <td>York</td>
      <td>Caledonia-Fairbanks</td>
      <td>43.689026</td>
      <td>-79.453512</td>
    </tr>
    <tr>
      <th>75</th>
      <td>M6G</td>
      <td>Downtown Toronto</td>
      <td>Christie</td>
      <td>43.669542</td>
      <td>-79.422564</td>
    </tr>
    <tr>
      <th>76</th>
      <td>M6H</td>
      <td>West Toronto</td>
      <td>Dovercourt Village,Dufferin</td>
      <td>43.669005</td>
      <td>-79.442259</td>
    </tr>
    <tr>
      <th>77</th>
      <td>M6J</td>
      <td>West Toronto</td>
      <td>Little Portugal,Trinity</td>
      <td>43.647927</td>
      <td>-79.419750</td>
    </tr>
    <tr>
      <th>78</th>
      <td>M6K</td>
      <td>West Toronto</td>
      <td>Brockton,Exhibition Place,Parkdale Village</td>
      <td>43.636847</td>
      <td>-79.428191</td>
    </tr>
    <tr>
      <th>79</th>
      <td>M6L</td>
      <td>North York</td>
      <td>Downsview,North Park,Upwood Park</td>
      <td>43.713756</td>
      <td>-79.490074</td>
    </tr>
    <tr>
      <th>80</th>
      <td>M6M</td>
      <td>York</td>
      <td>Del Ray,Keelesdale,Mount Dennis,Silverthorn</td>
      <td>43.691116</td>
      <td>-79.476013</td>
    </tr>
    <tr>
      <th>81</th>
      <td>M6N</td>
      <td>York</td>
      <td>The Junction North,Runnymede</td>
      <td>43.673185</td>
      <td>-79.487262</td>
    </tr>
    <tr>
      <th>82</th>
      <td>M6P</td>
      <td>West Toronto</td>
      <td>High Park,The Junction South</td>
      <td>43.661608</td>
      <td>-79.464763</td>
    </tr>
    <tr>
      <th>83</th>
      <td>M6R</td>
      <td>West Toronto</td>
      <td>Parkdale,Roncesvalles</td>
      <td>43.648960</td>
      <td>-79.456325</td>
    </tr>
    <tr>
      <th>84</th>
      <td>M6S</td>
      <td>West Toronto</td>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
    </tr>
    <tr>
      <th>85</th>
      <td>M7A</td>
      <td>Queen's Park</td>
      <td>Queen's Park</td>
      <td>43.662301</td>
      <td>-79.389494</td>
    </tr>
    <tr>
      <th>86</th>
      <td>M7R</td>
      <td>Mississauga</td>
      <td>Canada Post Gateway Processing Centre</td>
      <td>43.636966</td>
      <td>-79.615819</td>
    </tr>
    <tr>
      <th>87</th>
      <td>M7Y</td>
      <td>East Toronto</td>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
    </tr>
    <tr>
      <th>88</th>
      <td>M8V</td>
      <td>Etobicoke</td>
      <td>Humber Bay Shores,Mimico South,New Toronto</td>
      <td>43.605647</td>
      <td>-79.501321</td>
    </tr>
    <tr>
      <th>89</th>
      <td>M8W</td>
      <td>Etobicoke</td>
      <td>Alderwood,Long Branch</td>
      <td>43.602414</td>
      <td>-79.543484</td>
    </tr>
    <tr>
      <th>90</th>
      <td>M8X</td>
      <td>Etobicoke</td>
      <td>The Kingsway,Montgomery Road,Old Mill North</td>
      <td>43.653654</td>
      <td>-79.506944</td>
    </tr>
    <tr>
      <th>91</th>
      <td>M8Y</td>
      <td>Etobicoke</td>
      <td>Humber Bay,King's Mill Park,Kingsway Park Sout...</td>
      <td>43.636258</td>
      <td>-79.498509</td>
    </tr>
    <tr>
      <th>92</th>
      <td>M8Z</td>
      <td>Etobicoke</td>
      <td>Kingsway Park South West,Mimico NW,The Queensw...</td>
      <td>43.628841</td>
      <td>-79.520999</td>
    </tr>
    <tr>
      <th>93</th>
      <td>M9A</td>
      <td>Etobicoke</td>
      <td>Islington Avenue</td>
      <td>43.667856</td>
      <td>-79.532242</td>
    </tr>
    <tr>
      <th>94</th>
      <td>M9B</td>
      <td>Etobicoke</td>
      <td>Cloverdale,Islington,Martin Grove,Princess Gar...</td>
      <td>43.650943</td>
      <td>-79.554724</td>
    </tr>
    <tr>
      <th>95</th>
      <td>M9C</td>
      <td>Etobicoke</td>
      <td>Bloordale Gardens,Eringate,Markland Wood,Old B...</td>
      <td>43.643515</td>
      <td>-79.577201</td>
    </tr>
    <tr>
      <th>96</th>
      <td>M9L</td>
      <td>North York</td>
      <td>Humber Summit</td>
      <td>43.756303</td>
      <td>-79.565963</td>
    </tr>
    <tr>
      <th>97</th>
      <td>M9M</td>
      <td>North York</td>
      <td>Emery,Humberlea</td>
      <td>43.724766</td>
      <td>-79.532242</td>
    </tr>
    <tr>
      <th>98</th>
      <td>M9N</td>
      <td>York</td>
      <td>Weston</td>
      <td>43.706876</td>
      <td>-79.518188</td>
    </tr>
    <tr>
      <th>99</th>
      <td>M9P</td>
      <td>Etobicoke</td>
      <td>Westmount</td>
      <td>43.696319</td>
      <td>-79.532242</td>
    </tr>
    <tr>
      <th>100</th>
      <td>M9R</td>
      <td>Etobicoke</td>
      <td>Kingsview Village,Martin Grove Gardens,Richvie...</td>
      <td>43.688905</td>
      <td>-79.554724</td>
    </tr>
    <tr>
      <th>101</th>
      <td>M9V</td>
      <td>Etobicoke</td>
      <td>Albion Gardens,Beaumond Heights,Humbergate,Jam...</td>
      <td>43.739416</td>
      <td>-79.588437</td>
    </tr>
    <tr>
      <th>102</th>
      <td>M9W</td>
      <td>Etobicoke</td>
      <td>Northwest</td>
      <td>43.706748</td>
      <td>-79.594054</td>
    </tr>
  </tbody>
</table>
<p>103 rows × 5 columns</p>
</div>




```python
df_final.shape
```




    (103, 5)




```python
df_map=df_final[df_final['Borough'].str.contains('Toronto')]
df_map
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>PostalCode</th>
      <th>Borough</th>
      <th>Neighborhood</th>
      <th>Latitude</th>
      <th>Longitude</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>37</th>
      <td>M4E</td>
      <td>East Toronto</td>
      <td>The Beaches</td>
      <td>43.676357</td>
      <td>-79.293031</td>
    </tr>
    <tr>
      <th>41</th>
      <td>M4K</td>
      <td>East Toronto</td>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
    </tr>
    <tr>
      <th>42</th>
      <td>M4L</td>
      <td>East Toronto</td>
      <td>The Beaches West,India Bazaar</td>
      <td>43.668999</td>
      <td>-79.315572</td>
    </tr>
    <tr>
      <th>43</th>
      <td>M4M</td>
      <td>East Toronto</td>
      <td>Studio District</td>
      <td>43.659526</td>
      <td>-79.340923</td>
    </tr>
    <tr>
      <th>44</th>
      <td>M4N</td>
      <td>Central Toronto</td>
      <td>Lawrence Park</td>
      <td>43.728020</td>
      <td>-79.388790</td>
    </tr>
    <tr>
      <th>45</th>
      <td>M4P</td>
      <td>Central Toronto</td>
      <td>Davisville North</td>
      <td>43.712751</td>
      <td>-79.390197</td>
    </tr>
    <tr>
      <th>46</th>
      <td>M4R</td>
      <td>Central Toronto</td>
      <td>North Toronto West</td>
      <td>43.715383</td>
      <td>-79.405678</td>
    </tr>
    <tr>
      <th>47</th>
      <td>M4S</td>
      <td>Central Toronto</td>
      <td>Davisville</td>
      <td>43.704324</td>
      <td>-79.388790</td>
    </tr>
    <tr>
      <th>48</th>
      <td>M4T</td>
      <td>Central Toronto</td>
      <td>Moore Park,Summerhill East</td>
      <td>43.689574</td>
      <td>-79.383160</td>
    </tr>
    <tr>
      <th>49</th>
      <td>M4V</td>
      <td>Central Toronto</td>
      <td>Deer Park,Forest Hill SE,Rathnelly,South Hill,...</td>
      <td>43.686412</td>
      <td>-79.400049</td>
    </tr>
    <tr>
      <th>50</th>
      <td>M4W</td>
      <td>Downtown Toronto</td>
      <td>Rosedale</td>
      <td>43.679563</td>
      <td>-79.377529</td>
    </tr>
    <tr>
      <th>51</th>
      <td>M4X</td>
      <td>Downtown Toronto</td>
      <td>Cabbagetown,St. James Town</td>
      <td>43.667967</td>
      <td>-79.367675</td>
    </tr>
    <tr>
      <th>52</th>
      <td>M4Y</td>
      <td>Downtown Toronto</td>
      <td>Church and Wellesley</td>
      <td>43.665860</td>
      <td>-79.383160</td>
    </tr>
    <tr>
      <th>53</th>
      <td>M5A</td>
      <td>Downtown Toronto</td>
      <td>Harbourfront,Regent Park</td>
      <td>43.654260</td>
      <td>-79.360636</td>
    </tr>
    <tr>
      <th>54</th>
      <td>M5B</td>
      <td>Downtown Toronto</td>
      <td>Ryerson,Garden District</td>
      <td>43.657162</td>
      <td>-79.378937</td>
    </tr>
    <tr>
      <th>55</th>
      <td>M5C</td>
      <td>Downtown Toronto</td>
      <td>St. James Town</td>
      <td>43.651494</td>
      <td>-79.375418</td>
    </tr>
    <tr>
      <th>56</th>
      <td>M5E</td>
      <td>Downtown Toronto</td>
      <td>Berczy Park</td>
      <td>43.644771</td>
      <td>-79.373306</td>
    </tr>
    <tr>
      <th>57</th>
      <td>M5G</td>
      <td>Downtown Toronto</td>
      <td>Central Bay Street</td>
      <td>43.657952</td>
      <td>-79.387383</td>
    </tr>
    <tr>
      <th>58</th>
      <td>M5H</td>
      <td>Downtown Toronto</td>
      <td>Adelaide,King,Richmond</td>
      <td>43.650571</td>
      <td>-79.384568</td>
    </tr>
    <tr>
      <th>59</th>
      <td>M5J</td>
      <td>Downtown Toronto</td>
      <td>Harbourfront East,Toronto Islands,Union Station</td>
      <td>43.640816</td>
      <td>-79.381752</td>
    </tr>
    <tr>
      <th>60</th>
      <td>M5K</td>
      <td>Downtown Toronto</td>
      <td>Design Exchange,Toronto Dominion Centre</td>
      <td>43.647177</td>
      <td>-79.381576</td>
    </tr>
    <tr>
      <th>61</th>
      <td>M5L</td>
      <td>Downtown Toronto</td>
      <td>Commerce Court,Victoria Hotel</td>
      <td>43.648198</td>
      <td>-79.379817</td>
    </tr>
    <tr>
      <th>63</th>
      <td>M5N</td>
      <td>Central Toronto</td>
      <td>Roselawn</td>
      <td>43.711695</td>
      <td>-79.416936</td>
    </tr>
    <tr>
      <th>64</th>
      <td>M5P</td>
      <td>Central Toronto</td>
      <td>Forest Hill North,Forest Hill West</td>
      <td>43.696948</td>
      <td>-79.411307</td>
    </tr>
    <tr>
      <th>65</th>
      <td>M5R</td>
      <td>Central Toronto</td>
      <td>The Annex,North Midtown,Yorkville</td>
      <td>43.672710</td>
      <td>-79.405678</td>
    </tr>
    <tr>
      <th>66</th>
      <td>M5S</td>
      <td>Downtown Toronto</td>
      <td>Harbord,University of Toronto</td>
      <td>43.662696</td>
      <td>-79.400049</td>
    </tr>
    <tr>
      <th>67</th>
      <td>M5T</td>
      <td>Downtown Toronto</td>
      <td>Chinatown,Grange Park,Kensington Market</td>
      <td>43.653206</td>
      <td>-79.400049</td>
    </tr>
    <tr>
      <th>68</th>
      <td>M5V</td>
      <td>Downtown Toronto</td>
      <td>CN Tower,Bathurst Quay,Island airport,Harbourf...</td>
      <td>43.628947</td>
      <td>-79.394420</td>
    </tr>
    <tr>
      <th>69</th>
      <td>M5W</td>
      <td>Downtown Toronto</td>
      <td>Stn A PO Boxes 25 The Esplanade</td>
      <td>43.646435</td>
      <td>-79.374846</td>
    </tr>
    <tr>
      <th>70</th>
      <td>M5X</td>
      <td>Downtown Toronto</td>
      <td>First Canadian Place,Underground city</td>
      <td>43.648429</td>
      <td>-79.382280</td>
    </tr>
    <tr>
      <th>75</th>
      <td>M6G</td>
      <td>Downtown Toronto</td>
      <td>Christie</td>
      <td>43.669542</td>
      <td>-79.422564</td>
    </tr>
    <tr>
      <th>76</th>
      <td>M6H</td>
      <td>West Toronto</td>
      <td>Dovercourt Village,Dufferin</td>
      <td>43.669005</td>
      <td>-79.442259</td>
    </tr>
    <tr>
      <th>77</th>
      <td>M6J</td>
      <td>West Toronto</td>
      <td>Little Portugal,Trinity</td>
      <td>43.647927</td>
      <td>-79.419750</td>
    </tr>
    <tr>
      <th>78</th>
      <td>M6K</td>
      <td>West Toronto</td>
      <td>Brockton,Exhibition Place,Parkdale Village</td>
      <td>43.636847</td>
      <td>-79.428191</td>
    </tr>
    <tr>
      <th>82</th>
      <td>M6P</td>
      <td>West Toronto</td>
      <td>High Park,The Junction South</td>
      <td>43.661608</td>
      <td>-79.464763</td>
    </tr>
    <tr>
      <th>83</th>
      <td>M6R</td>
      <td>West Toronto</td>
      <td>Parkdale,Roncesvalles</td>
      <td>43.648960</td>
      <td>-79.456325</td>
    </tr>
    <tr>
      <th>84</th>
      <td>M6S</td>
      <td>West Toronto</td>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
    </tr>
    <tr>
      <th>87</th>
      <td>M7Y</td>
      <td>East Toronto</td>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
    </tr>
  </tbody>
</table>
</div>




```python
for lat, lng, borough, neighborhood in zip(df_map['Latitude'], df_map['Longitude'], df_map['Borough'], df_map['Neighborhood']):
    label = '{}--{}'.format(neighborhood, borough)
    label = folium.Popup(label, parse_html=True)
    folium.CircleMarker(
        [lat, lng],
        radius=5,
        popup=label,
        color='blue',
        fill=True,
        fill_color='#3186cc',
        fill_opacity=0.7,
        parse_html=False).add_to(map_toronto)  
    
map_toronto
```




<div style="width:100%;"><div style="position:relative;width:100%;height:0;padding-bottom:60%;"><iframe src="data:text/html;charset=utf-8;base64,PCFET0NUWVBFIGh0bWw+CjxoZWFkPiAgICAKICAgIDxtZXRhIGh0dHAtZXF1aXY9ImNvbnRlbnQtdHlwZSIgY29udGVudD0idGV4dC9odG1sOyBjaGFyc2V0PVVURi04IiAvPgogICAgPHNjcmlwdD5MX1BSRUZFUl9DQU5WQVMgPSBmYWxzZTsgTF9OT19UT1VDSCA9IGZhbHNlOyBMX0RJU0FCTEVfM0QgPSBmYWxzZTs8L3NjcmlwdD4KICAgIDxzY3JpcHQgc3JjPSJodHRwczovL2Nkbi5qc2RlbGl2ci5uZXQvbnBtL2xlYWZsZXRAMS4yLjAvZGlzdC9sZWFmbGV0LmpzIj48L3NjcmlwdD4KICAgIDxzY3JpcHQgc3JjPSJodHRwczovL2FqYXguZ29vZ2xlYXBpcy5jb20vYWpheC9saWJzL2pxdWVyeS8xLjExLjEvanF1ZXJ5Lm1pbi5qcyI+PC9zY3JpcHQ+CiAgICA8c2NyaXB0IHNyYz0iaHR0cHM6Ly9tYXhjZG4uYm9vdHN0cmFwY2RuLmNvbS9ib290c3RyYXAvMy4yLjAvanMvYm9vdHN0cmFwLm1pbi5qcyI+PC9zY3JpcHQ+CiAgICA8c2NyaXB0IHNyYz0iaHR0cHM6Ly9jZG5qcy5jbG91ZGZsYXJlLmNvbS9hamF4L2xpYnMvTGVhZmxldC5hd2Vzb21lLW1hcmtlcnMvMi4wLjIvbGVhZmxldC5hd2Vzb21lLW1hcmtlcnMuanMiPjwvc2NyaXB0PgogICAgPGxpbmsgcmVsPSJzdHlsZXNoZWV0IiBocmVmPSJodHRwczovL2Nkbi5qc2RlbGl2ci5uZXQvbnBtL2xlYWZsZXRAMS4yLjAvZGlzdC9sZWFmbGV0LmNzcyIvPgogICAgPGxpbmsgcmVsPSJzdHlsZXNoZWV0IiBocmVmPSJodHRwczovL21heGNkbi5ib290c3RyYXBjZG4uY29tL2Jvb3RzdHJhcC8zLjIuMC9jc3MvYm9vdHN0cmFwLm1pbi5jc3MiLz4KICAgIDxsaW5rIHJlbD0ic3R5bGVzaGVldCIgaHJlZj0iaHR0cHM6Ly9tYXhjZG4uYm9vdHN0cmFwY2RuLmNvbS9ib290c3RyYXAvMy4yLjAvY3NzL2Jvb3RzdHJhcC10aGVtZS5taW4uY3NzIi8+CiAgICA8bGluayByZWw9InN0eWxlc2hlZXQiIGhyZWY9Imh0dHBzOi8vbWF4Y2RuLmJvb3RzdHJhcGNkbi5jb20vZm9udC1hd2Vzb21lLzQuNi4zL2Nzcy9mb250LWF3ZXNvbWUubWluLmNzcyIvPgogICAgPGxpbmsgcmVsPSJzdHlsZXNoZWV0IiBocmVmPSJodHRwczovL2NkbmpzLmNsb3VkZmxhcmUuY29tL2FqYXgvbGlicy9MZWFmbGV0LmF3ZXNvbWUtbWFya2Vycy8yLjAuMi9sZWFmbGV0LmF3ZXNvbWUtbWFya2Vycy5jc3MiLz4KICAgIDxsaW5rIHJlbD0ic3R5bGVzaGVldCIgaHJlZj0iaHR0cHM6Ly9yYXdnaXQuY29tL3B5dGhvbi12aXN1YWxpemF0aW9uL2ZvbGl1bS9tYXN0ZXIvZm9saXVtL3RlbXBsYXRlcy9sZWFmbGV0LmF3ZXNvbWUucm90YXRlLmNzcyIvPgogICAgPHN0eWxlPmh0bWwsIGJvZHkge3dpZHRoOiAxMDAlO2hlaWdodDogMTAwJTttYXJnaW46IDA7cGFkZGluZzogMDt9PC9zdHlsZT4KICAgIDxzdHlsZT4jbWFwIHtwb3NpdGlvbjphYnNvbHV0ZTt0b3A6MDtib3R0b206MDtyaWdodDowO2xlZnQ6MDt9PC9zdHlsZT4KICAgIAogICAgICAgICAgICA8c3R5bGU+ICNtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUgewogICAgICAgICAgICAgICAgcG9zaXRpb24gOiByZWxhdGl2ZTsKICAgICAgICAgICAgICAgIHdpZHRoIDogMTAwLjAlOwogICAgICAgICAgICAgICAgaGVpZ2h0OiAxMDAuMCU7CiAgICAgICAgICAgICAgICBsZWZ0OiAwLjAlOwogICAgICAgICAgICAgICAgdG9wOiAwLjAlOwogICAgICAgICAgICAgICAgfQogICAgICAgICAgICA8L3N0eWxlPgogICAgICAgIAo8L2hlYWQ+Cjxib2R5PiAgICAKICAgIAogICAgICAgICAgICA8ZGl2IGNsYXNzPSJmb2xpdW0tbWFwIiBpZD0ibWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlIiA+PC9kaXY+CiAgICAgICAgCjwvYm9keT4KPHNjcmlwdD4gICAgCiAgICAKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGJvdW5kcyA9IG51bGw7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgdmFyIG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSA9IEwubWFwKAogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgJ21hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZScsCiAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICB7Y2VudGVyOiBbNDMuNjUzMiwtNzkuMzgzMl0sCiAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICB6b29tOiAxMCwKICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIG1heEJvdW5kczogYm91bmRzLAogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgbGF5ZXJzOiBbXSwKICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIHdvcmxkQ29weUp1bXA6IGZhbHNlLAogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgY3JzOiBMLkNSUy5FUFNHMzg1NwogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICB9KTsKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHRpbGVfbGF5ZXJfYTYzMzdmYWM3ODdkNDZmNmFmNWRlNTA1MWRkNjEzZjUgPSBMLnRpbGVMYXllcigKICAgICAgICAgICAgICAgICdodHRwczovL3tzfS50aWxlLm9wZW5zdHJlZXRtYXAub3JnL3t6fS97eH0ve3l9LnBuZycsCiAgICAgICAgICAgICAgICB7CiAgImF0dHJpYnV0aW9uIjogbnVsbCwKICAiZGV0ZWN0UmV0aW5hIjogZmFsc2UsCiAgIm1heFpvb20iOiAxOCwKICAibWluWm9vbSI6IDEsCiAgIm5vV3JhcCI6IGZhbHNlLAogICJzdWJkb21haW5zIjogImFiYyIKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzkzYTQzOTUzNWU3NTRjOTM4Y2E1NTE4OGNkYzg1YWNiID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjc2MzU3Mzk5OTk5OTksLTc5LjI5MzAzMTJdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfZDNjNWViMzU5OWM3NDA4YTk3NGJhMmYxNmY2ODZlNjYgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfYjJiNzMwNDY0MDE5NGFiZDhkZjFiZTE2MGU3Y2NkYzUgPSAkKCc8ZGl2IGlkPSJodG1sX2IyYjczMDQ2NDAxOTRhYmQ4ZGYxYmUxNjBlN2NjZGM1IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5UaGUgQmVhY2hlcywgRWFzdCBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF9kM2M1ZWIzNTk5Yzc0MDhhOTc0YmEyZjE2ZjY4NmU2Ni5zZXRDb250ZW50KGh0bWxfYjJiNzMwNDY0MDE5NGFiZDhkZjFiZTE2MGU3Y2NkYzUpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfOTNhNDM5NTM1ZTc1NGM5MzhjYTU1MTg4Y2RjODVhY2IuYmluZFBvcHVwKHBvcHVwX2QzYzVlYjM1OTljNzQwOGE5NzRiYTJmMTZmNjg2ZTY2KTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2ZmOWJjOGM1MzdlZjRkOTdhZDk5ZTUyYzI3Zjg2MzkxID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjc5NTU3MSwtNzkuMzUyMTg4XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzQ3MTk3NGUzNmVmZjQ1OGQ5ZDUyYjI4ZGI1YzQyYmMxID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzAyYmE2NWMwM2Q3ZTQxYTRhZGZiYzc3ZGY0NWRhOGI3ID0gJCgnPGRpdiBpZD0iaHRtbF8wMmJhNjVjMDNkN2U0MWE0YWRmYmM3N2RmNDVkYThiNyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+VGhlIERhbmZvcnRoIFdlc3QsUml2ZXJkYWxlLCBFYXN0IFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzQ3MTk3NGUzNmVmZjQ1OGQ5ZDUyYjI4ZGI1YzQyYmMxLnNldENvbnRlbnQoaHRtbF8wMmJhNjVjMDNkN2U0MWE0YWRmYmM3N2RmNDVkYThiNyk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9mZjliYzhjNTM3ZWY0ZDk3YWQ5OWU1MmMyN2Y4NjM5MS5iaW5kUG9wdXAocG9wdXBfNDcxOTc0ZTM2ZWZmNDU4ZDlkNTJiMjhkYjVjNDJiYzEpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfODIwNjUxYTdhYmZiNDM5ZGFlYWVhNzFkODA1N2Y2ZDYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42Njg5OTg1LC03OS4zMTU1NzE1OTk5OTk5OF0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF82ZGFmZTkwMWI5Yzg0MmJjYmE1NWEwMTgzZTY3NTVmOCA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF85NjZmZjJlMDhmODk0MDg1OGQwY2MwYzBiNTJjMDg5ZSA9ICQoJzxkaXYgaWQ9Imh0bWxfOTY2ZmYyZTA4Zjg5NDA4NThkMGNjMGMwYjUyYzA4OWUiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlRoZSBCZWFjaGVzIFdlc3QsSW5kaWEgQmF6YWFyLCBFYXN0IFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzZkYWZlOTAxYjljODQyYmNiYTU1YTAxODNlNjc1NWY4LnNldENvbnRlbnQoaHRtbF85NjZmZjJlMDhmODk0MDg1OGQwY2MwYzBiNTJjMDg5ZSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl84MjA2NTFhN2FiZmI0MzlkYWVhZWE3MWQ4MDU3ZjZkNi5iaW5kUG9wdXAocG9wdXBfNmRhZmU5MDFiOWM4NDJiY2JhNTVhMDE4M2U2NzU1ZjgpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNDNiNjZjNjZiODQ3NDFmZjg3YTkxYmE5ZWQwZTNmZDAgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NTk1MjU1LC03OS4zNDA5MjNdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfNzE1OTFiNDhjMjAwNGRjNmEzYWRkNjBlZDM5OTBjZDEgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfYjg2NjMzZjNmZjdjNGVjZjg5NjM0ZjkxZWMyMmQ2MzQgPSAkKCc8ZGl2IGlkPSJodG1sX2I4NjYzM2YzZmY3YzRlY2Y4OTYzNGY5MWVjMjJkNjM0IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5TdHVkaW8gRGlzdHJpY3QsIEVhc3QgVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfNzE1OTFiNDhjMjAwNGRjNmEzYWRkNjBlZDM5OTBjZDEuc2V0Q29udGVudChodG1sX2I4NjYzM2YzZmY3YzRlY2Y4OTYzNGY5MWVjMjJkNjM0KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzQzYjY2YzY2Yjg0NzQxZmY4N2E5MWJhOWVkMGUzZmQwLmJpbmRQb3B1cChwb3B1cF83MTU5MWI0OGMyMDA0ZGM2YTNhZGQ2MGVkMzk5MGNkMSk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9mMzk0MTNhYjY1MjA0ZWU3ODYyODMxOTgyMDA0NTZiMSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjcyODAyMDUsLTc5LjM4ODc5MDFdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfMWVlZWNkMTkzZmUwNGJjNzg3OGFkMTNhZDZlMGY2N2EgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfYjQyZmFmYzQwY2IyNDFjM2FmMTcyZjU5ZmNjODQwMDcgPSAkKCc8ZGl2IGlkPSJodG1sX2I0MmZhZmM0MGNiMjQxYzNhZjE3MmY1OWZjYzg0MDA3IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5MYXdyZW5jZSBQYXJrLCBDZW50cmFsIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzFlZWVjZDE5M2ZlMDRiYzc4NzhhZDEzYWQ2ZTBmNjdhLnNldENvbnRlbnQoaHRtbF9iNDJmYWZjNDBjYjI0MWMzYWYxNzJmNTlmY2M4NDAwNyk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9mMzk0MTNhYjY1MjA0ZWU3ODYyODMxOTgyMDA0NTZiMS5iaW5kUG9wdXAocG9wdXBfMWVlZWNkMTkzZmUwNGJjNzg3OGFkMTNhZDZlMGY2N2EpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMWZjZjNjNWFlNGRkNDMyODg5MmY1NTc1ZDY2Njg0YWYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My43MTI3NTExLC03OS4zOTAxOTc1XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2E1YzU1OTA3NTcyNTQxMDdiYjhhNjk0NjYxOGMyZmIzID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sX2M3NWQxNTU4MjY2MDQ2NGZhMjk2MjFhYjY2NzI5NDhhID0gJCgnPGRpdiBpZD0iaHRtbF9jNzVkMTU1ODI2NjA0NjRmYTI5NjIxYWI2NjcyOTQ4YSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+RGF2aXN2aWxsZSBOb3J0aCwgQ2VudHJhbCBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF9hNWM1NTkwNzU3MjU0MTA3YmI4YTY5NDY2MThjMmZiMy5zZXRDb250ZW50KGh0bWxfYzc1ZDE1NTgyNjYwNDY0ZmEyOTYyMWFiNjY3Mjk0OGEpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfMWZjZjNjNWFlNGRkNDMyODg5MmY1NTc1ZDY2Njg0YWYuYmluZFBvcHVwKHBvcHVwX2E1YzU1OTA3NTcyNTQxMDdiYjhhNjk0NjYxOGMyZmIzKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzRkYmRhMGYyMjZlODQzMzU5YjNhNGMwNzU5NmM1OGQyID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNzE1MzgzNCwtNzkuNDA1Njc4NDAwMDAwMDFdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfNmQ3OGFjN2RhZmU2NGViNzkyMzM0OTQ2OWQyMTcyMTUgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfYjA2ODhlZDI0OWFlNDJlNTg1ZDk3NzQ3OTM4NmUwYmYgPSAkKCc8ZGl2IGlkPSJodG1sX2IwNjg4ZWQyNDlhZTQyZTU4NWQ5Nzc0NzkzODZlMGJmIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Ob3J0aCBUb3JvbnRvIFdlc3QsIENlbnRyYWwgVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfNmQ3OGFjN2RhZmU2NGViNzkyMzM0OTQ2OWQyMTcyMTUuc2V0Q29udGVudChodG1sX2IwNjg4ZWQyNDlhZTQyZTU4NWQ5Nzc0NzkzODZlMGJmKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzRkYmRhMGYyMjZlODQzMzU5YjNhNGMwNzU5NmM1OGQyLmJpbmRQb3B1cChwb3B1cF82ZDc4YWM3ZGFmZTY0ZWI3OTIzMzQ5NDY5ZDIxNzIxNSk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl84YzBiM2E1OTE4ZDQ0ZmRiOTIxNjM1OTk5MWZjNGE5OCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjcwNDMyNDQsLTc5LjM4ODc5MDFdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfNzdhMDM0MDBkZDYzNGVkOGFlODJmODczZDIzMWQyNmYgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfOGE5NDBkODI0OTk1NDg4YWI1NmJiMjJhM2E5N2M2ZWMgPSAkKCc8ZGl2IGlkPSJodG1sXzhhOTQwZDgyNDk5NTQ4OGFiNTZiYjIyYTNhOTdjNmVjIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5EYXZpc3ZpbGxlLCBDZW50cmFsIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzc3YTAzNDAwZGQ2MzRlZDhhZTgyZjg3M2QyMzFkMjZmLnNldENvbnRlbnQoaHRtbF84YTk0MGQ4MjQ5OTU0ODhhYjU2YmIyMmEzYTk3YzZlYyk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl84YzBiM2E1OTE4ZDQ0ZmRiOTIxNjM1OTk5MWZjNGE5OC5iaW5kUG9wdXAocG9wdXBfNzdhMDM0MDBkZDYzNGVkOGFlODJmODczZDIzMWQyNmYpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfOTM1MjY3OWYxOWQ2NDIxMWE2MDIyZmFkZDU4OTQwYzYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42ODk1NzQzLC03OS4zODMxNTk5MDAwMDAwMV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8xZWFhZGNhM2E2YWI0YTM0YTA3ZTFkNDZkYjM5NzJmMiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF8wMmZhOTU0ODkyYTA0ZDRmOTA3MTgzODMwMmNmOGVmNyA9ICQoJzxkaXYgaWQ9Imh0bWxfMDJmYTk1NDg5MmEwNGQ0ZjkwNzE4MzgzMDJjZjhlZjciIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPk1vb3JlIFBhcmssU3VtbWVyaGlsbCBFYXN0LCBDZW50cmFsIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzFlYWFkY2EzYTZhYjRhMzRhMDdlMWQ0NmRiMzk3MmYyLnNldENvbnRlbnQoaHRtbF8wMmZhOTU0ODkyYTA0ZDRmOTA3MTgzODMwMmNmOGVmNyk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl85MzUyNjc5ZjE5ZDY0MjExYTYwMjJmYWRkNTg5NDBjNi5iaW5kUG9wdXAocG9wdXBfMWVhYWRjYTNhNmFiNGEzNGEwN2UxZDQ2ZGIzOTcyZjIpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYjQyZGRiMzJiOWYyNDJhMThlYWVhODA4ZjcxNGY1MjEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42ODY0MTIyOTk5OTk5OSwtNzkuNDAwMDQ5M10sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF83MWNmZmY1ZDU0ZWU0N2E2OWQ5ZTg3MjcyYzBjOTdhNiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9mNzk5MWM4NDQ5ODU0NzA2YTExZWExMzIxOWI1ODA2MSA9ICQoJzxkaXYgaWQ9Imh0bWxfZjc5OTFjODQ0OTg1NDcwNmExMWVhMTMyMTliNTgwNjEiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkRlZXIgUGFyayxGb3Jlc3QgSGlsbCBTRSxSYXRobmVsbHksU291dGggSGlsbCxTdW1tZXJoaWxsIFdlc3QsIENlbnRyYWwgVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfNzFjZmZmNWQ1NGVlNDdhNjlkOWU4NzI3MmMwYzk3YTYuc2V0Q29udGVudChodG1sX2Y3OTkxYzg0NDk4NTQ3MDZhMTFlYTEzMjE5YjU4MDYxKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyX2I0MmRkYjMyYjlmMjQyYTE4ZWFlYTgwOGY3MTRmNTIxLmJpbmRQb3B1cChwb3B1cF83MWNmZmY1ZDU0ZWU0N2E2OWQ5ZTg3MjcyYzBjOTdhNik7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl82Nzk4ZDY0NTY1YTM0MzRiOWYzNTk3YWVkYzA2MWYyYyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY3OTU2MjYsLTc5LjM3NzUyOTQwMDAwMDAxXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2FmYjg0MGE2Y2I1ODRjNTM4OGZmYTU0OTBiMDRmOGFkID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sX2E3ZWJjOWQ4YjRmZDRkMDM4NGZiZThjNzMxNjQ5M2U4ID0gJCgnPGRpdiBpZD0iaHRtbF9hN2ViYzlkOGI0ZmQ0ZDAzODRmYmU4YzczMTY0OTNlOCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Um9zZWRhbGUsIERvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2FmYjg0MGE2Y2I1ODRjNTM4OGZmYTU0OTBiMDRmOGFkLnNldENvbnRlbnQoaHRtbF9hN2ViYzlkOGI0ZmQ0ZDAzODRmYmU4YzczMTY0OTNlOCk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl82Nzk4ZDY0NTY1YTM0MzRiOWYzNTk3YWVkYzA2MWYyYy5iaW5kUG9wdXAocG9wdXBfYWZiODQwYTZjYjU4NGM1Mzg4ZmZhNTQ5MGIwNGY4YWQpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZGQxODU1ZTlmYWEzNDBlZTgwN2E3YmM5ZjE3MDk0YWIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42Njc5NjcsLTc5LjM2NzY3NTNdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfOWQzYTRhYzNhNjE1NDRkMWI4MTAzMGZlY2RlMWRmYzcgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfMjM2NzkwZGZkZGZjNDAxMmE5ZmZhZjkxOTQ3YjgxZDAgPSAkKCc8ZGl2IGlkPSJodG1sXzIzNjc5MGRmZGRmYzQwMTJhOWZmYWY5MTk0N2I4MWQwIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5DYWJiYWdldG93bixTdC4gSmFtZXMgVG93biwgRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfOWQzYTRhYzNhNjE1NDRkMWI4MTAzMGZlY2RlMWRmYzcuc2V0Q29udGVudChodG1sXzIzNjc5MGRmZGRmYzQwMTJhOWZmYWY5MTk0N2I4MWQwKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyX2RkMTg1NWU5ZmFhMzQwZWU4MDdhN2JjOWYxNzA5NGFiLmJpbmRQb3B1cChwb3B1cF85ZDNhNGFjM2E2MTU0NGQxYjgxMDMwZmVjZGUxZGZjNyk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl81MTJkN2Y5N2NkNTQ0NWRjYjUxMzA3MDYyYzIyMGVmZSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY2NTg1OTksLTc5LjM4MzE1OTkwMDAwMDAxXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2NmZTNiNmI0Y2FkNjRjMDI5ZDkxMDg4YWM2OTIyYjEyID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzc1MzMwYmUyODc2MzQzNjRiZjNiZjdhZjgwNjFmZTI5ID0gJCgnPGRpdiBpZD0iaHRtbF83NTMzMGJlMjg3NjM0MzY0YmYzYmY3YWY4MDYxZmUyOSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Q2h1cmNoIGFuZCBXZWxsZXNsZXksIERvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2NmZTNiNmI0Y2FkNjRjMDI5ZDkxMDg4YWM2OTIyYjEyLnNldENvbnRlbnQoaHRtbF83NTMzMGJlMjg3NjM0MzY0YmYzYmY3YWY4MDYxZmUyOSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl81MTJkN2Y5N2NkNTQ0NWRjYjUxMzA3MDYyYzIyMGVmZS5iaW5kUG9wdXAocG9wdXBfY2ZlM2I2YjRjYWQ2NGMwMjlkOTEwODhhYzY5MjJiMTIpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfY2Q2ZWVhNGJhZjRlNDY4NWI3NzdlNjg2YzU4YmY4MjYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NTQyNTk5LC03OS4zNjA2MzU5XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzViOWU4NDY0ZjRhMzRmZWY5NzlhZjQ2YjliNDg4ZTJhID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzQ2YTcwYjNlZTFiZjQ1ZDRhZGJlNzNjMjNhZjE5ZDc4ID0gJCgnPGRpdiBpZD0iaHRtbF80NmE3MGIzZWUxYmY0NWQ0YWRiZTczYzIzYWYxOWQ3OCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+SGFyYm91cmZyb250LFJlZ2VudCBQYXJrLCBEb3dudG93biBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF81YjllODQ2NGY0YTM0ZmVmOTc5YWY0NmI5YjQ4OGUyYS5zZXRDb250ZW50KGh0bWxfNDZhNzBiM2VlMWJmNDVkNGFkYmU3M2MyM2FmMTlkNzgpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfY2Q2ZWVhNGJhZjRlNDY4NWI3NzdlNjg2YzU4YmY4MjYuYmluZFBvcHVwKHBvcHVwXzViOWU4NDY0ZjRhMzRmZWY5NzlhZjQ2YjliNDg4ZTJhKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzQ2NzJlNGJkZmM5MzQxMTA4YWIxZWRmODNmMzgxYTM2ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjU3MTYxOCwtNzkuMzc4OTM3MDk5OTk5OTldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfMmZhNzYxMzZlZjRmNDg1YmFjYjg2Yjc0NTkxZGY3M2UgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfMTM4ZDE5N2VmZmQ3NGUxM2EzYjUxYmQyMmVkY2E1ZmUgPSAkKCc8ZGl2IGlkPSJodG1sXzEzOGQxOTdlZmZkNzRlMTNhM2I1MWJkMjJlZGNhNWZlIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5SeWVyc29uLEdhcmRlbiBEaXN0cmljdCwgRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfMmZhNzYxMzZlZjRmNDg1YmFjYjg2Yjc0NTkxZGY3M2Uuc2V0Q29udGVudChodG1sXzEzOGQxOTdlZmZkNzRlMTNhM2I1MWJkMjJlZGNhNWZlKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzQ2NzJlNGJkZmM5MzQxMTA4YWIxZWRmODNmMzgxYTM2LmJpbmRQb3B1cChwb3B1cF8yZmE3NjEzNmVmNGY0ODViYWNiODZiNzQ1OTFkZjczZSk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8xZTZjNDMyYTZkYjc0NzBlYTg5MjQ2ZmNiMjk2NzM2ZiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY1MTQ5MzksLTc5LjM3NTQxNzldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfMDQ1ZGI4OTVmYzdhNDUzM2JjYjE3MzM2MGUyYTYwZjYgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfYWI2ZWFlOTc3M2Y5NGU2NjkyNGNkMjI3MjAyMjhhYzMgPSAkKCc8ZGl2IGlkPSJodG1sX2FiNmVhZTk3NzNmOTRlNjY5MjRjZDIyNzIwMjI4YWMzIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5TdC4gSmFtZXMgVG93biwgRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfMDQ1ZGI4OTVmYzdhNDUzM2JjYjE3MzM2MGUyYTYwZjYuc2V0Q29udGVudChodG1sX2FiNmVhZTk3NzNmOTRlNjY5MjRjZDIyNzIwMjI4YWMzKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzFlNmM0MzJhNmRiNzQ3MGVhODkyNDZmY2IyOTY3MzZmLmJpbmRQb3B1cChwb3B1cF8wNDVkYjg5NWZjN2E0NTMzYmNiMTczMzYwZTJhNjBmNik7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8xMDFiOGU1MWQ0NzI0N2FlOTU5N2UzYzZmNGU3ZWM0YSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY0NDc3MDc5OTk5OTk5NiwtNzkuMzczMzA2NF0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF9kNzNkYzA0ZjU0YmI0ZGFiODk4NTdjZWIxNjk0NGZkNSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9kYWYxZTU4ZmEzNmM0ZWJhOGU0ZDc3MGY1ZjY4YjMyNyA9ICQoJzxkaXYgaWQ9Imh0bWxfZGFmMWU1OGZhMzZjNGViYThlNGQ3NzBmNWY2OGIzMjciIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJlcmN6eSBQYXJrLCBEb3dudG93biBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF9kNzNkYzA0ZjU0YmI0ZGFiODk4NTdjZWIxNjk0NGZkNS5zZXRDb250ZW50KGh0bWxfZGFmMWU1OGZhMzZjNGViYThlNGQ3NzBmNWY2OGIzMjcpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfMTAxYjhlNTFkNDcyNDdhZTk1OTdlM2M2ZjRlN2VjNGEuYmluZFBvcHVwKHBvcHVwX2Q3M2RjMDRmNTRiYjRkYWI4OTg1N2NlYjE2OTQ0ZmQ1KTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzJkNWNjNjJlNGYxYTQ0NTFhNjc2OTg5NmYxM2M0N2E4ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjU3OTUyNCwtNzkuMzg3MzgyNl0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF9jNjhiMDVhZmIxNjE0ZDRiYWI2MTM0ODI2ZTk5MDRiZCA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF81MTdkMWZlZjZmMWM0MGMwOWNkNGUyMDhlYmU0ZWNmZSA9ICQoJzxkaXYgaWQ9Imh0bWxfNTE3ZDFmZWY2ZjFjNDBjMDljZDRlMjA4ZWJlNGVjZmUiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkNlbnRyYWwgQmF5IFN0cmVldCwgRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfYzY4YjA1YWZiMTYxNGQ0YmFiNjEzNDgyNmU5OTA0YmQuc2V0Q29udGVudChodG1sXzUxN2QxZmVmNmYxYzQwYzA5Y2Q0ZTIwOGViZTRlY2ZlKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzJkNWNjNjJlNGYxYTQ0NTFhNjc2OTg5NmYxM2M0N2E4LmJpbmRQb3B1cChwb3B1cF9jNjhiMDVhZmIxNjE0ZDRiYWI2MTM0ODI2ZTk5MDRiZCk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl84NGNhNDc1NWUwNmY0MmE3OTkwMjQ4ZmQ5ZGQyODI1OSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY1MDU3MTIwMDAwMDAxLC03OS4zODQ1Njc1XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzk0NDYxMTlmZjkxZDQwYjNhOThiZGNhZWE1ZDdlYWM1ID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzc2ZTUyNDBjNGRjNDRhNTBhNjc3YmZmZjNkYzc1ZDQ4ID0gJCgnPGRpdiBpZD0iaHRtbF83NmU1MjQwYzRkYzQ0YTUwYTY3N2JmZmYzZGM3NWQ0OCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QWRlbGFpZGUsS2luZyxSaWNobW9uZCwgRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfOTQ0NjExOWZmOTFkNDBiM2E5OGJkY2FlYTVkN2VhYzUuc2V0Q29udGVudChodG1sXzc2ZTUyNDBjNGRjNDRhNTBhNjc3YmZmZjNkYzc1ZDQ4KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzg0Y2E0NzU1ZTA2ZjQyYTc5OTAyNDhmZDlkZDI4MjU5LmJpbmRQb3B1cChwb3B1cF85NDQ2MTE5ZmY5MWQ0MGIzYTk4YmRjYWVhNWQ3ZWFjNSk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8wYmRiMjc5NGMyZjc0NTg5YmJlZWFhOGY3ZDI1NDQ2MyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY0MDgxNTcsLTc5LjM4MTc1MjI5OTk5OTk5XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzdiYjA2NDNkZWQzMDQwYWI5Y2M2NzRmNzViODdlZTA5ID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzQyNDhlYWMyMzE3NTRiMTI4ZWYyZDhmZWM2MDhhYmE0ID0gJCgnPGRpdiBpZD0iaHRtbF80MjQ4ZWFjMjMxNzU0YjEyOGVmMmQ4ZmVjNjA4YWJhNCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+SGFyYm91cmZyb250IEVhc3QsVG9yb250byBJc2xhbmRzLFVuaW9uIFN0YXRpb24sIERvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzdiYjA2NDNkZWQzMDQwYWI5Y2M2NzRmNzViODdlZTA5LnNldENvbnRlbnQoaHRtbF80MjQ4ZWFjMjMxNzU0YjEyOGVmMmQ4ZmVjNjA4YWJhNCk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl8wYmRiMjc5NGMyZjc0NTg5YmJlZWFhOGY3ZDI1NDQ2My5iaW5kUG9wdXAocG9wdXBfN2JiMDY0M2RlZDMwNDBhYjljYzY3NGY3NWI4N2VlMDkpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZWViMGE4MTE3YmE3NGUyNTk0OWNlZGVjNWQwMTM3ODUgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NDcxNzY4LC03OS4zODE1NzY0MDAwMDAwMV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF9hZTVhMzY5YzE3YzM0NTVkYmZjYzk3MDBkN2M4ODU1ZSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9hYmY3MDFhYTQwZjI0ZjM1ODc4OTkzYTg1MWMwZTRjNCA9ICQoJzxkaXYgaWQ9Imh0bWxfYWJmNzAxYWE0MGYyNGYzNTg3ODk5M2E4NTFjMGU0YzQiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkRlc2lnbiBFeGNoYW5nZSxUb3JvbnRvIERvbWluaW9uIENlbnRyZSwgRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfYWU1YTM2OWMxN2MzNDU1ZGJmY2M5NzAwZDdjODg1NWUuc2V0Q29udGVudChodG1sX2FiZjcwMWFhNDBmMjRmMzU4Nzg5OTNhODUxYzBlNGM0KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyX2VlYjBhODExN2JhNzRlMjU5NDljZWRlYzVkMDEzNzg1LmJpbmRQb3B1cChwb3B1cF9hZTVhMzY5YzE3YzM0NTVkYmZjYzk3MDBkN2M4ODU1ZSk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl82NGJiZGI5ZWYxYjQ0YzAxOTJlMzE0NGI4YWIyZTVmNCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY0ODE5ODUsLTc5LjM3OTgxNjkwMDAwMDAxXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzNhMmI3NzJhM2Y1YjQ1MDBhMWIyNGMyMDJmODRjZWRhID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzEwODUzNDQ2M2ViMzQ2NTZhNzJhNGRlODFjZjg1YTlhID0gJCgnPGRpdiBpZD0iaHRtbF8xMDg1MzQ0NjNlYjM0NjU2YTcyYTRkZTgxY2Y4NWE5YSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Q29tbWVyY2UgQ291cnQsVmljdG9yaWEgSG90ZWwsIERvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzNhMmI3NzJhM2Y1YjQ1MDBhMWIyNGMyMDJmODRjZWRhLnNldENvbnRlbnQoaHRtbF8xMDg1MzQ0NjNlYjM0NjU2YTcyYTRkZTgxY2Y4NWE5YSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl82NGJiZGI5ZWYxYjQ0YzAxOTJlMzE0NGI4YWIyZTVmNC5iaW5kUG9wdXAocG9wdXBfM2EyYjc3MmEzZjViNDUwMGExYjI0YzIwMmY4NGNlZGEpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMmRlZDZjNDk5MDZiNDBiNThiNTQ0ZWEyOTRhZjVmODUgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My43MTE2OTQ4LC03OS40MTY5MzU1OTk5OTk5OV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF9jNGFlMTQxNzEzZWM0ZDkwYmJiMmUwMzE5NjJjY2FiNSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF82YzE1Nzg5OTkzMzQ0NjBhODljMDk5M2I1MWVjN2VkYyA9ICQoJzxkaXYgaWQ9Imh0bWxfNmMxNTc4OTk5MzM0NDYwYTg5YzA5OTNiNTFlYzdlZGMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlJvc2VsYXduLCBDZW50cmFsIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2M0YWUxNDE3MTNlYzRkOTBiYmIyZTAzMTk2MmNjYWI1LnNldENvbnRlbnQoaHRtbF82YzE1Nzg5OTkzMzQ0NjBhODljMDk5M2I1MWVjN2VkYyk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl8yZGVkNmM0OTkwNmI0MGI1OGI1NDRlYTI5NGFmNWY4NS5iaW5kUG9wdXAocG9wdXBfYzRhZTE0MTcxM2VjNGQ5MGJiYjJlMDMxOTYyY2NhYjUpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYmNjYWI5M2E1ZjgwNDRhMWI3ZWM3MGFhNWIyZDJiZTAgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42OTY5NDc2LC03OS40MTEzMDcyMDAwMDAwMV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF80OWM1Y2FlN2UxYWI0ZTAyYjA3NWEzZGM1NTRlMzgzMSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF8xNDQxOWEyZTU4ZTE0MDczYjI4MjQ5ODhlNjkwMGVjMyA9ICQoJzxkaXYgaWQ9Imh0bWxfMTQ0MTlhMmU1OGUxNDA3M2IyODI0OTg4ZTY5MDBlYzMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkZvcmVzdCBIaWxsIE5vcnRoLEZvcmVzdCBIaWxsIFdlc3QsIENlbnRyYWwgVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfNDljNWNhZTdlMWFiNGUwMmIwNzVhM2RjNTU0ZTM4MzEuc2V0Q29udGVudChodG1sXzE0NDE5YTJlNThlMTQwNzNiMjgyNDk4OGU2OTAwZWMzKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyX2JjY2FiOTNhNWY4MDQ0YTFiN2VjNzBhYTViMmQyYmUwLmJpbmRQb3B1cChwb3B1cF80OWM1Y2FlN2UxYWI0ZTAyYjA3NWEzZGM1NTRlMzgzMSk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl84YWEwOTY1ZjUyYWI0MDQ2YTNlYTlkODRmMzBlYWIzNSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY3MjcwOTcsLTc5LjQwNTY3ODQwMDAwMDAxXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2JjMDM2MWQyMTYxMjQ3NjRiOTU3OWQyY2NjZGJhMDdjID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzI5MGNhNDcyYTZjMjQxODk5MzJhMDRiZmZlOTI3ZWMzID0gJCgnPGRpdiBpZD0iaHRtbF8yOTBjYTQ3MmE2YzI0MTg5OTMyYTA0YmZmZTkyN2VjMyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+VGhlIEFubmV4LE5vcnRoIE1pZHRvd24sWW9ya3ZpbGxlLCBDZW50cmFsIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2JjMDM2MWQyMTYxMjQ3NjRiOTU3OWQyY2NjZGJhMDdjLnNldENvbnRlbnQoaHRtbF8yOTBjYTQ3MmE2YzI0MTg5OTMyYTA0YmZmZTkyN2VjMyk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl84YWEwOTY1ZjUyYWI0MDQ2YTNlYTlkODRmMzBlYWIzNS5iaW5kUG9wdXAocG9wdXBfYmMwMzYxZDIxNjEyNDc2NGI5NTc5ZDJjY2NkYmEwN2MpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNDVhNTY1NTVhYWIwNGUyZWIwNWQ4NTIyOTA1MjA2MTcgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NjI2OTU2LC03OS40MDAwNDkzXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2E2Y2IzMDg2NTcxZTRjMDU4NDJkZDVlZTM4ZWRiMjI0ID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sX2U2NGIyYTljYWJlOTQxYTc5YzFlNDBkNDRjMTFiODJmID0gJCgnPGRpdiBpZD0iaHRtbF9lNjRiMmE5Y2FiZTk0MWE3OWMxZTQwZDQ0YzExYjgyZiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+SGFyYm9yZCxVbml2ZXJzaXR5IG9mIFRvcm9udG8sIERvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2E2Y2IzMDg2NTcxZTRjMDU4NDJkZDVlZTM4ZWRiMjI0LnNldENvbnRlbnQoaHRtbF9lNjRiMmE5Y2FiZTk0MWE3OWMxZTQwZDQ0YzExYjgyZik7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl80NWE1NjU1NWFhYjA0ZTJlYjA1ZDg1MjI5MDUyMDYxNy5iaW5kUG9wdXAocG9wdXBfYTZjYjMwODY1NzFlNGMwNTg0MmRkNWVlMzhlZGIyMjQpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZmViNWJkYWM2ZTMxNGNjMzhiOWQxNGQ0YzdlODIxNWYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NTMyMDU3LC03OS40MDAwNDkzXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzdhNWY1MmJiOTU5MjRiNWViMmM2YTNiNDBhYmVkNmJhID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sX2E1MDdlYzcxNmY2ZTRiMTliMTdjMTAwNjhmYmRjMDE4ID0gJCgnPGRpdiBpZD0iaHRtbF9hNTA3ZWM3MTZmNmU0YjE5YjE3YzEwMDY4ZmJkYzAxOCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Q2hpbmF0b3duLEdyYW5nZSBQYXJrLEtlbnNpbmd0b24gTWFya2V0LCBEb3dudG93biBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF83YTVmNTJiYjk1OTI0YjVlYjJjNmEzYjQwYWJlZDZiYS5zZXRDb250ZW50KGh0bWxfYTUwN2VjNzE2ZjZlNGIxOWIxN2MxMDA2OGZiZGMwMTgpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfZmViNWJkYWM2ZTMxNGNjMzhiOWQxNGQ0YzdlODIxNWYuYmluZFBvcHVwKHBvcHVwXzdhNWY1MmJiOTU5MjRiNWViMmM2YTNiNDBhYmVkNmJhKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzQwMTAzNzYxMDAyZTRmNjQ5N2E2NjQ0YTQyYTAwZTQ1ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjI4OTQ2NywtNzkuMzk0NDE5OV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8yZDVhN2RmYWMyNjE0YTBmODgzYmJhOWNiOTYxMGQ3MCA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9iZjViNTg5YjRiYzQ0NzI2YmQwY2U5MDJkMzAxZTY3MiA9ICQoJzxkaXYgaWQ9Imh0bWxfYmY1YjU4OWI0YmM0NDcyNmJkMGNlOTAyZDMwMWU2NzIiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkNOIFRvd2VyLEJhdGh1cnN0IFF1YXksSXNsYW5kIGFpcnBvcnQsSGFyYm91cmZyb250IFdlc3QsS2luZyBhbmQgU3BhZGluYSxSYWlsd2F5IExhbmRzLFNvdXRoIE5pYWdhcmEsIERvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzJkNWE3ZGZhYzI2MTRhMGY4ODNiYmE5Y2I5NjEwZDcwLnNldENvbnRlbnQoaHRtbF9iZjViNTg5YjRiYzQ0NzI2YmQwY2U5MDJkMzAxZTY3Mik7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl80MDEwMzc2MTAwMmU0ZjY0OTdhNjY0NGE0MmEwMGU0NS5iaW5kUG9wdXAocG9wdXBfMmQ1YTdkZmFjMjYxNGEwZjg4M2JiYTljYjk2MTBkNzApOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZjkwNjU4ZTQxNTkyNDZhZTlkNDE0N2NmYTM0OWNjYWEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NDY0MzUyLC03OS4zNzQ4NDU5OTk5OTk5OV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF85MDQzMWNmZGI2OWQ0Njg0YTg1MzFkN2FjZWVkNzMyMSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF8wZjk2ZjUwODZkZjg0OGMxYTM5ZmZiY2ZhNGI1NzYyNSA9ICQoJzxkaXYgaWQ9Imh0bWxfMGY5NmY1MDg2ZGY4NDhjMWEzOWZmYmNmYTRiNTc2MjUiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlN0biBBIFBPIEJveGVzIDI1IFRoZSBFc3BsYW5hZGUsIERvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzkwNDMxY2ZkYjY5ZDQ2ODRhODUzMWQ3YWNlZWQ3MzIxLnNldENvbnRlbnQoaHRtbF8wZjk2ZjUwODZkZjg0OGMxYTM5ZmZiY2ZhNGI1NzYyNSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9mOTA2NThlNDE1OTI0NmFlOWQ0MTQ3Y2ZhMzQ5Y2NhYS5iaW5kUG9wdXAocG9wdXBfOTA0MzFjZmRiNjlkNDY4NGE4NTMxZDdhY2VlZDczMjEpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYTA0NGYzNTY2YTU0NDBkNmI0Y2E2YmNiOTI2MTA3ODggPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NDg0MjkyLC03OS4zODIyODAyXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2FkZjYyOGJkNTM5OTQwNDk4MDg3ZGFiZTJlNWM1YWJhID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzdhNzExMjI2YzRiOTQwYTI5MDg5ODY4MGU2ODhkZDAyID0gJCgnPGRpdiBpZD0iaHRtbF83YTcxMTIyNmM0Yjk0MGEyOTA4OTg2ODBlNjg4ZGQwMiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Rmlyc3QgQ2FuYWRpYW4gUGxhY2UsVW5kZXJncm91bmQgY2l0eSwgRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfYWRmNjI4YmQ1Mzk5NDA0OTgwODdkYWJlMmU1YzVhYmEuc2V0Q29udGVudChodG1sXzdhNzExMjI2YzRiOTQwYTI5MDg5ODY4MGU2ODhkZDAyKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyX2EwNDRmMzU2NmE1NDQwZDZiNGNhNmJjYjkyNjEwNzg4LmJpbmRQb3B1cChwb3B1cF9hZGY2MjhiZDUzOTk0MDQ5ODA4N2RhYmUyZTVjNWFiYSk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9iMDM0YTlkNWYxNDk0YWVkODZmYWRkMmM1OWVkNWU3NyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY2OTU0MiwtNzkuNDIyNTYzN10sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF81MjUxYmZjOGQwZmE0YjliYmRmODM5ZTg4N2RmMDhkMSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF8zOWJhZjA5NWYxMmU0ZjBhYWJmMTRhZjUzMTJiMjgyMCA9ICQoJzxkaXYgaWQ9Imh0bWxfMzliYWYwOTVmMTJlNGYwYWFiZjE0YWY1MzEyYjI4MjAiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkNocmlzdGllLCBEb3dudG93biBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF81MjUxYmZjOGQwZmE0YjliYmRmODM5ZTg4N2RmMDhkMS5zZXRDb250ZW50KGh0bWxfMzliYWYwOTVmMTJlNGYwYWFiZjE0YWY1MzEyYjI4MjApOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfYjAzNGE5ZDVmMTQ5NGFlZDg2ZmFkZDJjNTllZDVlNzcuYmluZFBvcHVwKHBvcHVwXzUyNTFiZmM4ZDBmYTRiOWJiZGY4MzllODg3ZGYwOGQxKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzZkYzhkOGE0M2IxZDQ4MDdhNGNlMjAxMzI2NWQyYTY1ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjY5MDA1MTAwMDAwMDEsLTc5LjQ0MjI1OTNdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfZDY1MThkZTZjNTZiNGEwNGFhMTkwMWYyOTA2Y2NkMzUgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfN2JkOTEwNTk0MjE1NGZlOWI5M2Q2OTI3MzU5YzdhNjYgPSAkKCc8ZGl2IGlkPSJodG1sXzdiZDkxMDU5NDIxNTRmZTliOTNkNjkyNzM1OWM3YTY2IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Eb3ZlcmNvdXJ0IFZpbGxhZ2UsRHVmZmVyaW4sIFdlc3QgVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfZDY1MThkZTZjNTZiNGEwNGFhMTkwMWYyOTA2Y2NkMzUuc2V0Q29udGVudChodG1sXzdiZDkxMDU5NDIxNTRmZTliOTNkNjkyNzM1OWM3YTY2KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzZkYzhkOGE0M2IxZDQ4MDdhNGNlMjAxMzI2NWQyYTY1LmJpbmRQb3B1cChwb3B1cF9kNjUxOGRlNmM1NmI0YTA0YWExOTAxZjI5MDZjY2QzNSk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl82ZDA2MGQ5ZWJmYmE0NjUwYTkxYjliMWZmYzUwYmI5ZCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY0NzkyNjcwMDAwMDAwNiwtNzkuNDE5NzQ5N10sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8wZTk5ODgzMWFjMjg0YzQzYjcyZTFlZmNhZTY4ODRmMSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9iY2QwZmI1YTcyMDM0MWI1OGE1OWZhOTI5NzQxM2Q4NyA9ICQoJzxkaXYgaWQ9Imh0bWxfYmNkMGZiNWE3MjAzNDFiNThhNTlmYTkyOTc0MTNkODciIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkxpdHRsZSBQb3J0dWdhbCxUcmluaXR5LCBXZXN0IFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzBlOTk4ODMxYWMyODRjNDNiNzJlMWVmY2FlNjg4NGYxLnNldENvbnRlbnQoaHRtbF9iY2QwZmI1YTcyMDM0MWI1OGE1OWZhOTI5NzQxM2Q4Nyk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl82ZDA2MGQ5ZWJmYmE0NjUwYTkxYjliMWZmYzUwYmI5ZC5iaW5kUG9wdXAocG9wdXBfMGU5OTg4MzFhYzI4NGM0M2I3MmUxZWZjYWU2ODg0ZjEpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZTFlM2IwZWEzNTE2NDA1ODk1M2IyZTJkYTYxNjc3MzggPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42MzY4NDcyLC03OS40MjgxOTE0MDAwMDAwMl0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF84MmMzOTU3YTdmOTQ0ZjMwOGViNjk0MTkwOTdmMzM1NSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF83NDg3ZWIwOTkyNTQ0Y2ZhYjUyZmM0YzU5NDAyMzc3OCA9ICQoJzxkaXYgaWQ9Imh0bWxfNzQ4N2ViMDk5MjU0NGNmYWI1MmZjNGM1OTQwMjM3NzgiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJyb2NrdG9uLEV4aGliaXRpb24gUGxhY2UsUGFya2RhbGUgVmlsbGFnZSwgV2VzdCBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF84MmMzOTU3YTdmOTQ0ZjMwOGViNjk0MTkwOTdmMzM1NS5zZXRDb250ZW50KGh0bWxfNzQ4N2ViMDk5MjU0NGNmYWI1MmZjNGM1OTQwMjM3NzgpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfZTFlM2IwZWEzNTE2NDA1ODk1M2IyZTJkYTYxNjc3MzguYmluZFBvcHVwKHBvcHVwXzgyYzM5NTdhN2Y5NDRmMzA4ZWI2OTQxOTA5N2YzMzU1KTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2VmYWI1ZjEzN2Y4ZjQzMTVhMjlkMGUwNzYxM2NiZjRhID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjYxNjA4MywtNzkuNDY0NzYzMjk5OTk5OTldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfZmVjZGUyMGM3NWQwNDg4NjhmZjIzNWE2MDk3YzU0M2QgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfOGQxMmRhMTYwY2JjNGI4MWEyNmI2YWU1NjZkYjAzN2EgPSAkKCc8ZGl2IGlkPSJodG1sXzhkMTJkYTE2MGNiYzRiODFhMjZiNmFlNTY2ZGIwMzdhIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5IaWdoIFBhcmssVGhlIEp1bmN0aW9uIFNvdXRoLCBXZXN0IFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2ZlY2RlMjBjNzVkMDQ4ODY4ZmYyMzVhNjA5N2M1NDNkLnNldENvbnRlbnQoaHRtbF84ZDEyZGExNjBjYmM0YjgxYTI2YjZhZTU2NmRiMDM3YSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9lZmFiNWYxMzdmOGY0MzE1YTI5ZDBlMDc2MTNjYmY0YS5iaW5kUG9wdXAocG9wdXBfZmVjZGUyMGM3NWQwNDg4NjhmZjIzNWE2MDk3YzU0M2QpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfY2Y1MjEzNWFhZmMxNGI5OGIzZTk1MjE2NjUyYzI4NzkgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NDg5NTk3LC03OS40NTYzMjVdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfYTEyNmNlNDRhYTliNDBhMWE3NzEzNWU3ZDg2ZjM1NzAgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfM2RkOTE3ZmRhYTUxNGMwMGJlZmU4M2RkMGViZGRjYjIgPSAkKCc8ZGl2IGlkPSJodG1sXzNkZDkxN2ZkYWE1MTRjMDBiZWZlODNkZDBlYmRkY2IyIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5QYXJrZGFsZSxSb25jZXN2YWxsZXMsIFdlc3QgVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfYTEyNmNlNDRhYTliNDBhMWE3NzEzNWU3ZDg2ZjM1NzAuc2V0Q29udGVudChodG1sXzNkZDkxN2ZkYWE1MTRjMDBiZWZlODNkZDBlYmRkY2IyKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyX2NmNTIxMzVhYWZjMTRiOThiM2U5NTIxNjY1MmMyODc5LmJpbmRQb3B1cChwb3B1cF9hMTI2Y2U0NGFhOWI0MGExYTc3MTM1ZTdkODZmMzU3MCk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl84NDAwZGNiN2U2ZTA0NGY2YWE4ODIxM2I1NTJhNzg4MiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY1MTU3MDYsLTc5LjQ4NDQ0OTldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfMWRlZjk5N2JmOWViNGFmZDg2Y2FlY2MwMjdjZDBmYzEgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfOGQwNzVmODQzMWU4NGQxMWEwOTM0ZWE5YjE5ZDg5ZjAgPSAkKCc8ZGl2IGlkPSJodG1sXzhkMDc1Zjg0MzFlODRkMTFhMDkzNGVhOWIxOWQ4OWYwIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5SdW5ueW1lZGUsU3dhbnNlYSwgV2VzdCBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF8xZGVmOTk3YmY5ZWI0YWZkODZjYWVjYzAyN2NkMGZjMS5zZXRDb250ZW50KGh0bWxfOGQwNzVmODQzMWU4NGQxMWEwOTM0ZWE5YjE5ZDg5ZjApOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfODQwMGRjYjdlNmUwNDRmNmFhODgyMTNiNTUyYTc4ODIuYmluZFBvcHVwKHBvcHVwXzFkZWY5OTdiZjllYjRhZmQ4NmNhZWNjMDI3Y2QwZmMxKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzk2YmUwNTU2OTlkMzQwNWNiMmFjMGQxMTg4Y2NkZDY1ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjYyNzQzOSwtNzkuMzIxNTU4XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2FlYjY2MjEyODRmMTQyZGRhNDU5NDM0NDQ5ZWYwYTBlID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sX2E2YmIzMWVhODI3ODRjNTNiZTYwYTAxYjliNmFiOWRiID0gJCgnPGRpdiBpZD0iaHRtbF9hNmJiMzFlYTgyNzg0YzUzYmU2MGEwMWI5YjZhYjlkYiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzaW5lc3MgUmVwbHkgTWFpbCBQcm9jZXNzaW5nIENlbnRyZSA5NjkgRWFzdGVybiwgRWFzdCBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF9hZWI2NjIxMjg0ZjE0MmRkYTQ1OTQzNDQ0OWVmMGEwZS5zZXRDb250ZW50KGh0bWxfYTZiYjMxZWE4Mjc4NGM1M2JlNjBhMDFiOWI2YWI5ZGIpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfOTZiZTA1NTY5OWQzNDA1Y2IyYWMwZDExODhjY2RkNjUuYmluZFBvcHVwKHBvcHVwX2FlYjY2MjEyODRmMTQyZGRhNDU5NDM0NDQ5ZWYwYTBlKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2Q4MWI0ZTdiODBmODRjOWVhNzE0ZTBkYmRmMjU2ZTExID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjc2MzU3Mzk5OTk5OTksLTc5LjI5MzAzMTJdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfODljNzQ4MDNmOTk2NDI0YmFjNzdmNzRmZmI1NWYxNTkgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfODk2NzlhNzE2MmJiNDAwOGEzNThmMTE4NzcxOWQxNzQgPSAkKCc8ZGl2IGlkPSJodG1sXzg5Njc5YTcxNjJiYjQwMDhhMzU4ZjExODc3MTlkMTc0IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5UaGUgQmVhY2hlcy0tRWFzdCBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF84OWM3NDgwM2Y5OTY0MjRiYWM3N2Y3NGZmYjU1ZjE1OS5zZXRDb250ZW50KGh0bWxfODk2NzlhNzE2MmJiNDAwOGEzNThmMTE4NzcxOWQxNzQpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfZDgxYjRlN2I4MGY4NGM5ZWE3MTRlMGRiZGYyNTZlMTEuYmluZFBvcHVwKHBvcHVwXzg5Yzc0ODAzZjk5NjQyNGJhYzc3Zjc0ZmZiNTVmMTU5KTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2MwMDYyMDViMjMyZTQ1Mjc4NmU1NDVjNjdlZGRhNzYyID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjc5NTU3MSwtNzkuMzUyMTg4XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2JkMzkxNjY1NTIwMjQyZGM4MmQwMWFkNTc2YTAzM2UyID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzY2NzgzZDU1ZmFlYTQ4YWE4NWUzMjliMzkzNGQzMmRjID0gJCgnPGRpdiBpZD0iaHRtbF82Njc4M2Q1NWZhZWE0OGFhODVlMzI5YjM5MzRkMzJkYyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+VGhlIERhbmZvcnRoIFdlc3QsUml2ZXJkYWxlLS1FYXN0IFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2JkMzkxNjY1NTIwMjQyZGM4MmQwMWFkNTc2YTAzM2UyLnNldENvbnRlbnQoaHRtbF82Njc4M2Q1NWZhZWE0OGFhODVlMzI5YjM5MzRkMzJkYyk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9jMDA2MjA1YjIzMmU0NTI3ODZlNTQ1YzY3ZWRkYTc2Mi5iaW5kUG9wdXAocG9wdXBfYmQzOTE2NjU1MjAyNDJkYzgyZDAxYWQ1NzZhMDMzZTIpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYzI4NWJkMjlmZDJhNDY4NmJiZmQ1NGY4NWRhNzdkYWQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42Njg5OTg1LC03OS4zMTU1NzE1OTk5OTk5OF0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF81Y2NhMDJlZmJhMTQ0MzI0YjRlNTRhYTg5ZDQwN2NiYSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9mMzQzNjliNGU5YWE0ODViOTA2ZjA1ODI4NmFlNDliMCA9ICQoJzxkaXYgaWQ9Imh0bWxfZjM0MzY5YjRlOWFhNDg1YjkwNmYwNTgyODZhZTQ5YjAiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlRoZSBCZWFjaGVzIFdlc3QsSW5kaWEgQmF6YWFyLS1FYXN0IFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzVjY2EwMmVmYmExNDQzMjRiNGU1NGFhODlkNDA3Y2JhLnNldENvbnRlbnQoaHRtbF9mMzQzNjliNGU5YWE0ODViOTA2ZjA1ODI4NmFlNDliMCk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9jMjg1YmQyOWZkMmE0Njg2YmJmZDU0Zjg1ZGE3N2RhZC5iaW5kUG9wdXAocG9wdXBfNWNjYTAyZWZiYTE0NDMyNGI0ZTU0YWE4OWQ0MDdjYmEpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMDE1MjhjM2I4NDc5NDU5OGI3NWVmMzgxODM0MzljZDYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NTk1MjU1LC03OS4zNDA5MjNdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfMTdiMDU3Y2ViZTdkNGEwOTgzNTUxMTFjZTg4NTI5YzQgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfYjcxYzlmODRkY2I0NGFhMDgwZWI1MjExMjdhOGVkNjYgPSAkKCc8ZGl2IGlkPSJodG1sX2I3MWM5Zjg0ZGNiNDRhYTA4MGViNTIxMTI3YThlZDY2IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5TdHVkaW8gRGlzdHJpY3QtLUVhc3QgVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfMTdiMDU3Y2ViZTdkNGEwOTgzNTUxMTFjZTg4NTI5YzQuc2V0Q29udGVudChodG1sX2I3MWM5Zjg0ZGNiNDRhYTA4MGViNTIxMTI3YThlZDY2KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzAxNTI4YzNiODQ3OTQ1OThiNzVlZjM4MTgzNDM5Y2Q2LmJpbmRQb3B1cChwb3B1cF8xN2IwNTdjZWJlN2Q0YTA5ODM1NTExMWNlODg1MjljNCk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl80ZjE4NjEzODM5ZTE0YmQyYjQ1YTRmMWNlZmM2ZDA0ZSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjcyODAyMDUsLTc5LjM4ODc5MDFdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfNjY1NmFmZWIwM2MwNDg3OGJiNjI0ZGEyNTU2N2JjM2UgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfY2JmMzQwYTNkY2M0NGJkZGJlNjQ3OGE2YTIyOTFiZGEgPSAkKCc8ZGl2IGlkPSJodG1sX2NiZjM0MGEzZGNjNDRiZGRiZTY0NzhhNmEyMjkxYmRhIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5MYXdyZW5jZSBQYXJrLS1DZW50cmFsIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzY2NTZhZmViMDNjMDQ4NzhiYjYyNGRhMjU1NjdiYzNlLnNldENvbnRlbnQoaHRtbF9jYmYzNDBhM2RjYzQ0YmRkYmU2NDc4YTZhMjI5MWJkYSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl80ZjE4NjEzODM5ZTE0YmQyYjQ1YTRmMWNlZmM2ZDA0ZS5iaW5kUG9wdXAocG9wdXBfNjY1NmFmZWIwM2MwNDg3OGJiNjI0ZGEyNTU2N2JjM2UpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYWFiNjRhOWQ0NmMyNDg4NDgwODgzNDZiZjI1YmE4MmQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My43MTI3NTExLC03OS4zOTAxOTc1XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzY2ZWZlZGViZWU5OTQyNzNiOWJmMWY2MTBlYmZjMzkxID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzRlN2Q5OWFlZjlhNzQ0Y2JiMWU4MTg1MDJkYzg0NjhhID0gJCgnPGRpdiBpZD0iaHRtbF80ZTdkOTlhZWY5YTc0NGNiYjFlODE4NTAyZGM4NDY4YSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+RGF2aXN2aWxsZSBOb3J0aC0tQ2VudHJhbCBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF82NmVmZWRlYmVlOTk0MjczYjliZjFmNjEwZWJmYzM5MS5zZXRDb250ZW50KGh0bWxfNGU3ZDk5YWVmOWE3NDRjYmIxZTgxODUwMmRjODQ2OGEpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfYWFiNjRhOWQ0NmMyNDg4NDgwODgzNDZiZjI1YmE4MmQuYmluZFBvcHVwKHBvcHVwXzY2ZWZlZGViZWU5OTQyNzNiOWJmMWY2MTBlYmZjMzkxKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2EwZjdjYmZjNDkwYzQ2NGViOGNlNDY4NjVlODExOWViID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNzE1MzgzNCwtNzkuNDA1Njc4NDAwMDAwMDFdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfNjlmMzY5MWYwNWZiNDVhODgxMGZjN2IxOTY3YzJlYzIgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfOTU0MDU1ZmEwOWJkNGZjZGFmOWRkMDI0OTQxZjQ2MjQgPSAkKCc8ZGl2IGlkPSJodG1sXzk1NDA1NWZhMDliZDRmY2RhZjlkZDAyNDk0MWY0NjI0IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Ob3J0aCBUb3JvbnRvIFdlc3QtLUNlbnRyYWwgVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfNjlmMzY5MWYwNWZiNDVhODgxMGZjN2IxOTY3YzJlYzIuc2V0Q29udGVudChodG1sXzk1NDA1NWZhMDliZDRmY2RhZjlkZDAyNDk0MWY0NjI0KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyX2EwZjdjYmZjNDkwYzQ2NGViOGNlNDY4NjVlODExOWViLmJpbmRQb3B1cChwb3B1cF82OWYzNjkxZjA1ZmI0NWE4ODEwZmM3YjE5NjdjMmVjMik7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl80MGExNjUyMjEyMTc0NzgxYTY5NGI2ZTFlYTQ0NjZiMiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjcwNDMyNDQsLTc5LjM4ODc5MDFdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfYjQwZThiMWU1YTA4NGZlYThhMGU2NWJjZGVhYzRjNTUgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfOTM4YWNhM2UyZTFjNDI5OWE4NTE0ZTE3MjVkYzliNDcgPSAkKCc8ZGl2IGlkPSJodG1sXzkzOGFjYTNlMmUxYzQyOTlhODUxNGUxNzI1ZGM5YjQ3IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5EYXZpc3ZpbGxlLS1DZW50cmFsIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2I0MGU4YjFlNWEwODRmZWE4YTBlNjViY2RlYWM0YzU1LnNldENvbnRlbnQoaHRtbF85MzhhY2EzZTJlMWM0Mjk5YTg1MTRlMTcyNWRjOWI0Nyk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl80MGExNjUyMjEyMTc0NzgxYTY5NGI2ZTFlYTQ0NjZiMi5iaW5kUG9wdXAocG9wdXBfYjQwZThiMWU1YTA4NGZlYThhMGU2NWJjZGVhYzRjNTUpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNDljMjNlZDBiMzYyNDg2NDg2NDRiMDY3YTFjZTc4NGEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42ODk1NzQzLC03OS4zODMxNTk5MDAwMDAwMV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF80N2JlNzNjMzc3YzA0MDc1ODIxMWRiMDdkNDhlYjA4MiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9jNTEzYzNhMDczZWE0Y2U5ODg5YmM3NWYyMGQ3Y2EwOSA9ICQoJzxkaXYgaWQ9Imh0bWxfYzUxM2MzYTA3M2VhNGNlOTg4OWJjNzVmMjBkN2NhMDkiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPk1vb3JlIFBhcmssU3VtbWVyaGlsbCBFYXN0LS1DZW50cmFsIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzQ3YmU3M2MzNzdjMDQwNzU4MjExZGIwN2Q0OGViMDgyLnNldENvbnRlbnQoaHRtbF9jNTEzYzNhMDczZWE0Y2U5ODg5YmM3NWYyMGQ3Y2EwOSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl80OWMyM2VkMGIzNjI0ODY0ODY0NGIwNjdhMWNlNzg0YS5iaW5kUG9wdXAocG9wdXBfNDdiZTczYzM3N2MwNDA3NTgyMTFkYjA3ZDQ4ZWIwODIpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNTMwMjQ4NDhhZWVhNDRkMjhjNWQ3OWRhMTc0ZjM1NWIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42ODY0MTIyOTk5OTk5OSwtNzkuNDAwMDQ5M10sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8wMTJhZDA5ZjMxYzU0ODgzOGJhZDAwNDQxOTg2MTE4MyA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF81MGZhYWJmOGI0YmE0ODFjOTI1MGQxN2ZhOWMxZTk2NiA9ICQoJzxkaXYgaWQ9Imh0bWxfNTBmYWFiZjhiNGJhNDgxYzkyNTBkMTdmYTljMWU5NjYiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkRlZXIgUGFyayxGb3Jlc3QgSGlsbCBTRSxSYXRobmVsbHksU291dGggSGlsbCxTdW1tZXJoaWxsIFdlc3QtLUNlbnRyYWwgVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfMDEyYWQwOWYzMWM1NDg4MzhiYWQwMDQ0MTk4NjExODMuc2V0Q29udGVudChodG1sXzUwZmFhYmY4YjRiYTQ4MWM5MjUwZDE3ZmE5YzFlOTY2KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzUzMDI0ODQ4YWVlYTQ0ZDI4YzVkNzlkYTE3NGYzNTViLmJpbmRQb3B1cChwb3B1cF8wMTJhZDA5ZjMxYzU0ODgzOGJhZDAwNDQxOTg2MTE4Myk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9lZTMyNjk4YzdiMjA0NTg0OTNmYTdlYzA1ODM1OTMyNCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY3OTU2MjYsLTc5LjM3NzUyOTQwMDAwMDAxXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzNiYjJmOWJiOGNkYjQwZjA5NzA2YzJkN2MwNDM3N2QyID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzUwZjZhZTZkMzZkNTQ1MGE5MjI4Y2YyOTQxNjI1YzIyID0gJCgnPGRpdiBpZD0iaHRtbF81MGY2YWU2ZDM2ZDU0NTBhOTIyOGNmMjk0MTYyNWMyMiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Um9zZWRhbGUtLURvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzNiYjJmOWJiOGNkYjQwZjA5NzA2YzJkN2MwNDM3N2QyLnNldENvbnRlbnQoaHRtbF81MGY2YWU2ZDM2ZDU0NTBhOTIyOGNmMjk0MTYyNWMyMik7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9lZTMyNjk4YzdiMjA0NTg0OTNmYTdlYzA1ODM1OTMyNC5iaW5kUG9wdXAocG9wdXBfM2JiMmY5YmI4Y2RiNDBmMDk3MDZjMmQ3YzA0Mzc3ZDIpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNDMxZmU1ODZjZDZhNDBiYWExYmU5ZGRhODQ4ZjFhNzkgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42Njc5NjcsLTc5LjM2NzY3NTNdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfNzMzNzBkZDEyMjkwNDQ0NmE3NWIwZjUwMTgzNmVmNzggPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfNmU4OGZiNGJjYWQyNGFjMWFiNTQ0MzljY2FiZjZkMmUgPSAkKCc8ZGl2IGlkPSJodG1sXzZlODhmYjRiY2FkMjRhYzFhYjU0NDM5Y2NhYmY2ZDJlIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5DYWJiYWdldG93bixTdC4gSmFtZXMgVG93bi0tRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfNzMzNzBkZDEyMjkwNDQ0NmE3NWIwZjUwMTgzNmVmNzguc2V0Q29udGVudChodG1sXzZlODhmYjRiY2FkMjRhYzFhYjU0NDM5Y2NhYmY2ZDJlKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzQzMWZlNTg2Y2Q2YTQwYmFhMWJlOWRkYTg0OGYxYTc5LmJpbmRQb3B1cChwb3B1cF83MzM3MGRkMTIyOTA0NDQ2YTc1YjBmNTAxODM2ZWY3OCk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8xNTY0ZTQ0ODkxNmM0NWQ3YjE2ODhlNDFjN2I0NmJlOSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY2NTg1OTksLTc5LjM4MzE1OTkwMDAwMDAxXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzIxZWRlMjE0YzdkYTQzNTViMDMxY2FlMjUwNDc5ZjAzID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sX2NkNGQ2ZjU5NmIxZDRlYjlhNjJlMDU3ZDlhMWQwNTU4ID0gJCgnPGRpdiBpZD0iaHRtbF9jZDRkNmY1OTZiMWQ0ZWI5YTYyZTA1N2Q5YTFkMDU1OCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Q2h1cmNoIGFuZCBXZWxsZXNsZXktLURvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzIxZWRlMjE0YzdkYTQzNTViMDMxY2FlMjUwNDc5ZjAzLnNldENvbnRlbnQoaHRtbF9jZDRkNmY1OTZiMWQ0ZWI5YTYyZTA1N2Q5YTFkMDU1OCk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl8xNTY0ZTQ0ODkxNmM0NWQ3YjE2ODhlNDFjN2I0NmJlOS5iaW5kUG9wdXAocG9wdXBfMjFlZGUyMTRjN2RhNDM1NWIwMzFjYWUyNTA0NzlmMDMpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfY2MyNDk5MGIxNGYzNDEwMTk5MWY0YWMzNGNhNGJjZWIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NTQyNTk5LC03OS4zNjA2MzU5XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzJlMjFjZjQ0OTk0ZjQyOTViNTMwMDQwNjRkOGViMTIyID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzQ0Y2I1Mjk5OGZjYzQyNzZiZDcyMjY3ZjBkNzg4M2I5ID0gJCgnPGRpdiBpZD0iaHRtbF80NGNiNTI5OThmY2M0Mjc2YmQ3MjI2N2YwZDc4ODNiOSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+SGFyYm91cmZyb250LFJlZ2VudCBQYXJrLS1Eb3dudG93biBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF8yZTIxY2Y0NDk5NGY0Mjk1YjUzMDA0MDY0ZDhlYjEyMi5zZXRDb250ZW50KGh0bWxfNDRjYjUyOTk4ZmNjNDI3NmJkNzIyNjdmMGQ3ODgzYjkpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfY2MyNDk5MGIxNGYzNDEwMTk5MWY0YWMzNGNhNGJjZWIuYmluZFBvcHVwKHBvcHVwXzJlMjFjZjQ0OTk0ZjQyOTViNTMwMDQwNjRkOGViMTIyKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzRhZWU4YzFlOTAwNDRmYmVhM2MyMzg2YTg3NGU5ZGNiID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjU3MTYxOCwtNzkuMzc4OTM3MDk5OTk5OTldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfZWUzZWUyODJlNTEzNGYzYTgwZTMwOTUyMGVlYjU2NjMgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfMWZlM2FmYjJjZWViNDZlYTk4N2ZhZTNmZTEyMGNkNWMgPSAkKCc8ZGl2IGlkPSJodG1sXzFmZTNhZmIyY2VlYjQ2ZWE5ODdmYWUzZmUxMjBjZDVjIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5SeWVyc29uLEdhcmRlbiBEaXN0cmljdC0tRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfZWUzZWUyODJlNTEzNGYzYTgwZTMwOTUyMGVlYjU2NjMuc2V0Q29udGVudChodG1sXzFmZTNhZmIyY2VlYjQ2ZWE5ODdmYWUzZmUxMjBjZDVjKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzRhZWU4YzFlOTAwNDRmYmVhM2MyMzg2YTg3NGU5ZGNiLmJpbmRQb3B1cChwb3B1cF9lZTNlZTI4MmU1MTM0ZjNhODBlMzA5NTIwZWViNTY2Myk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl84ZTFhOWJkNTM1YTM0NGY0YWY0YWJiNjFlNDRlY2Q0MiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY1MTQ5MzksLTc5LjM3NTQxNzldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfMjAxZDU0NWRkZjgxNDRkYWJlNDZhZTdmODIzMzlkNTYgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfN2IyNjhmMjRiNzkwNDYzM2E1MjE1ZGMyZTFlMzNlMWQgPSAkKCc8ZGl2IGlkPSJodG1sXzdiMjY4ZjI0Yjc5MDQ2MzNhNTIxNWRjMmUxZTMzZTFkIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5TdC4gSmFtZXMgVG93bi0tRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfMjAxZDU0NWRkZjgxNDRkYWJlNDZhZTdmODIzMzlkNTYuc2V0Q29udGVudChodG1sXzdiMjY4ZjI0Yjc5MDQ2MzNhNTIxNWRjMmUxZTMzZTFkKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzhlMWE5YmQ1MzVhMzQ0ZjRhZjRhYmI2MWU0NGVjZDQyLmJpbmRQb3B1cChwb3B1cF8yMDFkNTQ1ZGRmODE0NGRhYmU0NmFlN2Y4MjMzOWQ1Nik7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8xOTllNGNlMTRjMzE0MTM4YTM2ODQ3MWM0NTI2MGRlMiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY0NDc3MDc5OTk5OTk5NiwtNzkuMzczMzA2NF0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF9jNDVmZTYzMWFmODQ0ZTE3OGFjY2FhNWRiODVjYzQxMCA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF82YmExOTI1MjNiMmI0ZDc2OGZiODAzNzZlNzRkNGQ1MyA9ICQoJzxkaXYgaWQ9Imh0bWxfNmJhMTkyNTIzYjJiNGQ3NjhmYjgwMzc2ZTc0ZDRkNTMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJlcmN6eSBQYXJrLS1Eb3dudG93biBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF9jNDVmZTYzMWFmODQ0ZTE3OGFjY2FhNWRiODVjYzQxMC5zZXRDb250ZW50KGh0bWxfNmJhMTkyNTIzYjJiNGQ3NjhmYjgwMzc2ZTc0ZDRkNTMpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfMTk5ZTRjZTE0YzMxNDEzOGEzNjg0NzFjNDUyNjBkZTIuYmluZFBvcHVwKHBvcHVwX2M0NWZlNjMxYWY4NDRlMTc4YWNjYWE1ZGI4NWNjNDEwKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2UyNmY2MzdiMjM4ZDQ1M2Q5MmQ0MGFhMmRjNmYyNDFhID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjU3OTUyNCwtNzkuMzg3MzgyNl0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF80NGRhNDcyYTQ0MDY0ZDdlODZjNDQ5ZDU4MzM4NmQ4YiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF82OTlhYWZlOWNmZjc0ZWE5YmE3YjE2NjYxMDEzZTFiZCA9ICQoJzxkaXYgaWQ9Imh0bWxfNjk5YWFmZTljZmY3NGVhOWJhN2IxNjY2MTAxM2UxYmQiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkNlbnRyYWwgQmF5IFN0cmVldC0tRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfNDRkYTQ3MmE0NDA2NGQ3ZTg2YzQ0OWQ1ODMzODZkOGIuc2V0Q29udGVudChodG1sXzY5OWFhZmU5Y2ZmNzRlYTliYTdiMTY2NjEwMTNlMWJkKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyX2UyNmY2MzdiMjM4ZDQ1M2Q5MmQ0MGFhMmRjNmYyNDFhLmJpbmRQb3B1cChwb3B1cF80NGRhNDcyYTQ0MDY0ZDdlODZjNDQ5ZDU4MzM4NmQ4Yik7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl82NmRhZTFkYTI2OTA0YTMzOWExOGNlMjkzZjdmNDQ0MyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY1MDU3MTIwMDAwMDAxLC03OS4zODQ1Njc1XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzQwNjI1ZDE5ODJiODRhM2ZiMDExODNmMDFhZTAxNTMwID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sX2QwOWUwMmI1YTFkZDQ5Y2ZiYjk0ZGQ0Y2FmZTMzMmNlID0gJCgnPGRpdiBpZD0iaHRtbF9kMDllMDJiNWExZGQ0OWNmYmI5NGRkNGNhZmUzMzJjZSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QWRlbGFpZGUsS2luZyxSaWNobW9uZC0tRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfNDA2MjVkMTk4MmI4NGEzZmIwMTE4M2YwMWFlMDE1MzAuc2V0Q29udGVudChodG1sX2QwOWUwMmI1YTFkZDQ5Y2ZiYjk0ZGQ0Y2FmZTMzMmNlKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzY2ZGFlMWRhMjY5MDRhMzM5YTE4Y2UyOTNmN2Y0NDQzLmJpbmRQb3B1cChwb3B1cF80MDYyNWQxOTgyYjg0YTNmYjAxMTgzZjAxYWUwMTUzMCk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8yOGMzMzU0NTk5ZDM0ZDY2OWFkZTk0ZWVlZDQzOGIzYiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY0MDgxNTcsLTc5LjM4MTc1MjI5OTk5OTk5XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzI5NjhkMDhmMTJiMjQ4NzJhMTE0MTg4N2MxYjQ2YzA5ID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzc0OWEwZWE5NWM5MjQxNzRhOGRiMWZlMTJiMjUyYjVhID0gJCgnPGRpdiBpZD0iaHRtbF83NDlhMGVhOTVjOTI0MTc0YThkYjFmZTEyYjI1MmI1YSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+SGFyYm91cmZyb250IEVhc3QsVG9yb250byBJc2xhbmRzLFVuaW9uIFN0YXRpb24tLURvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzI5NjhkMDhmMTJiMjQ4NzJhMTE0MTg4N2MxYjQ2YzA5LnNldENvbnRlbnQoaHRtbF83NDlhMGVhOTVjOTI0MTc0YThkYjFmZTEyYjI1MmI1YSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl8yOGMzMzU0NTk5ZDM0ZDY2OWFkZTk0ZWVlZDQzOGIzYi5iaW5kUG9wdXAocG9wdXBfMjk2OGQwOGYxMmIyNDg3MmExMTQxODg3YzFiNDZjMDkpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNmVjNzNkNTE0YjZlNDlmNzlkZTRkMGYwYmIxNWY4YTYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NDcxNzY4LC03OS4zODE1NzY0MDAwMDAwMV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8yY2JhNjE4MDlmODg0ZGRmYTNiNGI3MDY0MTJlNzFhZiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9lNjA2OTEwOGZlNjI0MTRhOWQ5YTk3OWZiNDcxODY0ZCA9ICQoJzxkaXYgaWQ9Imh0bWxfZTYwNjkxMDhmZTYyNDE0YTlkOWE5NzlmYjQ3MTg2NGQiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkRlc2lnbiBFeGNoYW5nZSxUb3JvbnRvIERvbWluaW9uIENlbnRyZS0tRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfMmNiYTYxODA5Zjg4NGRkZmEzYjRiNzA2NDEyZTcxYWYuc2V0Q29udGVudChodG1sX2U2MDY5MTA4ZmU2MjQxNGE5ZDlhOTc5ZmI0NzE4NjRkKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzZlYzczZDUxNGI2ZTQ5Zjc5ZGU0ZDBmMGJiMTVmOGE2LmJpbmRQb3B1cChwb3B1cF8yY2JhNjE4MDlmODg0ZGRmYTNiNGI3MDY0MTJlNzFhZik7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8wODE5YTE4YWZmMmQ0OTUwYmMzYWNmNzU4MzA4YTU4MyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY0ODE5ODUsLTc5LjM3OTgxNjkwMDAwMDAxXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzk0OTgzM2FjOTY3YTQzYTY5YjA1NDRmN2FiNThjNzlhID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzUxMGU4NGZhMzlkYjRjNTRhNWRmNjkyYzBhZDMyZjczID0gJCgnPGRpdiBpZD0iaHRtbF81MTBlODRmYTM5ZGI0YzU0YTVkZjY5MmMwYWQzMmY3MyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Q29tbWVyY2UgQ291cnQsVmljdG9yaWEgSG90ZWwtLURvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzk0OTgzM2FjOTY3YTQzYTY5YjA1NDRmN2FiNThjNzlhLnNldENvbnRlbnQoaHRtbF81MTBlODRmYTM5ZGI0YzU0YTVkZjY5MmMwYWQzMmY3Myk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl8wODE5YTE4YWZmMmQ0OTUwYmMzYWNmNzU4MzA4YTU4My5iaW5kUG9wdXAocG9wdXBfOTQ5ODMzYWM5NjdhNDNhNjliMDU0NGY3YWI1OGM3OWEpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfOWU5OWQzYTMzYjc4NDA1Yzk3ZGVhYmJiNTczOGNkZTIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My43MTE2OTQ4LC03OS40MTY5MzU1OTk5OTk5OV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8yM2FkMjU5NDRiZjU0YjZhYTU2OTE0NjNiODZiMGNiYyA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF85ZGU2MjU5ZjY5NTg0ZTIwOTIzZmJhZTQ2OWEyMjViNiA9ICQoJzxkaXYgaWQ9Imh0bWxfOWRlNjI1OWY2OTU4NGUyMDkyM2ZiYWU0NjlhMjI1YjYiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlJvc2VsYXduLS1DZW50cmFsIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzIzYWQyNTk0NGJmNTRiNmFhNTY5MTQ2M2I4NmIwY2JjLnNldENvbnRlbnQoaHRtbF85ZGU2MjU5ZjY5NTg0ZTIwOTIzZmJhZTQ2OWEyMjViNik7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl85ZTk5ZDNhMzNiNzg0MDVjOTdkZWFiYmI1NzM4Y2RlMi5iaW5kUG9wdXAocG9wdXBfMjNhZDI1OTQ0YmY1NGI2YWE1NjkxNDYzYjg2YjBjYmMpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZTA5YjdiMTVkYzcwNGM5MTllZmRmMWE1M2ZjMTg3ZmUgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42OTY5NDc2LC03OS40MTEzMDcyMDAwMDAwMV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF85YmJiODEzMDU4ODE0MzQ2YWU2ODI2MjdlMGRmMWFiNCA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9iY2IwNTkxOWZhZjM0MDVkODM2MzJmMGYxMGZiMzQ4OCA9ICQoJzxkaXYgaWQ9Imh0bWxfYmNiMDU5MTlmYWYzNDA1ZDgzNjMyZjBmMTBmYjM0ODgiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkZvcmVzdCBIaWxsIE5vcnRoLEZvcmVzdCBIaWxsIFdlc3QtLUNlbnRyYWwgVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfOWJiYjgxMzA1ODgxNDM0NmFlNjgyNjI3ZTBkZjFhYjQuc2V0Q29udGVudChodG1sX2JjYjA1OTE5ZmFmMzQwNWQ4MzYzMmYwZjEwZmIzNDg4KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyX2UwOWI3YjE1ZGM3MDRjOTE5ZWZkZjFhNTNmYzE4N2ZlLmJpbmRQb3B1cChwb3B1cF85YmJiODEzMDU4ODE0MzQ2YWU2ODI2MjdlMGRmMWFiNCk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9jZTY0ZTc3ZmNlZDY0MjRjOThiYmViZmVkYzNjZDE2OSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY3MjcwOTcsLTc5LjQwNTY3ODQwMDAwMDAxXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2U3NGYwYzU2MTMwMzRhY2Y5MDNmMTc3MmVmYzk0ZjM5ID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzY5NmEzYTY0M2FlZTQ0MzQ4MjExYmRlMjU2MDgyMDc5ID0gJCgnPGRpdiBpZD0iaHRtbF82OTZhM2E2NDNhZWU0NDM0ODIxMWJkZTI1NjA4MjA3OSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+VGhlIEFubmV4LE5vcnRoIE1pZHRvd24sWW9ya3ZpbGxlLS1DZW50cmFsIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2U3NGYwYzU2MTMwMzRhY2Y5MDNmMTc3MmVmYzk0ZjM5LnNldENvbnRlbnQoaHRtbF82OTZhM2E2NDNhZWU0NDM0ODIxMWJkZTI1NjA4MjA3OSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9jZTY0ZTc3ZmNlZDY0MjRjOThiYmViZmVkYzNjZDE2OS5iaW5kUG9wdXAocG9wdXBfZTc0ZjBjNTYxMzAzNGFjZjkwM2YxNzcyZWZjOTRmMzkpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMzBjYzFhMGVmMzc4NDNiNTk0YWU2OWY5ZDQzNWMxOWQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NjI2OTU2LC03OS40MDAwNDkzXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzM4NjIwNDM0ZGJkYzRiOGJiZThiOWM1NDFmNmMxNzAyID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sX2VkNmU0MTY0Mjk5MDQ3ZDJiMDU0NGE2MzBlZDU3M2RmID0gJCgnPGRpdiBpZD0iaHRtbF9lZDZlNDE2NDI5OTA0N2QyYjA1NDRhNjMwZWQ1NzNkZiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+SGFyYm9yZCxVbml2ZXJzaXR5IG9mIFRvcm9udG8tLURvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzM4NjIwNDM0ZGJkYzRiOGJiZThiOWM1NDFmNmMxNzAyLnNldENvbnRlbnQoaHRtbF9lZDZlNDE2NDI5OTA0N2QyYjA1NDRhNjMwZWQ1NzNkZik7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl8zMGNjMWEwZWYzNzg0M2I1OTRhZTY5ZjlkNDM1YzE5ZC5iaW5kUG9wdXAocG9wdXBfMzg2MjA0MzRkYmRjNGI4YmJlOGI5YzU0MWY2YzE3MDIpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNTFmZjYwZTNkM2M3NGRlNGJlMjc0ZDBlNjNhYmQ3MjkgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NTMyMDU3LC03OS40MDAwNDkzXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzQ5Y2QzMmJkMmFhYTRlOTk4MzdhNDEwYWRlNzdkYzAwID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzU3ZTIzZjNlNDJiYzRjZjc5ZGJkOTZkMzAxOTJiNmI0ID0gJCgnPGRpdiBpZD0iaHRtbF81N2UyM2YzZTQyYmM0Y2Y3OWRiZDk2ZDMwMTkyYjZiNCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Q2hpbmF0b3duLEdyYW5nZSBQYXJrLEtlbnNpbmd0b24gTWFya2V0LS1Eb3dudG93biBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF80OWNkMzJiZDJhYWE0ZTk5ODM3YTQxMGFkZTc3ZGMwMC5zZXRDb250ZW50KGh0bWxfNTdlMjNmM2U0MmJjNGNmNzlkYmQ5NmQzMDE5MmI2YjQpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfNTFmZjYwZTNkM2M3NGRlNGJlMjc0ZDBlNjNhYmQ3MjkuYmluZFBvcHVwKHBvcHVwXzQ5Y2QzMmJkMmFhYTRlOTk4MzdhNDEwYWRlNzdkYzAwKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzY3Njg1OTc3YTZiODRmZDJhOWY4MWZhMGZlOTQ4ZGYwID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjI4OTQ2NywtNzkuMzk0NDE5OV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF9hMDYwODQ3MWIzNWY0ZGFkYmM3NWRjMjEwZTc2NTA3OCA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9mZjczMWQxZDVmMDg0OTlmOGFkOTgwMmVjYjk2OGQzOCA9ICQoJzxkaXYgaWQ9Imh0bWxfZmY3MzFkMWQ1ZjA4NDk5ZjhhZDk4MDJlY2I5NjhkMzgiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkNOIFRvd2VyLEJhdGh1cnN0IFF1YXksSXNsYW5kIGFpcnBvcnQsSGFyYm91cmZyb250IFdlc3QsS2luZyBhbmQgU3BhZGluYSxSYWlsd2F5IExhbmRzLFNvdXRoIE5pYWdhcmEtLURvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2EwNjA4NDcxYjM1ZjRkYWRiYzc1ZGMyMTBlNzY1MDc4LnNldENvbnRlbnQoaHRtbF9mZjczMWQxZDVmMDg0OTlmOGFkOTgwMmVjYjk2OGQzOCk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl82NzY4NTk3N2E2Yjg0ZmQyYTlmODFmYTBmZTk0OGRmMC5iaW5kUG9wdXAocG9wdXBfYTA2MDg0NzFiMzVmNGRhZGJjNzVkYzIxMGU3NjUwNzgpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYzhiNWFhZDdiMWFiNDdmYzllMzNmYzBmOTA1YWMwYzggPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NDY0MzUyLC03OS4zNzQ4NDU5OTk5OTk5OV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF9jOTIwZTJhYTgwZTQ0MDAyYWVkNTFmYWMzZjIzMTQzYiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF8yNDRmYzUwMjk3Njk0YmM0ODQxOTk5ZTNhNjJhMzYxZCA9ICQoJzxkaXYgaWQ9Imh0bWxfMjQ0ZmM1MDI5NzY5NGJjNDg0MTk5OWUzYTYyYTM2MWQiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPlN0biBBIFBPIEJveGVzIDI1IFRoZSBFc3BsYW5hZGUtLURvd250b3duIFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2M5MjBlMmFhODBlNDQwMDJhZWQ1MWZhYzNmMjMxNDNiLnNldENvbnRlbnQoaHRtbF8yNDRmYzUwMjk3Njk0YmM0ODQxOTk5ZTNhNjJhMzYxZCk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9jOGI1YWFkN2IxYWI0N2ZjOWUzM2ZjMGY5MDVhYzBjOC5iaW5kUG9wdXAocG9wdXBfYzkyMGUyYWE4MGU0NDAwMmFlZDUxZmFjM2YyMzE0M2IpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZDE1ZDZiYjk5OTkzNDE0OGJjMDAxNmNmZTYzYWQ1YmUgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NDg0MjkyLC03OS4zODIyODAyXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2Y3ZDMwYjA3YTRhMzQ0Y2ZhZmRiMmIzYThiYThiYzViID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sX2YyYzQ0YjM1ZTcxODQwNTJiYjk1OTk3NmQyNTk0NmE3ID0gJCgnPGRpdiBpZD0iaHRtbF9mMmM0NGIzNWU3MTg0MDUyYmI5NTk5NzZkMjU5NDZhNyIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Rmlyc3QgQ2FuYWRpYW4gUGxhY2UsVW5kZXJncm91bmQgY2l0eS0tRG93bnRvd24gVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfZjdkMzBiMDdhNGEzNDRjZmFmZGIyYjNhOGJhOGJjNWIuc2V0Q29udGVudChodG1sX2YyYzQ0YjM1ZTcxODQwNTJiYjk1OTk3NmQyNTk0NmE3KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyX2QxNWQ2YmI5OTk5MzQxNDhiYzAwMTZjZmU2M2FkNWJlLmJpbmRQb3B1cChwb3B1cF9mN2QzMGIwN2E0YTM0NGNmYWZkYjJiM2E4YmE4YmM1Yik7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl84YWJkOGU0ZmE1YTg0NThkOTE5YTE4NTk4OTJkNzljYiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY2OTU0MiwtNzkuNDIyNTYzN10sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8xOTkwY2FmM2Q0MmI0NjM5YjdhOTYyZTU3NjZhOWIzOSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9lYzY3YzU0YTRkMmQ0MzEwYTk2MTI4MjI2Mzg1ZTdlYSA9ICQoJzxkaXYgaWQ9Imh0bWxfZWM2N2M1NGE0ZDJkNDMxMGE5NjEyODIyNjM4NWU3ZWEiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkNocmlzdGllLS1Eb3dudG93biBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF8xOTkwY2FmM2Q0MmI0NjM5YjdhOTYyZTU3NjZhOWIzOS5zZXRDb250ZW50KGh0bWxfZWM2N2M1NGE0ZDJkNDMxMGE5NjEyODIyNjM4NWU3ZWEpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfOGFiZDhlNGZhNWE4NDU4ZDkxOWExODU5ODkyZDc5Y2IuYmluZFBvcHVwKHBvcHVwXzE5OTBjYWYzZDQyYjQ2MzliN2E5NjJlNTc2NmE5YjM5KTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzA5M2EwZGQzYjMzMDQ0NjdiMDM2NGM4OGViYmQzNmRjID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjY5MDA1MTAwMDAwMDEsLTc5LjQ0MjI1OTNdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfNjg5MjdiNDdkNTk3NDA0ZDk1ZWUyYzQ0ODE1ZjI1MjUgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfNTVjODYwODQ1NTc2NDBmMGIyMDY2NzdiOTBmYzU4OWIgPSAkKCc8ZGl2IGlkPSJodG1sXzU1Yzg2MDg0NTU3NjQwZjBiMjA2Njc3YjkwZmM1ODliIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Eb3ZlcmNvdXJ0IFZpbGxhZ2UsRHVmZmVyaW4tLVdlc3QgVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfNjg5MjdiNDdkNTk3NDA0ZDk1ZWUyYzQ0ODE1ZjI1MjUuc2V0Q29udGVudChodG1sXzU1Yzg2MDg0NTU3NjQwZjBiMjA2Njc3YjkwZmM1ODliKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzA5M2EwZGQzYjMzMDQ0NjdiMDM2NGM4OGViYmQzNmRjLmJpbmRQb3B1cChwb3B1cF82ODkyN2I0N2Q1OTc0MDRkOTVlZTJjNDQ4MTVmMjUyNSk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9jMmFjOTk4NTM1MWM0NDAwOGRlMjRjMzc0YmM3MmZhOSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY0NzkyNjcwMDAwMDAwNiwtNzkuNDE5NzQ5N10sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8wYTIzMmU5MDQzYjQ0OGI5OTQzNzBiODBmNWQ4ODc2MyA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF84MDExNTYwNzdlYmY0ZTRmODNlMzU2ZDIyOGMyYWZhZiA9ICQoJzxkaXYgaWQ9Imh0bWxfODAxMTU2MDc3ZWJmNGU0ZjgzZTM1NmQyMjhjMmFmYWYiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkxpdHRsZSBQb3J0dWdhbCxUcmluaXR5LS1XZXN0IFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzBhMjMyZTkwNDNiNDQ4Yjk5NDM3MGI4MGY1ZDg4NzYzLnNldENvbnRlbnQoaHRtbF84MDExNTYwNzdlYmY0ZTRmODNlMzU2ZDIyOGMyYWZhZik7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9jMmFjOTk4NTM1MWM0NDAwOGRlMjRjMzc0YmM3MmZhOS5iaW5kUG9wdXAocG9wdXBfMGEyMzJlOTA0M2I0NDhiOTk0MzcwYjgwZjVkODg3NjMpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfODBlYzYwMDk1ZjVjNDU4ZTg1Nzc2MGQ2N2RmZGFjOTQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42MzY4NDcyLC03OS40MjgxOTE0MDAwMDAwMl0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICJibHVlIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzMxODZjYyIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9mOTg2OTYwNTAzMWM0YjliOTVmOTY3YTlhOTkwNmIxZSk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF81OTM5NTQyNGFmZDk0OWI5YWI3MWQ4ODNlYTlkZTA5ZiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF82ZTdkMDJkYzQxNTA0NGYzYmQ5NDU2Y2Y4OGIzOTA2MSA9ICQoJzxkaXYgaWQ9Imh0bWxfNmU3ZDAyZGM0MTUwNDRmM2JkOTQ1NmNmODhiMzkwNjEiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJyb2NrdG9uLEV4aGliaXRpb24gUGxhY2UsUGFya2RhbGUgVmlsbGFnZS0tV2VzdCBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF81OTM5NTQyNGFmZDk0OWI5YWI3MWQ4ODNlYTlkZTA5Zi5zZXRDb250ZW50KGh0bWxfNmU3ZDAyZGM0MTUwNDRmM2JkOTQ1NmNmODhiMzkwNjEpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfODBlYzYwMDk1ZjVjNDU4ZTg1Nzc2MGQ2N2RmZGFjOTQuYmluZFBvcHVwKHBvcHVwXzU5Mzk1NDI0YWZkOTQ5YjlhYjcxZDg4M2VhOWRlMDlmKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2RiOTUzNDI3M2UwYzQwZGJiMWY0NGFlYTI2ODYzMDU4ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjYxNjA4MywtNzkuNDY0NzYzMjk5OTk5OTldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfZTdjMmRlMzYwZjdjNDg3OGI5YzFlZjBiOGNjYjdjOWYgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfNjBmYmUzOWQyN2ViNDFjODliNmQxNGMyMWQ3ODI0N2IgPSAkKCc8ZGl2IGlkPSJodG1sXzYwZmJlMzlkMjdlYjQxYzg5YjZkMTRjMjFkNzgyNDdiIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5IaWdoIFBhcmssVGhlIEp1bmN0aW9uIFNvdXRoLS1XZXN0IFRvcm9udG88L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2U3YzJkZTM2MGY3YzQ4NzhiOWMxZWYwYjhjY2I3YzlmLnNldENvbnRlbnQoaHRtbF82MGZiZTM5ZDI3ZWI0MWM4OWI2ZDE0YzIxZDc4MjQ3Yik7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9kYjk1MzQyNzNlMGM0MGRiYjFmNDRhZWEyNjg2MzA1OC5iaW5kUG9wdXAocG9wdXBfZTdjMmRlMzYwZjdjNDg3OGI5YzFlZjBiOGNjYjdjOWYpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNDhjNmQ2NjgzNWNiNDZiMGJhYzkyNjZiYzFiMjg2NGIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NDg5NTk3LC03OS40NTYzMjVdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfODEzMDIyYmI3NjdkNDg0ZmI3ODQ1MDk1Zjc2NjFkNTUgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfZGU0M2Q5OTVmMGM4NGFlMzhlZWMwNDk4ZDgyZjJmMGIgPSAkKCc8ZGl2IGlkPSJodG1sX2RlNDNkOTk1ZjBjODRhZTM4ZWVjMDQ5OGQ4MmYyZjBiIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5QYXJrZGFsZSxSb25jZXN2YWxsZXMtLVdlc3QgVG9yb250bzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfODEzMDIyYmI3NjdkNDg0ZmI3ODQ1MDk1Zjc2NjFkNTUuc2V0Q29udGVudChodG1sX2RlNDNkOTk1ZjBjODRhZTM4ZWVjMDQ5OGQ4MmYyZjBiKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzQ4YzZkNjY4MzVjYjQ2YjBiYWM5MjY2YmMxYjI4NjRiLmJpbmRQb3B1cChwb3B1cF84MTMwMjJiYjc2N2Q0ODRmYjc4NDUwOTVmNzY2MWQ1NSk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9iNjYxM2U1ZWJkMTk0YWEwODZkNGJhMjViNjE4NjllZSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY1MTU3MDYsLTc5LjQ4NDQ0OTldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiYmx1ZSIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMzMTg2Y2MiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZjk4Njk2MDUwMzFjNGI5Yjk1Zjk2N2E5YTk5MDZiMWUpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfOGEwMDVhZTEyYTUzNDA2ODg4ZGQzYWRiYTY4N2Y3NDkgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfNjY5NmJjMzJhMTcwNDRlMTkyODkzMTUxNDMxOTZkNmEgPSAkKCc8ZGl2IGlkPSJodG1sXzY2OTZiYzMyYTE3MDQ0ZTE5Mjg5MzE1MTQzMTk2ZDZhIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5SdW5ueW1lZGUsU3dhbnNlYS0tV2VzdCBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF84YTAwNWFlMTJhNTM0MDY4ODhkZDNhZGJhNjg3Zjc0OS5zZXRDb250ZW50KGh0bWxfNjY5NmJjMzJhMTcwNDRlMTkyODkzMTUxNDMxOTZkNmEpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfYjY2MTNlNWViZDE5NGFhMDg2ZDRiYTI1YjYxODY5ZWUuYmluZFBvcHVwKHBvcHVwXzhhMDA1YWUxMmE1MzQwNjg4OGRkM2FkYmE2ODdmNzQ5KTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzU2ZWM5OTEzNzdjYzRhZDY5OTU3MGI3YWM3YmUyYjIwID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjYyNzQzOSwtNzkuMzIxNTU4XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogImJsdWUiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMzE4NmNjIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2Y5ODY5NjA1MDMxYzRiOWI5NWY5NjdhOWE5OTA2YjFlKTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzIyNmJmNGQxZDMyNTQwZTU4ZTA3ZDlmMWQ2M2Y4NmZkID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzBiMzk1MWMxZGUxYzRhYTA5YTk0YzE3YWJhNmMyYmE0ID0gJCgnPGRpdiBpZD0iaHRtbF8wYjM5NTFjMWRlMWM0YWEwOWE5NGMxN2FiYTZjMmJhNCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QnVzaW5lc3MgUmVwbHkgTWFpbCBQcm9jZXNzaW5nIENlbnRyZSA5NjkgRWFzdGVybi0tRWFzdCBUb3JvbnRvPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF8yMjZiZjRkMWQzMjU0MGU1OGUwN2Q5ZjFkNjNmODZmZC5zZXRDb250ZW50KGh0bWxfMGIzOTUxYzFkZTFjNGFhMDlhOTRjMTdhYmE2YzJiYTQpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfNTZlYzk5MTM3N2NjNGFkNjk5NTcwYjdhYzdiZTJiMjAuYmluZFBvcHVwKHBvcHVwXzIyNmJmNGQxZDMyNTQwZTU4ZTA3ZDlmMWQ2M2Y4NmZkKTsKCiAgICAgICAgICAgIAogICAgICAgIAo8L3NjcmlwdD4=" style="position:absolute;width:100%;height:100%;left:0;top:0;border:none !important;" allowfullscreen webkitallowfullscreen mozallowfullscreen></iframe></div></div>




```python
CLIENT_ID = 'QPG4LS2XMXGC2KXOGFMHKXCTIACEGEYEKGT0BS3E0DAOXGDG' # your Foursquare ID
CLIENT_SECRET = 'WVWNOOZAJ11DOKZAKJWKPPD1LRRESFJFZ4BABL5RBDD50UT1' # your Foursquare Secret
VERSION = '20180605' # Foursquare API version

print('Your credentails:')
print('CLIENT_ID: ' + CLIENT_ID)
print('CLIENT_SECRET:' + CLIENT_SECRET)
```

    Your credentails:
    CLIENT_ID: QPG4LS2XMXGC2KXOGFMHKXCTIACEGEYEKGT0BS3E0DAOXGDG
    CLIENT_SECRET:WVWNOOZAJ11DOKZAKJWKPPD1LRRESFJFZ4BABL5RBDD50UT1
    


```python
def getNearbyVenues(names, latitudes, longitudes, radius=500):
    
    venues_list=[]
    LIMIT = 100
    for name, lat, lng in zip(names, latitudes, longitudes):
        print(name)
            
        # create the API request URL
        url = 'https://api.foursquare.com/v2/venues/explore?&client_id={}&client_secret={}&v={}&ll={},{}&radius={}&limit={}'.format(
            CLIENT_ID, 
            CLIENT_SECRET, 
            VERSION, 
            lat, 
            lng, 
            radius, 
            LIMIT)
            
        # make the GET request
        results = requests.get(url).json()["response"]['groups'][0]['items']
        
        # return only relevant information for each nearby venue
        venues_list.append([(
            name, 
            lat, 
            lng, 
            v['venue']['name'], 
            v['venue']['location']['lat'], 
            v['venue']['location']['lng'],  
            v['venue']['categories'][0]['name']) for v in results])

    nearby_venues = pd.DataFrame([item for venue_list in venues_list for item in venue_list])
    nearby_venues.columns = ['Neighborhood', 
                  'Neighborhood Latitude', 
                  'Neighborhood Longitude', 
                  'Venue', 
                  'Venue Latitude', 
                  'Venue Longitude', 
                  'Venue Category']
    
    return(nearby_venues)
```


```python
map_result=getNearbyVenues(names=df_map['Neighborhood'],
                           latitudes=df_map['Latitude'],
                          longitudes=df_map['Longitude'])
```

    The Beaches
    The Danforth West,Riverdale
    The Beaches West,India Bazaar
    Studio District
    Lawrence Park
    Davisville North
    North Toronto West
    Davisville
    Moore Park,Summerhill East
    Deer Park,Forest Hill SE,Rathnelly,South Hill,Summerhill West
    Rosedale
    Cabbagetown,St. James Town
    Church and Wellesley
    Harbourfront,Regent Park
    Ryerson,Garden District
    St. James Town
    Berczy Park
    Central Bay Street
    Adelaide,King,Richmond
    Harbourfront East,Toronto Islands,Union Station
    Design Exchange,Toronto Dominion Centre
    Commerce Court,Victoria Hotel
    Roselawn
    Forest Hill North,Forest Hill West
    The Annex,North Midtown,Yorkville
    Harbord,University of Toronto
    Chinatown,Grange Park,Kensington Market
    CN Tower,Bathurst Quay,Island airport,Harbourfront West,King and Spadina,Railway Lands,South Niagara
    Stn A PO Boxes 25 The Esplanade
    First Canadian Place,Underground city
    Christie
    Dovercourt Village,Dufferin
    Little Portugal,Trinity
    Brockton,Exhibition Place,Parkdale Village
    High Park,The Junction South
    Parkdale,Roncesvalles
    Runnymede,Swansea
    Business Reply Mail Processing Centre 969 Eastern
    


```python
map_result
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Neighborhood</th>
      <th>Neighborhood Latitude</th>
      <th>Neighborhood Longitude</th>
      <th>Venue</th>
      <th>Venue Latitude</th>
      <th>Venue Longitude</th>
      <th>Venue Category</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>The Beaches</td>
      <td>43.676357</td>
      <td>-79.293031</td>
      <td>Glen Manor Ravine</td>
      <td>43.676821</td>
      <td>-79.293942</td>
      <td>Trail</td>
    </tr>
    <tr>
      <th>1</th>
      <td>The Beaches</td>
      <td>43.676357</td>
      <td>-79.293031</td>
      <td>The Big Carrot Natural Food Market</td>
      <td>43.678879</td>
      <td>-79.297734</td>
      <td>Health Food Store</td>
    </tr>
    <tr>
      <th>2</th>
      <td>The Beaches</td>
      <td>43.676357</td>
      <td>-79.293031</td>
      <td>Grover Pub and Grub</td>
      <td>43.679181</td>
      <td>-79.297215</td>
      <td>Pub</td>
    </tr>
    <tr>
      <th>3</th>
      <td>The Beaches</td>
      <td>43.676357</td>
      <td>-79.293031</td>
      <td>Glen Stewart Ravine</td>
      <td>43.676300</td>
      <td>-79.294784</td>
      <td>Other Great Outdoors</td>
    </tr>
    <tr>
      <th>4</th>
      <td>The Beaches</td>
      <td>43.676357</td>
      <td>-79.293031</td>
      <td>Upper Beaches</td>
      <td>43.680563</td>
      <td>-79.292869</td>
      <td>Neighborhood</td>
    </tr>
    <tr>
      <th>5</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Pantheon</td>
      <td>43.677621</td>
      <td>-79.351434</td>
      <td>Greek Restaurant</td>
    </tr>
    <tr>
      <th>6</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>MenEssentials</td>
      <td>43.677820</td>
      <td>-79.351265</td>
      <td>Cosmetics Shop</td>
    </tr>
    <tr>
      <th>7</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Dolce Gelato</td>
      <td>43.677773</td>
      <td>-79.351187</td>
      <td>Ice Cream Shop</td>
    </tr>
    <tr>
      <th>8</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Cafe Fiorentina</td>
      <td>43.677743</td>
      <td>-79.350115</td>
      <td>Italian Restaurant</td>
    </tr>
    <tr>
      <th>9</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>La Diperie</td>
      <td>43.677530</td>
      <td>-79.352295</td>
      <td>Ice Cream Shop</td>
    </tr>
    <tr>
      <th>10</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Mezes</td>
      <td>43.677962</td>
      <td>-79.350196</td>
      <td>Greek Restaurant</td>
    </tr>
    <tr>
      <th>11</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Messini Authentic Gyros</td>
      <td>43.677827</td>
      <td>-79.350569</td>
      <td>Greek Restaurant</td>
    </tr>
    <tr>
      <th>12</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Louis Cifer Brew Works</td>
      <td>43.677663</td>
      <td>-79.351313</td>
      <td>Brewery</td>
    </tr>
    <tr>
      <th>13</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>The Auld Spot Pub</td>
      <td>43.677335</td>
      <td>-79.353130</td>
      <td>Pub</td>
    </tr>
    <tr>
      <th>14</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Moksha Yoga Danforth</td>
      <td>43.677622</td>
      <td>-79.352116</td>
      <td>Yoga Studio</td>
    </tr>
    <tr>
      <th>15</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>The Big Carrot Organic Juice Bar</td>
      <td>43.677438</td>
      <td>-79.352683</td>
      <td>Juice Bar</td>
    </tr>
    <tr>
      <th>16</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Valley Farm Produce</td>
      <td>43.677999</td>
      <td>-79.349969</td>
      <td>Fruit &amp; Vegetable Store</td>
    </tr>
    <tr>
      <th>17</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Alexandros</td>
      <td>43.678304</td>
      <td>-79.349486</td>
      <td>Greek Restaurant</td>
    </tr>
    <tr>
      <th>18</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Pizzeria Libretto</td>
      <td>43.678489</td>
      <td>-79.347576</td>
      <td>Pizza Place</td>
    </tr>
    <tr>
      <th>19</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>7 Numbers</td>
      <td>43.677062</td>
      <td>-79.353934</td>
      <td>Italian Restaurant</td>
    </tr>
    <tr>
      <th>20</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Caffé Demetre</td>
      <td>43.677683</td>
      <td>-79.351608</td>
      <td>Dessert Shop</td>
    </tr>
    <tr>
      <th>21</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Rikkochez</td>
      <td>43.677267</td>
      <td>-79.353274</td>
      <td>Restaurant</td>
    </tr>
    <tr>
      <th>22</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Re: Reading</td>
      <td>43.678507</td>
      <td>-79.347678</td>
      <td>Bookstore</td>
    </tr>
    <tr>
      <th>23</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Christina's On The Danforth</td>
      <td>43.678240</td>
      <td>-79.349185</td>
      <td>Greek Restaurant</td>
    </tr>
    <tr>
      <th>24</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>IQ Living</td>
      <td>43.678477</td>
      <td>-79.347811</td>
      <td>Furniture / Home Store</td>
    </tr>
    <tr>
      <th>25</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Astoria Shish Kebob House</td>
      <td>43.677689</td>
      <td>-79.351892</td>
      <td>Greek Restaurant</td>
    </tr>
    <tr>
      <th>26</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Tsaa Tea Shop</td>
      <td>43.677769</td>
      <td>-79.351304</td>
      <td>Bubble Tea Shop</td>
    </tr>
    <tr>
      <th>27</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Don Valley Trail</td>
      <td>43.676331</td>
      <td>-79.353923</td>
      <td>Trail</td>
    </tr>
    <tr>
      <th>28</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Athen's Pastries</td>
      <td>43.678166</td>
      <td>-79.348927</td>
      <td>Greek Restaurant</td>
    </tr>
    <tr>
      <th>29</th>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>Urban Nails</td>
      <td>43.676668</td>
      <td>-79.356602</td>
      <td>Spa</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>1685</th>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
      <td>Heart</td>
      <td>43.650310</td>
      <td>-79.480125</td>
      <td>Dessert Shop</td>
    </tr>
    <tr>
      <th>1686</th>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
      <td>Coffee Tree</td>
      <td>43.650075</td>
      <td>-79.483140</td>
      <td>Café</td>
    </tr>
    <tr>
      <th>1687</th>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
      <td>Second Cup</td>
      <td>43.650137</td>
      <td>-79.480795</td>
      <td>Café</td>
    </tr>
    <tr>
      <th>1688</th>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
      <td>Pizzaiolo</td>
      <td>43.649395</td>
      <td>-79.483560</td>
      <td>Pizza Place</td>
    </tr>
    <tr>
      <th>1689</th>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
      <td>Classico</td>
      <td>43.649194</td>
      <td>-79.484699</td>
      <td>Pizza Place</td>
    </tr>
    <tr>
      <th>1690</th>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
      <td>Supper Solved</td>
      <td>43.648781</td>
      <td>-79.485233</td>
      <td>Restaurant</td>
    </tr>
    <tr>
      <th>1691</th>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
      <td>Cards 'N' Such</td>
      <td>43.650497</td>
      <td>-79.480778</td>
      <td>Post Office</td>
    </tr>
    <tr>
      <th>1692</th>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
      <td>The Coffee Bouquets</td>
      <td>43.648785</td>
      <td>-79.485940</td>
      <td>Coffee Shop</td>
    </tr>
    <tr>
      <th>1693</th>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
      <td>Think Fitness</td>
      <td>43.647966</td>
      <td>-79.486462</td>
      <td>Gym</td>
    </tr>
    <tr>
      <th>1694</th>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
      <td>Fresh and Wild</td>
      <td>43.650647</td>
      <td>-79.478996</td>
      <td>Grocery Store</td>
    </tr>
    <tr>
      <th>1695</th>
      <td>Runnymede,Swansea</td>
      <td>43.651571</td>
      <td>-79.484450</td>
      <td>Los Arrieros</td>
      <td>43.655593</td>
      <td>-79.487028</td>
      <td>South American Restaurant</td>
    </tr>
    <tr>
      <th>1696</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>Rorschach Brewing Co.</td>
      <td>43.663483</td>
      <td>-79.319824</td>
      <td>Brewery</td>
    </tr>
    <tr>
      <th>1697</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>Leslieville Farmers Market</td>
      <td>43.664901</td>
      <td>-79.319784</td>
      <td>Farmers Market</td>
    </tr>
    <tr>
      <th>1698</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>The Sidekick</td>
      <td>43.664484</td>
      <td>-79.325162</td>
      <td>Comic Shop</td>
    </tr>
    <tr>
      <th>1699</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>Chino Locos</td>
      <td>43.664653</td>
      <td>-79.325584</td>
      <td>Burrito Place</td>
    </tr>
    <tr>
      <th>1700</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>Queen Margherita Pizza</td>
      <td>43.664685</td>
      <td>-79.324164</td>
      <td>Pizza Place</td>
    </tr>
    <tr>
      <th>1701</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>The Green Wood</td>
      <td>43.664728</td>
      <td>-79.324117</td>
      <td>Restaurant</td>
    </tr>
    <tr>
      <th>1702</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>Chick-n-Joy</td>
      <td>43.665181</td>
      <td>-79.321403</td>
      <td>Fast Food Restaurant</td>
    </tr>
    <tr>
      <th>1703</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>Ashbridges Bay Skatepark</td>
      <td>43.662548</td>
      <td>-79.315631</td>
      <td>Skate Park</td>
    </tr>
    <tr>
      <th>1704</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>East End Garden Centre &amp; Hardware</td>
      <td>43.664555</td>
      <td>-79.324598</td>
      <td>Garden Center</td>
    </tr>
    <tr>
      <th>1705</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>Amin Car Repair Garage</td>
      <td>43.663544</td>
      <td>-79.320130</td>
      <td>Auto Workshop</td>
    </tr>
    <tr>
      <th>1706</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>The Ashbridge Estate</td>
      <td>43.664691</td>
      <td>-79.321805</td>
      <td>Garden</td>
    </tr>
    <tr>
      <th>1707</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>TTC Russell Division</td>
      <td>43.664908</td>
      <td>-79.322560</td>
      <td>Light Rail Station</td>
    </tr>
    <tr>
      <th>1708</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>Jonathan Ashbridge Park</td>
      <td>43.664702</td>
      <td>-79.319898</td>
      <td>Park</td>
    </tr>
    <tr>
      <th>1709</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>The Ten Spot</td>
      <td>43.664815</td>
      <td>-79.324213</td>
      <td>Spa</td>
    </tr>
    <tr>
      <th>1710</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>Toronto Yoga Mamas</td>
      <td>43.664824</td>
      <td>-79.324335</td>
      <td>Yoga Studio</td>
    </tr>
    <tr>
      <th>1711</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>Olliffe On Queen</td>
      <td>43.664503</td>
      <td>-79.324768</td>
      <td>Butcher</td>
    </tr>
    <tr>
      <th>1712</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>TTC Stop #03049</td>
      <td>43.664470</td>
      <td>-79.325145</td>
      <td>Light Rail Station</td>
    </tr>
    <tr>
      <th>1713</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>Greenwood Cigar &amp; Variety</td>
      <td>43.664538</td>
      <td>-79.325379</td>
      <td>Smoke Shop</td>
    </tr>
    <tr>
      <th>1714</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>43.662744</td>
      <td>-79.321558</td>
      <td>ONE Academy</td>
      <td>43.662253</td>
      <td>-79.326911</td>
      <td>Gym / Fitness Center</td>
    </tr>
  </tbody>
</table>
<p>1715 rows × 7 columns</p>
</div>




```python
map_result.shape
```




    (1715, 7)




```python
# venues summary
toronto_venues = pd.get_dummies(map_result[['Venue Category']], prefix="", prefix_sep="")
toronto_venues.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Afghan Restaurant</th>
      <th>Airport</th>
      <th>Airport Food Court</th>
      <th>Airport Gate</th>
      <th>Airport Lounge</th>
      <th>Airport Service</th>
      <th>Airport Terminal</th>
      <th>American Restaurant</th>
      <th>Antique Shop</th>
      <th>Aquarium</th>
      <th>...</th>
      <th>Toy / Game Store</th>
      <th>Trail</th>
      <th>Train Station</th>
      <th>Vegetarian / Vegan Restaurant</th>
      <th>Video Game Store</th>
      <th>Vietnamese Restaurant</th>
      <th>Wine Bar</th>
      <th>Wings Joint</th>
      <th>Women's Store</th>
      <th>Yoga Studio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 240 columns</p>
</div>




```python
#add Neighbor into the dataframe to avoid overlapping.
## there is a column called Neighborhood
toronto_venues.insert(0,'Neighbor',map_result['Neighborhood'])
toronto_venues.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Neighbor</th>
      <th>Afghan Restaurant</th>
      <th>Airport</th>
      <th>Airport Food Court</th>
      <th>Airport Gate</th>
      <th>Airport Lounge</th>
      <th>Airport Service</th>
      <th>Airport Terminal</th>
      <th>American Restaurant</th>
      <th>Antique Shop</th>
      <th>...</th>
      <th>Toy / Game Store</th>
      <th>Trail</th>
      <th>Train Station</th>
      <th>Vegetarian / Vegan Restaurant</th>
      <th>Video Game Store</th>
      <th>Vietnamese Restaurant</th>
      <th>Wine Bar</th>
      <th>Wings Joint</th>
      <th>Women's Store</th>
      <th>Yoga Studio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>The Beaches</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>The Beaches</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>The Beaches</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>The Beaches</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>The Beaches</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 241 columns</p>
</div>




```python
toronto_grouped = toronto_venues.groupby('Neighbor').mean().reset_index()
toronto_grouped
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Neighbor</th>
      <th>Afghan Restaurant</th>
      <th>Airport</th>
      <th>Airport Food Court</th>
      <th>Airport Gate</th>
      <th>Airport Lounge</th>
      <th>Airport Service</th>
      <th>Airport Terminal</th>
      <th>American Restaurant</th>
      <th>Antique Shop</th>
      <th>...</th>
      <th>Toy / Game Store</th>
      <th>Trail</th>
      <th>Train Station</th>
      <th>Vegetarian / Vegan Restaurant</th>
      <th>Video Game Store</th>
      <th>Vietnamese Restaurant</th>
      <th>Wine Bar</th>
      <th>Wings Joint</th>
      <th>Women's Store</th>
      <th>Yoga Studio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Adelaide,King,Richmond</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.030000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.020000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.01</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Berczy Park</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.017857</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Brockton,Exhibition Place,Parkdale Village</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.074074</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.052632</td>
    </tr>
    <tr>
      <th>4</th>
      <td>CN Tower,Bathurst Quay,Island airport,Harbourf...</td>
      <td>0.000000</td>
      <td>0.066667</td>
      <td>0.066667</td>
      <td>0.066667</td>
      <td>0.133333</td>
      <td>0.133333</td>
      <td>0.133333</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Cabbagetown,St. James Town</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Central Bay Street</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.011628</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.011628</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.011628</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.011628</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Chinatown,Grange Park,Kensington Market</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.060000</td>
      <td>0.000000</td>
      <td>0.040000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Christie</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Church and Wellesley</td>
      <td>0.011494</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.011494</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.011494</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.011494</td>
      <td>0.00</td>
      <td>0.022989</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Commerce Court,Victoria Hotel</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.040000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.020000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Davisville</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.030303</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Davisville North</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Deer Park,Forest Hill SE,Rathnelly,South Hill,...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.062500</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.062500</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>14</th>
      <td>Design Exchange,Toronto Dominion Centre</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.020000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.01</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>15</th>
      <td>Dovercourt Village,Dufferin</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>16</th>
      <td>First Canadian Place,Underground city</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.030000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.01</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>17</th>
      <td>Forest Hill North,Forest Hill West</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.200000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>18</th>
      <td>Harbord,University of Toronto</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.027778</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.027778</td>
    </tr>
    <tr>
      <th>19</th>
      <td>Harbourfront East,Toronto Islands,Union Station</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.01</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>20</th>
      <td>Harbourfront,Regent Park</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.019231</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>21</th>
      <td>High Park,The Junction South</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>22</th>
      <td>Lawrence Park</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>23</th>
      <td>Little Portugal,Trinity</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.029851</td>
      <td>0.014925</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.014925</td>
    </tr>
    <tr>
      <th>24</th>
      <td>Moore Park,Summerhill East</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>25</th>
      <td>North Toronto West</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.052632</td>
    </tr>
    <tr>
      <th>26</th>
      <td>Parkdale,Roncesvalles</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>27</th>
      <td>Rosedale</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.200000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>28</th>
      <td>Roselawn</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>29</th>
      <td>Runnymede,Swansea</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.027778</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>30</th>
      <td>Ryerson,Garden District</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.010000</td>
      <td>0.010000</td>
      <td>0.010000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>31</th>
      <td>St. James Town</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.020000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>32</th>
      <td>Stn A PO Boxes 25 The Esplanade</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010204</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.010204</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>33</th>
      <td>Studio District</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.051282</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.025641</td>
    </tr>
    <tr>
      <th>34</th>
      <td>The Annex,North Midtown,Yorkville</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.047619</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.047619</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>35</th>
      <td>The Beaches</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.200000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>36</th>
      <td>The Beaches West,India Bazaar</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>37</th>
      <td>The Danforth West,Riverdale</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.023256</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.023256</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.023256</td>
    </tr>
  </tbody>
</table>
<p>38 rows × 241 columns</p>
</div>



# Use k-means to cluster neighborhood of Toronto by venues characteristics.


```python
from sklearn.cluster import KMeans
```


```python
# set number of clusters
kclusters = 5

toronto_grouped_clustering = toronto_grouped.drop('Neighbor', 1)

# run k-means clustering
kmeans = KMeans(n_clusters=kclusters, random_state=0).fit(toronto_grouped_clustering)

# check cluster labels generated for each row in the dataframe
kmeans.labels_[-10:-1] 
```




    array([4, 3, 3, 3, 3, 3, 3, 3, 3])




```python
# add clustering labels
toronto_grouped.insert(1, 'Cluster Labels', kmeans.labels_)
toronto_grouped
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Neighbor</th>
      <th>Cluster Labels</th>
      <th>Afghan Restaurant</th>
      <th>Airport</th>
      <th>Airport Food Court</th>
      <th>Airport Gate</th>
      <th>Airport Lounge</th>
      <th>Airport Service</th>
      <th>Airport Terminal</th>
      <th>American Restaurant</th>
      <th>...</th>
      <th>Toy / Game Store</th>
      <th>Trail</th>
      <th>Train Station</th>
      <th>Vegetarian / Vegan Restaurant</th>
      <th>Video Game Store</th>
      <th>Vietnamese Restaurant</th>
      <th>Wine Bar</th>
      <th>Wings Joint</th>
      <th>Women's Store</th>
      <th>Yoga Studio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Adelaide,King,Richmond</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.030000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.020000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.01</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Berczy Park</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.017857</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Brockton,Exhibition Place,Parkdale Village</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.074074</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Business Reply Mail Processing Centre 969 Eastern</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.052632</td>
    </tr>
    <tr>
      <th>4</th>
      <td>CN Tower,Bathurst Quay,Island airport,Harbourf...</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.066667</td>
      <td>0.066667</td>
      <td>0.066667</td>
      <td>0.133333</td>
      <td>0.133333</td>
      <td>0.133333</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Cabbagetown,St. James Town</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Central Bay Street</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.011628</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.011628</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.011628</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.011628</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Chinatown,Grange Park,Kensington Market</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.060000</td>
      <td>0.000000</td>
      <td>0.040000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Christie</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Church and Wellesley</td>
      <td>3</td>
      <td>0.011494</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.011494</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.011494</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.011494</td>
      <td>0.00</td>
      <td>0.022989</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Commerce Court,Victoria Hotel</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.040000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.020000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Davisville</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.030303</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Davisville North</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Deer Park,Forest Hill SE,Rathnelly,South Hill,...</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.062500</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.062500</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>14</th>
      <td>Design Exchange,Toronto Dominion Centre</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.020000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.01</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>15</th>
      <td>Dovercourt Village,Dufferin</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>16</th>
      <td>First Canadian Place,Underground city</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.030000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.01</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>17</th>
      <td>Forest Hill North,Forest Hill West</td>
      <td>1</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.200000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>18</th>
      <td>Harbord,University of Toronto</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.027778</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.027778</td>
    </tr>
    <tr>
      <th>19</th>
      <td>Harbourfront East,Toronto Islands,Union Station</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.01</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>20</th>
      <td>Harbourfront,Regent Park</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>21</th>
      <td>High Park,The Junction South</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>22</th>
      <td>Lawrence Park</td>
      <td>2</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>23</th>
      <td>Little Portugal,Trinity</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.029851</td>
      <td>0.014925</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.014925</td>
    </tr>
    <tr>
      <th>24</th>
      <td>Moore Park,Summerhill East</td>
      <td>0</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>25</th>
      <td>North Toronto West</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.052632</td>
    </tr>
    <tr>
      <th>26</th>
      <td>Parkdale,Roncesvalles</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>27</th>
      <td>Rosedale</td>
      <td>1</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.200000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>28</th>
      <td>Roselawn</td>
      <td>4</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>29</th>
      <td>Runnymede,Swansea</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.027778</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>30</th>
      <td>Ryerson,Garden District</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>...</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.010000</td>
      <td>0.010000</td>
      <td>0.010000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>31</th>
      <td>St. James Town</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.020000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.010000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>32</th>
      <td>Stn A PO Boxes 25 The Esplanade</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.010204</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>33</th>
      <td>Studio District</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.051282</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.025641</td>
    </tr>
    <tr>
      <th>34</th>
      <td>The Annex,North Midtown,Yorkville</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.047619</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.047619</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>35</th>
      <td>The Beaches</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.200000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>36</th>
      <td>The Beaches West,India Bazaar</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>37</th>
      <td>The Danforth West,Riverdale</td>
      <td>3</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.023256</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.023256</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.023256</td>
    </tr>
  </tbody>
</table>
<p>38 rows × 242 columns</p>
</div>




```python
toronto_merged = df_map
toronto_merged.rename(columns={'Neighborhood':'Neighbor'},inplace=True)
# merge toronto_grouped with toronto_data to add latitude/longitude for each neighborhood
toronto_merged = toronto_merged.join(toronto_grouped.set_index('Neighbor'), on='Neighbor')

toronto_merged.head() # check the last columns!
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>PostalCode</th>
      <th>Borough</th>
      <th>Neighbor</th>
      <th>Latitude</th>
      <th>Longitude</th>
      <th>Cluster Labels</th>
      <th>Afghan Restaurant</th>
      <th>Airport</th>
      <th>Airport Food Court</th>
      <th>Airport Gate</th>
      <th>...</th>
      <th>Toy / Game Store</th>
      <th>Trail</th>
      <th>Train Station</th>
      <th>Vegetarian / Vegan Restaurant</th>
      <th>Video Game Store</th>
      <th>Vietnamese Restaurant</th>
      <th>Wine Bar</th>
      <th>Wings Joint</th>
      <th>Women's Store</th>
      <th>Yoga Studio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>37</th>
      <td>M4E</td>
      <td>East Toronto</td>
      <td>The Beaches</td>
      <td>43.676357</td>
      <td>-79.293031</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.200000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>41</th>
      <td>M4K</td>
      <td>East Toronto</td>
      <td>The Danforth West,Riverdale</td>
      <td>43.679557</td>
      <td>-79.352188</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.023256</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.023256</td>
    </tr>
    <tr>
      <th>42</th>
      <td>M4L</td>
      <td>East Toronto</td>
      <td>The Beaches West,India Bazaar</td>
      <td>43.668999</td>
      <td>-79.315572</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>43</th>
      <td>M4M</td>
      <td>East Toronto</td>
      <td>Studio District</td>
      <td>43.659526</td>
      <td>-79.340923</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.025641</td>
    </tr>
    <tr>
      <th>44</th>
      <td>M4N</td>
      <td>Central Toronto</td>
      <td>Lawrence Park</td>
      <td>43.728020</td>
      <td>-79.388790</td>
      <td>2</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000000</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 246 columns</p>
</div>




```python
import numpy as np
import matplotlib.cm as cm
import matplotlib.colors as colors
```


```python
# create map
map_final = folium.Map(location=[43.6532, -79.3832], zoom_start=12)

# set color scheme for the clusters
x = np.arange(kclusters)
ys = [i + x + (i*x)**2 for i in range(kclusters)]
colors_array = cm.rainbow(np.linspace(0, 1, len(ys)))
rainbow = [colors.rgb2hex(i) for i in colors_array]

# add markers to the map
markers_colors = []
for lat, lon, poi, cluster in zip(toronto_merged['Latitude'], toronto_merged['Longitude'], toronto_merged['Neighbor'], toronto_merged['Cluster Labels']):
    label = folium.Popup(str(poi) + ' Cluster ' + str(cluster), parse_html=True)
    folium.CircleMarker(
        [lat, lon],
        radius=5,
        popup=label,
        color=rainbow[cluster-2],
        fill=True,
        fill_color=rainbow[cluster-2],
        fill_opacity=0.7).add_to(map_final)
       
map_final
```




<div style="width:100%;"><div style="position:relative;width:100%;height:0;padding-bottom:60%;"><iframe src="data:text/html;charset=utf-8;base64,PCFET0NUWVBFIGh0bWw+CjxoZWFkPiAgICAKICAgIDxtZXRhIGh0dHAtZXF1aXY9ImNvbnRlbnQtdHlwZSIgY29udGVudD0idGV4dC9odG1sOyBjaGFyc2V0PVVURi04IiAvPgogICAgPHNjcmlwdD5MX1BSRUZFUl9DQU5WQVMgPSBmYWxzZTsgTF9OT19UT1VDSCA9IGZhbHNlOyBMX0RJU0FCTEVfM0QgPSBmYWxzZTs8L3NjcmlwdD4KICAgIDxzY3JpcHQgc3JjPSJodHRwczovL2Nkbi5qc2RlbGl2ci5uZXQvbnBtL2xlYWZsZXRAMS4yLjAvZGlzdC9sZWFmbGV0LmpzIj48L3NjcmlwdD4KICAgIDxzY3JpcHQgc3JjPSJodHRwczovL2FqYXguZ29vZ2xlYXBpcy5jb20vYWpheC9saWJzL2pxdWVyeS8xLjExLjEvanF1ZXJ5Lm1pbi5qcyI+PC9zY3JpcHQ+CiAgICA8c2NyaXB0IHNyYz0iaHR0cHM6Ly9tYXhjZG4uYm9vdHN0cmFwY2RuLmNvbS9ib290c3RyYXAvMy4yLjAvanMvYm9vdHN0cmFwLm1pbi5qcyI+PC9zY3JpcHQ+CiAgICA8c2NyaXB0IHNyYz0iaHR0cHM6Ly9jZG5qcy5jbG91ZGZsYXJlLmNvbS9hamF4L2xpYnMvTGVhZmxldC5hd2Vzb21lLW1hcmtlcnMvMi4wLjIvbGVhZmxldC5hd2Vzb21lLW1hcmtlcnMuanMiPjwvc2NyaXB0PgogICAgPGxpbmsgcmVsPSJzdHlsZXNoZWV0IiBocmVmPSJodHRwczovL2Nkbi5qc2RlbGl2ci5uZXQvbnBtL2xlYWZsZXRAMS4yLjAvZGlzdC9sZWFmbGV0LmNzcyIvPgogICAgPGxpbmsgcmVsPSJzdHlsZXNoZWV0IiBocmVmPSJodHRwczovL21heGNkbi5ib290c3RyYXBjZG4uY29tL2Jvb3RzdHJhcC8zLjIuMC9jc3MvYm9vdHN0cmFwLm1pbi5jc3MiLz4KICAgIDxsaW5rIHJlbD0ic3R5bGVzaGVldCIgaHJlZj0iaHR0cHM6Ly9tYXhjZG4uYm9vdHN0cmFwY2RuLmNvbS9ib290c3RyYXAvMy4yLjAvY3NzL2Jvb3RzdHJhcC10aGVtZS5taW4uY3NzIi8+CiAgICA8bGluayByZWw9InN0eWxlc2hlZXQiIGhyZWY9Imh0dHBzOi8vbWF4Y2RuLmJvb3RzdHJhcGNkbi5jb20vZm9udC1hd2Vzb21lLzQuNi4zL2Nzcy9mb250LWF3ZXNvbWUubWluLmNzcyIvPgogICAgPGxpbmsgcmVsPSJzdHlsZXNoZWV0IiBocmVmPSJodHRwczovL2NkbmpzLmNsb3VkZmxhcmUuY29tL2FqYXgvbGlicy9MZWFmbGV0LmF3ZXNvbWUtbWFya2Vycy8yLjAuMi9sZWFmbGV0LmF3ZXNvbWUtbWFya2Vycy5jc3MiLz4KICAgIDxsaW5rIHJlbD0ic3R5bGVzaGVldCIgaHJlZj0iaHR0cHM6Ly9yYXdnaXQuY29tL3B5dGhvbi12aXN1YWxpemF0aW9uL2ZvbGl1bS9tYXN0ZXIvZm9saXVtL3RlbXBsYXRlcy9sZWFmbGV0LmF3ZXNvbWUucm90YXRlLmNzcyIvPgogICAgPHN0eWxlPmh0bWwsIGJvZHkge3dpZHRoOiAxMDAlO2hlaWdodDogMTAwJTttYXJnaW46IDA7cGFkZGluZzogMDt9PC9zdHlsZT4KICAgIDxzdHlsZT4jbWFwIHtwb3NpdGlvbjphYnNvbHV0ZTt0b3A6MDtib3R0b206MDtyaWdodDowO2xlZnQ6MDt9PC9zdHlsZT4KICAgIAogICAgICAgICAgICA8c3R5bGU+ICNtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcgewogICAgICAgICAgICAgICAgcG9zaXRpb24gOiByZWxhdGl2ZTsKICAgICAgICAgICAgICAgIHdpZHRoIDogMTAwLjAlOwogICAgICAgICAgICAgICAgaGVpZ2h0OiAxMDAuMCU7CiAgICAgICAgICAgICAgICBsZWZ0OiAwLjAlOwogICAgICAgICAgICAgICAgdG9wOiAwLjAlOwogICAgICAgICAgICAgICAgfQogICAgICAgICAgICA8L3N0eWxlPgogICAgICAgIAo8L2hlYWQ+Cjxib2R5PiAgICAKICAgIAogICAgICAgICAgICA8ZGl2IGNsYXNzPSJmb2xpdW0tbWFwIiBpZD0ibWFwX2ViZTM3MzQyN2NjMjRmZmNhMGZhYmQwMDg4NjMyZGU3IiA+PC9kaXY+CiAgICAgICAgCjwvYm9keT4KPHNjcmlwdD4gICAgCiAgICAKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGJvdW5kcyA9IG51bGw7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgdmFyIG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyA9IEwubWFwKAogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgJ21hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNycsCiAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICB7Y2VudGVyOiBbNDMuNjUzMiwtNzkuMzgzMl0sCiAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICB6b29tOiAxMiwKICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIG1heEJvdW5kczogYm91bmRzLAogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgbGF5ZXJzOiBbXSwKICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIHdvcmxkQ29weUp1bXA6IGZhbHNlLAogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgY3JzOiBMLkNSUy5FUFNHMzg1NwogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICB9KTsKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHRpbGVfbGF5ZXJfYWNiZjMwNWUzZjM5NDAyNTg2ODdmYjExZThhN2I5NDUgPSBMLnRpbGVMYXllcigKICAgICAgICAgICAgICAgICdodHRwczovL3tzfS50aWxlLm9wZW5zdHJlZXRtYXAub3JnL3t6fS97eH0ve3l9LnBuZycsCiAgICAgICAgICAgICAgICB7CiAgImF0dHJpYnV0aW9uIjogbnVsbCwKICAiZGV0ZWN0UmV0aW5hIjogZmFsc2UsCiAgIm1heFpvb20iOiAxOCwKICAibWluWm9vbSI6IDEsCiAgIm5vV3JhcCI6IGZhbHNlLAogICJzdWJkb21haW5zIjogImFiYyIKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzRiNWQ1ZTM1MmJjNzQzNzVhZDg3ODVlZGQxZWM2NzU5ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjc2MzU3Mzk5OTk5OTksLTc5LjI5MzAzMTJdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfZmNhNjg2YWI4YTM2NGViZTk4ZjBmYWZlOThjOWU1OTcgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfNDcxM2NhZWY0ZGQxNGI4M2IxOTMxMGI3ZDZlZmNhNzIgPSAkKCc8ZGl2IGlkPSJodG1sXzQ3MTNjYWVmNGRkMTRiODNiMTkzMTBiN2Q2ZWZjYTcyIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5UaGUgQmVhY2hlcyBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2ZjYTY4NmFiOGEzNjRlYmU5OGYwZmFmZTk4YzllNTk3LnNldENvbnRlbnQoaHRtbF80NzEzY2FlZjRkZDE0YjgzYjE5MzEwYjdkNmVmY2E3Mik7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl80YjVkNWUzNTJiYzc0Mzc1YWQ4Nzg1ZWRkMWVjNjc1OS5iaW5kUG9wdXAocG9wdXBfZmNhNjg2YWI4YTM2NGViZTk4ZjBmYWZlOThjOWU1OTcpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYjQzMWJkMGYzOWNiNDQwMmJiZWEwYTAzYjQ3MzgzYWUgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42Nzk1NTcxLC03OS4zNTIxODhdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfMDc5ODZiZTg3MzVhNGJjMmFlN2UyMzE5M2E0NjEyMDAgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfMmZlZWIzYzBlNmViNGUwOTk5YzIxMWFiMzA2MjlhMDggPSAkKCc8ZGl2IGlkPSJodG1sXzJmZWViM2MwZTZlYjRlMDk5OWMyMTFhYjMwNjI5YTA4IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5UaGUgRGFuZm9ydGggV2VzdCxSaXZlcmRhbGUgQ2x1c3RlciAzPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF8wNzk4NmJlODczNWE0YmMyYWU3ZTIzMTkzYTQ2MTIwMC5zZXRDb250ZW50KGh0bWxfMmZlZWIzYzBlNmViNGUwOTk5YzIxMWFiMzA2MjlhMDgpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfYjQzMWJkMGYzOWNiNDQwMmJiZWEwYTAzYjQ3MzgzYWUuYmluZFBvcHVwKHBvcHVwXzA3OTg2YmU4NzM1YTRiYzJhZTdlMjMxOTNhNDYxMjAwKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2QwMTc0YzExN2FlYzRkMDVhYmZkNGNjY2YwZjEzNzU4ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjY4OTk4NSwtNzkuMzE1NTcxNTk5OTk5OThdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfNzA1NGRmYjk4YmIzNGQ1NDhiNDJlZWVmOTE1MWEzMWIgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfNzQ1MWRkOTllZjcxNDhiMjk5OWJjYjQ4YmUzZWI5NmUgPSAkKCc8ZGl2IGlkPSJodG1sXzc0NTFkZDk5ZWY3MTQ4YjI5OTliY2I0OGJlM2ViOTZlIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5UaGUgQmVhY2hlcyBXZXN0LEluZGlhIEJhemFhciBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzcwNTRkZmI5OGJiMzRkNTQ4YjQyZWVlZjkxNTFhMzFiLnNldENvbnRlbnQoaHRtbF83NDUxZGQ5OWVmNzE0OGIyOTk5YmNiNDhiZTNlYjk2ZSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9kMDE3NGMxMTdhZWM0ZDA1YWJmZDRjY2NmMGYxMzc1OC5iaW5kUG9wdXAocG9wdXBfNzA1NGRmYjk4YmIzNGQ1NDhiNDJlZWVmOTE1MWEzMWIpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYTBiYjY5YjJmYmQ3NDgzMGI5NTJiYjdmYzdhM2YzMDAgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NTk1MjU1LC03OS4zNDA5MjNdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfMzkxYWI3MmE0NjBjNGYwOWFiZGUwZjcxYzE4YjJiZTcgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfNzBiMzdlMzFmZGQwNDYzZGFlYmVmNWNmZjM0ZjAwOGEgPSAkKCc8ZGl2IGlkPSJodG1sXzcwYjM3ZTMxZmRkMDQ2M2RhZWJlZjVjZmYzNGYwMDhhIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5TdHVkaW8gRGlzdHJpY3QgQ2x1c3RlciAzPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF8zOTFhYjcyYTQ2MGM0ZjA5YWJkZTBmNzFjMThiMmJlNy5zZXRDb250ZW50KGh0bWxfNzBiMzdlMzFmZGQwNDYzZGFlYmVmNWNmZjM0ZjAwOGEpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfYTBiYjY5YjJmYmQ3NDgzMGI5NTJiYjdmYzdhM2YzMDAuYmluZFBvcHVwKHBvcHVwXzM5MWFiNzJhNDYwYzRmMDlhYmRlMGY3MWMxOGIyYmU3KTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzE4ZmFjNmExNmY3MjQ4NTBhOWI5ZDA5YTg1OWJjMTQ0ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNzI4MDIwNSwtNzkuMzg4NzkwMV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICIjODAwMGZmIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzgwMDBmZiIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF9mNTBlMzQxNjI4OWE0ODE4OGNjYTNkNGIyN2Y2ODE1NSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9iNjRmYTQwYmVlNmQ0YjQ3YTk4NjM0YTA4ODQ3YzY0OCA9ICQoJzxkaXYgaWQ9Imh0bWxfYjY0ZmE0MGJlZTZkNGI0N2E5ODYzNGEwODg0N2M2NDgiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkxhd3JlbmNlIFBhcmsgQ2x1c3RlciAyPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF9mNTBlMzQxNjI4OWE0ODE4OGNjYTNkNGIyN2Y2ODE1NS5zZXRDb250ZW50KGh0bWxfYjY0ZmE0MGJlZTZkNGI0N2E5ODYzNGEwODg0N2M2NDgpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfMThmYWM2YTE2ZjcyNDg1MGE5YjlkMDlhODU5YmMxNDQuYmluZFBvcHVwKHBvcHVwX2Y1MGUzNDE2Mjg5YTQ4MTg4Y2NhM2Q0YjI3ZjY4MTU1KTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzJjZGU5MDIyYjk4ZjQyYjY4OGE0ZmVhZDE2YWUzMjdiID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNzEyNzUxMSwtNzkuMzkwMTk3NV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICIjMDBiNWViIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzAwYjVlYiIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8wM2E0NWU3MjkzN2Q0NTg1Yjg3NWJlZTYzODEyNzdiNiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF83YTIzYmRhYzFjNTg0YTZmYTAzZGJhZmM2NWQ1ZmVhOSA9ICQoJzxkaXYgaWQ9Imh0bWxfN2EyM2JkYWMxYzU4NGE2ZmEwM2RiYWZjNjVkNWZlYTkiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkRhdmlzdmlsbGUgTm9ydGggQ2x1c3RlciAzPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF8wM2E0NWU3MjkzN2Q0NTg1Yjg3NWJlZTYzODEyNzdiNi5zZXRDb250ZW50KGh0bWxfN2EyM2JkYWMxYzU4NGE2ZmEwM2RiYWZjNjVkNWZlYTkpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfMmNkZTkwMjJiOThmNDJiNjg4YTRmZWFkMTZhZTMyN2IuYmluZFBvcHVwKHBvcHVwXzAzYTQ1ZTcyOTM3ZDQ1ODViODc1YmVlNjM4MTI3N2I2KTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzkyMzFkYzc0ZTY4ZjQxODhiMDJmNjc3ZDUxNTVjMTJiID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNzE1MzgzNCwtNzkuNDA1Njc4NDAwMDAwMDFdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfODQ1ZWU2ZTFlNjYzNDFiN2E2NDMwMTc4MzBmZmU5MTIgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfMjIwNWZiYTRkODZhNDA3NWJmMDU4NTBkMWI1NzI1NjUgPSAkKCc8ZGl2IGlkPSJodG1sXzIyMDVmYmE0ZDg2YTQwNzViZjA1ODUwZDFiNTcyNTY1IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Ob3J0aCBUb3JvbnRvIFdlc3QgQ2x1c3RlciAzPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF84NDVlZTZlMWU2NjM0MWI3YTY0MzAxNzgzMGZmZTkxMi5zZXRDb250ZW50KGh0bWxfMjIwNWZiYTRkODZhNDA3NWJmMDU4NTBkMWI1NzI1NjUpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfOTIzMWRjNzRlNjhmNDE4OGIwMmY2NzdkNTE1NWMxMmIuYmluZFBvcHVwKHBvcHVwXzg0NWVlNmUxZTY2MzQxYjdhNjQzMDE3ODMwZmZlOTEyKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzlmOGVmYjg5M2U1ZTQ4MWNhM2ViNDZmZTYxN2I0NzM0ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNzA0MzI0NCwtNzkuMzg4NzkwMV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICIjMDBiNWViIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzAwYjVlYiIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8wNjA1NWJjNTI1ODQ0NzhlYWU3Yjg0YzMwYzkxMWUxOCA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF80ZjUwZDg5NDYyNmI0MDRjODZjNzJmNmIzMmIyYWUzYiA9ICQoJzxkaXYgaWQ9Imh0bWxfNGY1MGQ4OTQ2MjZiNDA0Yzg2YzcyZjZiMzJiMmFlM2IiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkRhdmlzdmlsbGUgQ2x1c3RlciAzPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF8wNjA1NWJjNTI1ODQ0NzhlYWU3Yjg0YzMwYzkxMWUxOC5zZXRDb250ZW50KGh0bWxfNGY1MGQ4OTQ2MjZiNDA0Yzg2YzcyZjZiMzJiMmFlM2IpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfOWY4ZWZiODkzZTVlNDgxY2EzZWI0NmZlNjE3YjQ3MzQuYmluZFBvcHVwKHBvcHVwXzA2MDU1YmM1MjU4NDQ3OGVhZTdiODRjMzBjOTExZTE4KTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2ZhMzgxNWJlNDBiYjRmNjk4Y2RiYmFjYjUzYTVlYTA1ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjg5NTc0MywtNzkuMzgzMTU5OTAwMDAwMDFdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiI2ZmYjM2MCIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiNmZmIzNjAiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfMjBhMjg5Mzk3MjczNDNjOGI3ZmMxODBhMTEyMDRiNTIgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfZDBmN2FlOWNiODgwNDQ2ZGE4NmE1Y2NiZDAwNDZkNjkgPSAkKCc8ZGl2IGlkPSJodG1sX2QwZjdhZTljYjg4MDQ0NmRhODZhNWNjYmQwMDQ2ZDY5IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Nb29yZSBQYXJrLFN1bW1lcmhpbGwgRWFzdCBDbHVzdGVyIDA8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzIwYTI4OTM5NzI3MzQzYzhiN2ZjMTgwYTExMjA0YjUyLnNldENvbnRlbnQoaHRtbF9kMGY3YWU5Y2I4ODA0NDZkYTg2YTVjY2JkMDA0NmQ2OSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9mYTM4MTViZTQwYmI0ZjY5OGNkYmJhY2I1M2E1ZWEwNS5iaW5kUG9wdXAocG9wdXBfMjBhMjg5Mzk3MjczNDNjOGI3ZmMxODBhMTEyMDRiNTIpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNjE1N2Q5MmExM2U5NDIxNTkzZmE5YTIzODRkODcxNzIgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42ODY0MTIyOTk5OTk5OSwtNzkuNDAwMDQ5M10sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICIjMDBiNWViIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzAwYjVlYiIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF9kYzNhYTM5MGZiNWE0ZDY2YWEyZjg0MjkyODllODQ1OSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF8yYzZmNGZhMzAxZTM0MGZjYmZkODFkMDQxMzUzNDlmNiA9ICQoJzxkaXYgaWQ9Imh0bWxfMmM2ZjRmYTMwMWUzNDBmY2JmZDgxZDA0MTM1MzQ5ZjYiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkRlZXIgUGFyayxGb3Jlc3QgSGlsbCBTRSxSYXRobmVsbHksU291dGggSGlsbCxTdW1tZXJoaWxsIFdlc3QgQ2x1c3RlciAzPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF9kYzNhYTM5MGZiNWE0ZDY2YWEyZjg0MjkyODllODQ1OS5zZXRDb250ZW50KGh0bWxfMmM2ZjRmYTMwMWUzNDBmY2JmZDgxZDA0MTM1MzQ5ZjYpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfNjE1N2Q5MmExM2U5NDIxNTkzZmE5YTIzODRkODcxNzIuYmluZFBvcHVwKHBvcHVwX2RjM2FhMzkwZmI1YTRkNjZhYTJmODQyOTI4OWU4NDU5KTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2YxNTM4NzdmZjRlYTRjYjdiOGNiMTVmM2M0ZTc0ZWMxID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjc5NTYyNiwtNzkuMzc3NTI5NDAwMDAwMDFdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiI2ZmMDAwMCIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiNmZjAwMDAiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfYzc1YjhiZmExMzIxNDcyYjkzYjM2MWJlY2EyM2E1YWQgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfODljNDkyODBlOGY3NGUwOTk5ZDViMzE4ODNjMTQ3ZTcgPSAkKCc8ZGl2IGlkPSJodG1sXzg5YzQ5MjgwZThmNzRlMDk5OWQ1YjMxODgzYzE0N2U3IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Sb3NlZGFsZSBDbHVzdGVyIDE8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2M3NWI4YmZhMTMyMTQ3MmI5M2IzNjFiZWNhMjNhNWFkLnNldENvbnRlbnQoaHRtbF84OWM0OTI4MGU4Zjc0ZTA5OTlkNWIzMTg4M2MxNDdlNyk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9mMTUzODc3ZmY0ZWE0Y2I3YjhjYjE1ZjNjNGU3NGVjMS5iaW5kUG9wdXAocG9wdXBfYzc1YjhiZmExMzIxNDcyYjkzYjM2MWJlY2EyM2E1YWQpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZDUyOThkNTEwNTQ1NDY0YjkyYjM0YTE0YTcwZDEyOWUgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42Njc5NjcsLTc5LjM2NzY3NTNdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfZjBmMjhiMDljMmIzNDhhM2E3ZjYzNGE4ZDliOTZlM2YgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfNTRmNGE4MDA3ZDQ4NGMxM2IyYjQzZjljNWQ1M2M0YTEgPSAkKCc8ZGl2IGlkPSJodG1sXzU0ZjRhODAwN2Q0ODRjMTNiMmI0M2Y5YzVkNTNjNGExIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5DYWJiYWdldG93bixTdC4gSmFtZXMgVG93biBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2YwZjI4YjA5YzJiMzQ4YTNhN2Y2MzRhOGQ5Yjk2ZTNmLnNldENvbnRlbnQoaHRtbF81NGY0YTgwMDdkNDg0YzEzYjJiNDNmOWM1ZDUzYzRhMSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9kNTI5OGQ1MTA1NDU0NjRiOTJiMzRhMTRhNzBkMTI5ZS5iaW5kUG9wdXAocG9wdXBfZjBmMjhiMDljMmIzNDhhM2E3ZjYzNGE4ZDliOTZlM2YpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfODFiOWU4NTdiYTg0NDYwMmFmYjNlY2YxOTc0NGI0NjUgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NjU4NTk5LC03OS4zODMxNTk5MDAwMDAwMV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICIjMDBiNWViIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzAwYjVlYiIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8yODViOGNkNTEzYzU0OGE4ODlhZWU4OTIwZGIzNDk0ZiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF8xM2RlNTI2MjZjY2E0NDZhOTEwZjhiZTlkMGRlMTFjMyA9ICQoJzxkaXYgaWQ9Imh0bWxfMTNkZTUyNjI2Y2NhNDQ2YTkxMGY4YmU5ZDBkZTExYzMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkNodXJjaCBhbmQgV2VsbGVzbGV5IENsdXN0ZXIgMzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfMjg1YjhjZDUxM2M1NDhhODg5YWVlODkyMGRiMzQ5NGYuc2V0Q29udGVudChodG1sXzEzZGU1MjYyNmNjYTQ0NmE5MTBmOGJlOWQwZGUxMWMzKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzgxYjllODU3YmE4NDQ2MDJhZmIzZWNmMTk3NDRiNDY1LmJpbmRQb3B1cChwb3B1cF8yODViOGNkNTEzYzU0OGE4ODlhZWU4OTIwZGIzNDk0Zik7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9lNjVmNDU3MDUzMDI0YTAwYWNjMWM4NTBhMmVlMzFiMyA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY1NDI1OTksLTc5LjM2MDYzNTldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfN2ExNzFlYWNkNDRjNGM0ODgzYjA1NWE0ZWFiOTg3NzUgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfY2FkZDQ2YWZkNjczNDVmZGI4YzEzZmQ3YzVmNDk1YjMgPSAkKCc8ZGl2IGlkPSJodG1sX2NhZGQ0NmFmZDY3MzQ1ZmRiOGMxM2ZkN2M1ZjQ5NWIzIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5IYXJib3VyZnJvbnQsUmVnZW50IFBhcmsgQ2x1c3RlciAzPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF83YTE3MWVhY2Q0NGM0YzQ4ODNiMDU1YTRlYWI5ODc3NS5zZXRDb250ZW50KGh0bWxfY2FkZDQ2YWZkNjczNDVmZGI4YzEzZmQ3YzVmNDk1YjMpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfZTY1ZjQ1NzA1MzAyNGEwMGFjYzFjODUwYTJlZTMxYjMuYmluZFBvcHVwKHBvcHVwXzdhMTcxZWFjZDQ0YzRjNDg4M2IwNTVhNGVhYjk4Nzc1KTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2QxOWYzYTMyMDI0MzRkZGFiMjhiMDJmMzg3YTI2NTkyID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjU3MTYxOCwtNzkuMzc4OTM3MDk5OTk5OTldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfY2MxM2IyZjBjNWM5NDg4N2FkZWVkZDM3NTkxNTdmM2EgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfZDRlZGE1MzAyNjZhNDZiZjlmM2MzM2U1YWJjNWRkOTQgPSAkKCc8ZGl2IGlkPSJodG1sX2Q0ZWRhNTMwMjY2YTQ2YmY5ZjNjMzNlNWFiYzVkZDk0IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5SeWVyc29uLEdhcmRlbiBEaXN0cmljdCBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2NjMTNiMmYwYzVjOTQ4ODdhZGVlZGQzNzU5MTU3ZjNhLnNldENvbnRlbnQoaHRtbF9kNGVkYTUzMDI2NmE0NmJmOWYzYzMzZTVhYmM1ZGQ5NCk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9kMTlmM2EzMjAyNDM0ZGRhYjI4YjAyZjM4N2EyNjU5Mi5iaW5kUG9wdXAocG9wdXBfY2MxM2IyZjBjNWM5NDg4N2FkZWVkZDM3NTkxNTdmM2EpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMmIxNTBhMmIwYjFjNDJhMzk2NTViY2JiYmI5ZTk4ZTQgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NTE0OTM5LC03OS4zNzU0MTc5XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogIiMwMGI1ZWIiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMDBiNWViIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2ViZTM3MzQyN2NjMjRmZmNhMGZhYmQwMDg4NjMyZGU3KTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2FmZGI0ZGVkOGNhMDRmN2VhODAyNDE2MTRlZmI0NjcyID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzk4MmM1MzAwZjM3MTQ5YTBhOWZlMjM0YjNjNDEwMWE2ID0gJCgnPGRpdiBpZD0iaHRtbF85ODJjNTMwMGYzNzE0OWEwYTlmZTIzNGIzYzQxMDFhNiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+U3QuIEphbWVzIFRvd24gQ2x1c3RlciAzPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF9hZmRiNGRlZDhjYTA0ZjdlYTgwMjQxNjE0ZWZiNDY3Mi5zZXRDb250ZW50KGh0bWxfOTgyYzUzMDBmMzcxNDlhMGE5ZmUyMzRiM2M0MTAxYTYpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfMmIxNTBhMmIwYjFjNDJhMzk2NTViY2JiYmI5ZTk4ZTQuYmluZFBvcHVwKHBvcHVwX2FmZGI0ZGVkOGNhMDRmN2VhODAyNDE2MTRlZmI0NjcyKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2JlNDcxODc3OWJjMDQzZWZhNTIyZmEzOGUxMTBkMTU2ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjQ0NzcwNzk5OTk5OTk2LC03OS4zNzMzMDY0XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogIiMwMGI1ZWIiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMDBiNWViIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2ViZTM3MzQyN2NjMjRmZmNhMGZhYmQwMDg4NjMyZGU3KTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2NiMjk2NWZkZTI0MzRhYmNhODBiZGNhOGIyYzAyNTExID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzA0ZmY3ZTQyZDVhZDRiZmRiMTY3NzBhYzU0NmI0NjcwID0gJCgnPGRpdiBpZD0iaHRtbF8wNGZmN2U0MmQ1YWQ0YmZkYjE2NzcwYWM1NDZiNDY3MCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+QmVyY3p5IFBhcmsgQ2x1c3RlciAzPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF9jYjI5NjVmZGUyNDM0YWJjYTgwYmRjYThiMmMwMjUxMS5zZXRDb250ZW50KGh0bWxfMDRmZjdlNDJkNWFkNGJmZGIxNjc3MGFjNTQ2YjQ2NzApOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfYmU0NzE4Nzc5YmMwNDNlZmE1MjJmYTM4ZTExMGQxNTYuYmluZFBvcHVwKHBvcHVwX2NiMjk2NWZkZTI0MzRhYmNhODBiZGNhOGIyYzAyNTExKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzY4ZmJiODBlYzM1MDQxYzBhMDQ3YjE2YjY0ZjBhMzBlID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjU3OTUyNCwtNzkuMzg3MzgyNl0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICIjMDBiNWViIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzAwYjVlYiIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8xYTVlMmJhN2I1MTQ0Zjk3YmE2YWIwOGNlNjViZjU4MiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9hNzM3ZWE3ZTAxNGE0ODU2OWY1ZTNjYTZkMmM3YzdlOCA9ICQoJzxkaXYgaWQ9Imh0bWxfYTczN2VhN2UwMTRhNDg1NjlmNWUzY2E2ZDJjN2M3ZTgiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkNlbnRyYWwgQmF5IFN0cmVldCBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzFhNWUyYmE3YjUxNDRmOTdiYTZhYjA4Y2U2NWJmNTgyLnNldENvbnRlbnQoaHRtbF9hNzM3ZWE3ZTAxNGE0ODU2OWY1ZTNjYTZkMmM3YzdlOCk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl82OGZiYjgwZWMzNTA0MWMwYTA0N2IxNmI2NGYwYTMwZS5iaW5kUG9wdXAocG9wdXBfMWE1ZTJiYTdiNTE0NGY5N2JhNmFiMDhjZTY1YmY1ODIpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMGU5MjcyOWY0Mjc1NDAzZjk4MGUxMzUyODRiYmM0ZTEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NTA1NzEyMDAwMDAwMSwtNzkuMzg0NTY3NV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICIjMDBiNWViIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzAwYjVlYiIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF82ODFhNGUyNTA3NWY0OGE0YWFiM2VlZWYwMGZiNWQxZiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9iNTZmZGFlZmFkMTU0NzVmOTU2ZDM4ZGIxNzEzZGZjNSA9ICQoJzxkaXYgaWQ9Imh0bWxfYjU2ZmRhZWZhZDE1NDc1Zjk1NmQzOGRiMTcxM2RmYzUiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkFkZWxhaWRlLEtpbmcsUmljaG1vbmQgQ2x1c3RlciAzPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF82ODFhNGUyNTA3NWY0OGE0YWFiM2VlZWYwMGZiNWQxZi5zZXRDb250ZW50KGh0bWxfYjU2ZmRhZWZhZDE1NDc1Zjk1NmQzOGRiMTcxM2RmYzUpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfMGU5MjcyOWY0Mjc1NDAzZjk4MGUxMzUyODRiYmM0ZTEuYmluZFBvcHVwKHBvcHVwXzY4MWE0ZTI1MDc1ZjQ4YTRhYWIzZWVlZjAwZmI1ZDFmKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyX2ZkNDVhMzBiNTIwZjQ1OTJiZjkyMjgwN2U0NTVlOTYwID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjQwODE1NywtNzkuMzgxNzUyMjk5OTk5OTldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfZGZhZWZlYjE5ODA0NDMxMGJlNWFlMTkyZjBkODEzNzkgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfN2YzYzM2NjEyOTJkNDdkZWI0MWNlZWFmNTQ3ODY4MWYgPSAkKCc8ZGl2IGlkPSJodG1sXzdmM2MzNjYxMjkyZDQ3ZGViNDFjZWVhZjU0Nzg2ODFmIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5IYXJib3VyZnJvbnQgRWFzdCxUb3JvbnRvIElzbGFuZHMsVW5pb24gU3RhdGlvbiBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2RmYWVmZWIxOTgwNDQzMTBiZTVhZTE5MmYwZDgxMzc5LnNldENvbnRlbnQoaHRtbF83ZjNjMzY2MTI5MmQ0N2RlYjQxY2VlYWY1NDc4NjgxZik7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9mZDQ1YTMwYjUyMGY0NTkyYmY5MjI4MDdlNDU1ZTk2MC5iaW5kUG9wdXAocG9wdXBfZGZhZWZlYjE5ODA0NDMxMGJlNWFlMTkyZjBkODEzNzkpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMGRlMTFiNGY2MmYyNDY0NDk2MDhlNzVmNjZlMTllZTcgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NDcxNzY4LC03OS4zODE1NzY0MDAwMDAwMV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICIjMDBiNWViIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzAwYjVlYiIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8zMGVjNmUyNDQ4NGY0NWIwOGJiZWI5ZWNhMTA1MDFjZiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9kM2M4YzdmM2RjYzQ0MzBlODMzYWUzNDliNWI2MTg4MyA9ICQoJzxkaXYgaWQ9Imh0bWxfZDNjOGM3ZjNkY2M0NDMwZTgzM2FlMzQ5YjViNjE4ODMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkRlc2lnbiBFeGNoYW5nZSxUb3JvbnRvIERvbWluaW9uIENlbnRyZSBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzMwZWM2ZTI0NDg0ZjQ1YjA4YmJlYjllY2ExMDUwMWNmLnNldENvbnRlbnQoaHRtbF9kM2M4YzdmM2RjYzQ0MzBlODMzYWUzNDliNWI2MTg4Myk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl8wZGUxMWI0ZjYyZjI0NjQ0OTYwOGU3NWY2NmUxOWVlNy5iaW5kUG9wdXAocG9wdXBfMzBlYzZlMjQ0ODRmNDViMDhiYmViOWVjYTEwNTAxY2YpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfNzBmMmQxYmUyYmIyNDRjMzlkOWY4N2VhYjk5ZTM1OWEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NDgxOTg1LC03OS4zNzk4MTY5MDAwMDAwMV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICIjMDBiNWViIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzAwYjVlYiIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF9iZjI4Yzg2MTMyZjA0N2Q0ODQyOWNjMDQ3MThjYjVhYSA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF9hZDkyZjAzMmEyMzk0MzNmOTJlNGQ1NzEzMDA5Y2E1YyA9ICQoJzxkaXYgaWQ9Imh0bWxfYWQ5MmYwMzJhMjM5NDMzZjkyZTRkNTcxMzAwOWNhNWMiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkNvbW1lcmNlIENvdXJ0LFZpY3RvcmlhIEhvdGVsIENsdXN0ZXIgMzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfYmYyOGM4NjEzMmYwNDdkNDg0MjljYzA0NzE4Y2I1YWEuc2V0Q29udGVudChodG1sX2FkOTJmMDMyYTIzOTQzM2Y5MmU0ZDU3MTMwMDljYTVjKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzcwZjJkMWJlMmJiMjQ0YzM5ZDlmODdlYWI5OWUzNTlhLmJpbmRQb3B1cChwb3B1cF9iZjI4Yzg2MTMyZjA0N2Q0ODQyOWNjMDQ3MThjYjVhYSk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl81NzZlNjAxYzhlYjY0MDM0ODczZWM0NTVkNjM4ZTMyZiA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjcxMTY5NDgsLTc5LjQxNjkzNTU5OTk5OTk5XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogIiM4MGZmYjQiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjODBmZmI0IiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2ViZTM3MzQyN2NjMjRmZmNhMGZhYmQwMDg4NjMyZGU3KTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2I1NzhkY2U0OTYzYzQ2MTE5MGE5MjMyYmIwMjkwNThiID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzJkYThkZmM3ODM4NzQ3OGZiNTAzZjJhNThhMmYxZGZmID0gJCgnPGRpdiBpZD0iaHRtbF8yZGE4ZGZjNzgzODc0NzhmYjUwM2YyYTU4YTJmMWRmZiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Um9zZWxhd24gQ2x1c3RlciA0PC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF9iNTc4ZGNlNDk2M2M0NjExOTBhOTIzMmJiMDI5MDU4Yi5zZXRDb250ZW50KGh0bWxfMmRhOGRmYzc4Mzg3NDc4ZmI1MDNmMmE1OGEyZjFkZmYpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfNTc2ZTYwMWM4ZWI2NDAzNDg3M2VjNDU1ZDYzOGUzMmYuYmluZFBvcHVwKHBvcHVwX2I1NzhkY2U0OTYzYzQ2MTE5MGE5MjMyYmIwMjkwNThiKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzc1N2U2OWM4NDg2MjRlMzQ4NDQ4MDcxNWEyYzYzNDg4ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjk2OTQ3NiwtNzkuNDExMzA3MjAwMDAwMDFdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiI2ZmMDAwMCIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiNmZjAwMDAiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfMjQ3YjE3ZmYzN2YwNDM1YTk1MTA5OGNlZjA2MmViOTcgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfYmE2ZDUwNjYyMmViNDBlYThlNDJjOTU3NmIwNWZhMjQgPSAkKCc8ZGl2IGlkPSJodG1sX2JhNmQ1MDY2MjJlYjQwZWE4ZTQyYzk1NzZiMDVmYTI0IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5Gb3Jlc3QgSGlsbCBOb3J0aCxGb3Jlc3QgSGlsbCBXZXN0IENsdXN0ZXIgMTwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfMjQ3YjE3ZmYzN2YwNDM1YTk1MTA5OGNlZjA2MmViOTcuc2V0Q29udGVudChodG1sX2JhNmQ1MDY2MjJlYjQwZWE4ZTQyYzk1NzZiMDVmYTI0KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzc1N2U2OWM4NDg2MjRlMzQ4NDQ4MDcxNWEyYzYzNDg4LmJpbmRQb3B1cChwb3B1cF8yNDdiMTdmZjM3ZjA0MzVhOTUxMDk4Y2VmMDYyZWI5Nyk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9lMDhhNjlmYmRhYjg0Nzc1YmEyNjFiNGZlMzA4MzYyZSA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY3MjcwOTcsLTc5LjQwNTY3ODQwMDAwMDAxXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogIiMwMGI1ZWIiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMDBiNWViIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2ViZTM3MzQyN2NjMjRmZmNhMGZhYmQwMDg4NjMyZGU3KTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzQ2NGViZTJjZWJkODQ1ZTdhNWFlNmQyZDk5YzE4OGQyID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzBkYWQ3MDllYWJmODRhNGJhMzU1NzI4NDc0MzQ1ZDViID0gJCgnPGRpdiBpZD0iaHRtbF8wZGFkNzA5ZWFiZjg0YTRiYTM1NTcyODQ3NDM0NWQ1YiIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+VGhlIEFubmV4LE5vcnRoIE1pZHRvd24sWW9ya3ZpbGxlIENsdXN0ZXIgMzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfNDY0ZWJlMmNlYmQ4NDVlN2E1YWU2ZDJkOTljMTg4ZDIuc2V0Q29udGVudChodG1sXzBkYWQ3MDllYWJmODRhNGJhMzU1NzI4NDc0MzQ1ZDViKTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyX2UwOGE2OWZiZGFiODQ3NzViYTI2MWI0ZmUzMDgzNjJlLmJpbmRQb3B1cChwb3B1cF80NjRlYmUyY2ViZDg0NWU3YTVhZTZkMmQ5OWMxODhkMik7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl9mYzQxMzRlMjYzMjc0NjkwYjY2YTA1YTZjYTVkNDc0MCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY2MjY5NTYsLTc5LjQwMDA0OTNdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfYzYzZTBjMGQ0NzU2NGQyYjgxM2QxZjE5M2YxZGQ1NjEgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfYzQxNWM4NWE3MDc4NGYzODk4MmM1YjJhZDNlMjNiNzkgPSAkKCc8ZGl2IGlkPSJodG1sX2M0MTVjODVhNzA3ODRmMzg5ODJjNWIyYWQzZTIzYjc5IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5IYXJib3JkLFVuaXZlcnNpdHkgb2YgVG9yb250byBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2M2M2UwYzBkNDc1NjRkMmI4MTNkMWYxOTNmMWRkNTYxLnNldENvbnRlbnQoaHRtbF9jNDE1Yzg1YTcwNzg0ZjM4OTgyYzViMmFkM2UyM2I3OSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9mYzQxMzRlMjYzMjc0NjkwYjY2YTA1YTZjYTVkNDc0MC5iaW5kUG9wdXAocG9wdXBfYzYzZTBjMGQ0NzU2NGQyYjgxM2QxZjE5M2YxZGQ1NjEpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfODZjYjQzOTM4ODA2NGJhMGJkMjg5MmNhNDg2N2NkMzYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NTMyMDU3LC03OS40MDAwNDkzXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogIiMwMGI1ZWIiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMDBiNWViIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2ViZTM3MzQyN2NjMjRmZmNhMGZhYmQwMDg4NjMyZGU3KTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwX2UxZjEzM2NiOTRjNzRlZDI5NjAxOTU4NTA0NGIzYjI5ID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzZkM2I1Njk5ZmVhYjRlMjg5OWUxNTBjNDk5YmVkNzI4ID0gJCgnPGRpdiBpZD0iaHRtbF82ZDNiNTY5OWZlYWI0ZTI4OTllMTUwYzQ5OWJlZDcyOCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Q2hpbmF0b3duLEdyYW5nZSBQYXJrLEtlbnNpbmd0b24gTWFya2V0IENsdXN0ZXIgMzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfZTFmMTMzY2I5NGM3NGVkMjk2MDE5NTg1MDQ0YjNiMjkuc2V0Q29udGVudChodG1sXzZkM2I1Njk5ZmVhYjRlMjg5OWUxNTBjNDk5YmVkNzI4KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzg2Y2I0MzkzODgwNjRiYTBiZDI4OTJjYTQ4NjdjZDM2LmJpbmRQb3B1cChwb3B1cF9lMWYxMzNjYjk0Yzc0ZWQyOTYwMTk1ODUwNDRiM2IyOSk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl84OTMyOTg0ZWI1MDk0ZGI5OTJjMjFiNjZmNjNjNGQyZCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjYyODk0NjcsLTc5LjM5NDQxOTldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfNDMxMGUzMTUzOTcyNDAzNzg4NjRmMzVmYWMzMTc0MTMgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfYWQwN2U1NzcxODY5NDhjMGI2YzExYzc1Mzc2NjQyODYgPSAkKCc8ZGl2IGlkPSJodG1sX2FkMDdlNTc3MTg2OTQ4YzBiNmMxMWM3NTM3NjY0Mjg2IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5DTiBUb3dlcixCYXRodXJzdCBRdWF5LElzbGFuZCBhaXJwb3J0LEhhcmJvdXJmcm9udCBXZXN0LEtpbmcgYW5kIFNwYWRpbmEsUmFpbHdheSBMYW5kcyxTb3V0aCBOaWFnYXJhIENsdXN0ZXIgMzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfNDMxMGUzMTUzOTcyNDAzNzg4NjRmMzVmYWMzMTc0MTMuc2V0Q29udGVudChodG1sX2FkMDdlNTc3MTg2OTQ4YzBiNmMxMWM3NTM3NjY0Mjg2KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzg5MzI5ODRlYjUwOTRkYjk5MmMyMWI2NmY2M2M0ZDJkLmJpbmRQb3B1cChwb3B1cF80MzEwZTMxNTM5NzI0MDM3ODg2NGYzNWZhYzMxNzQxMyk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl8xYmJmMDRmNzJmYjI0NTZlYjQ3ZjM4YzY4NmU2M2RiMCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY0NjQzNTIsLTc5LjM3NDg0NTk5OTk5OTk5XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogIiMwMGI1ZWIiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMDBiNWViIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2ViZTM3MzQyN2NjMjRmZmNhMGZhYmQwMDg4NjMyZGU3KTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzQ3MTE0MzJkY2NiZDQwYjU4ZjQ3Nzk3MzhlNDA4MzE5ID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzRiYjY1ZWE5YWE1ZTRlMThhNGQ2M2ViZjVjODQxYTU0ID0gJCgnPGRpdiBpZD0iaHRtbF80YmI2NWVhOWFhNWU0ZTE4YTRkNjNlYmY1Yzg0MWE1NCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+U3RuIEEgUE8gQm94ZXMgMjUgVGhlIEVzcGxhbmFkZSBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzQ3MTE0MzJkY2NiZDQwYjU4ZjQ3Nzk3MzhlNDA4MzE5LnNldENvbnRlbnQoaHRtbF80YmI2NWVhOWFhNWU0ZTE4YTRkNjNlYmY1Yzg0MWE1NCk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl8xYmJmMDRmNzJmYjI0NTZlYjQ3ZjM4YzY4NmU2M2RiMC5iaW5kUG9wdXAocG9wdXBfNDcxMTQzMmRjY2JkNDBiNThmNDc3OTczOGU0MDgzMTkpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMmE5YmI4NTZmNTEwNDllZmI4YTQyYzNkOGMyNmEzODEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NDg0MjkyLC03OS4zODIyODAyXSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogIiMwMGI1ZWIiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMDBiNWViIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2ViZTM3MzQyN2NjMjRmZmNhMGZhYmQwMDg4NjMyZGU3KTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzg0MTBjZTZhMWU0MDRlNWViYTNhNTcyOTQ3MDdjOTIxID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sXzEzYTJlMGFkNzIwYjQ4Nzk5MzIxZDMxYzMwMTc0NmFlID0gJCgnPGRpdiBpZD0iaHRtbF8xM2EyZTBhZDcyMGI0ODc5OTMyMWQzMWMzMDE3NDZhZSIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+Rmlyc3QgQ2FuYWRpYW4gUGxhY2UsVW5kZXJncm91bmQgY2l0eSBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzg0MTBjZTZhMWU0MDRlNWViYTNhNTcyOTQ3MDdjOTIxLnNldENvbnRlbnQoaHRtbF8xM2EyZTBhZDcyMGI0ODc5OTMyMWQzMWMzMDE3NDZhZSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl8yYTliYjg1NmY1MTA0OWVmYjhhNDJjM2Q4YzI2YTM4MS5iaW5kUG9wdXAocG9wdXBfODQxMGNlNmExZTQwNGU1ZWJhM2E1NzI5NDcwN2M5MjEpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZmY1M2MyNTc2YjVhNGUzZDhlZjY5NTFhNDMwNDBkODYgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42Njk1NDIsLTc5LjQyMjU2MzddLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfNzlkMDM5NmNlZDI1NDE1NWE1ZTYyYTdkNzY0MDVkNmUgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfMzFlMGRiODA2NWMwNDMzY2EzOGIxODE2MWFmNmZlMWMgPSAkKCc8ZGl2IGlkPSJodG1sXzMxZTBkYjgwNjVjMDQzM2NhMzhiMTgxNjFhZjZmZTFjIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5DaHJpc3RpZSBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzc5ZDAzOTZjZWQyNTQxNTVhNWU2MmE3ZDc2NDA1ZDZlLnNldENvbnRlbnQoaHRtbF8zMWUwZGI4MDY1YzA0MzNjYTM4YjE4MTYxYWY2ZmUxYyk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9mZjUzYzI1NzZiNWE0ZTNkOGVmNjk1MWE0MzA0MGQ4Ni5iaW5kUG9wdXAocG9wdXBfNzlkMDM5NmNlZDI1NDE1NWE1ZTYyYTdkNzY0MDVkNmUpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYTcyMDE1OGQzMmRkNDdiOThlNDQ1OWRlMGI0MGIxNGEgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NjkwMDUxMDAwMDAwMSwtNzkuNDQyMjU5M10sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICIjMDBiNWViIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzAwYjVlYiIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF9mN2RlMmNiZTM5YmU0MWRiYTYwZDQwZGU3YWNmODNjZCA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF8wZmU5ZmRjOTYyMjI0NjllOTY5ZGQyN2U4NzM3ZmRlYSA9ICQoJzxkaXYgaWQ9Imh0bWxfMGZlOWZkYzk2MjIyNDY5ZTk2OWRkMjdlODczN2ZkZWEiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkRvdmVyY291cnQgVmlsbGFnZSxEdWZmZXJpbiBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2Y3ZGUyY2JlMzliZTQxZGJhNjBkNDBkZTdhY2Y4M2NkLnNldENvbnRlbnQoaHRtbF8wZmU5ZmRjOTYyMjI0NjllOTY5ZGQyN2U4NzM3ZmRlYSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9hNzIwMTU4ZDMyZGQ0N2I5OGU0NDU5ZGUwYjQwYjE0YS5iaW5kUG9wdXAocG9wdXBfZjdkZTJjYmUzOWJlNDFkYmE2MGQ0MGRlN2FjZjgzY2QpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfZTJhMzg3MDg4NDg5NGFiNjhmYjMyMTFhYjEzODhmOTMgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NDc5MjY3MDAwMDAwMDYsLTc5LjQxOTc0OTddLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfYzEwZDM5MWZjOWE3NDhkYWIyMjEzZWNiYjRlOTc5Y2EgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfNjE4Zjg0YjQ5ZmVlNDZkNzlkOWM2ZTQ3NTc3YzU3NTEgPSAkKCc8ZGl2IGlkPSJodG1sXzYxOGY4NGI0OWZlZTQ2ZDc5ZDljNmU0NzU3N2M1NzUxIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5MaXR0bGUgUG9ydHVnYWwsVHJpbml0eSBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwX2MxMGQzOTFmYzlhNzQ4ZGFiMjIxM2VjYmI0ZTk3OWNhLnNldENvbnRlbnQoaHRtbF82MThmODRiNDlmZWU0NmQ3OWQ5YzZlNDc1NzdjNTc1MSk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl9lMmEzODcwODg0ODk0YWI2OGZiMzIxMWFiMTM4OGY5My5iaW5kUG9wdXAocG9wdXBfYzEwZDM5MWZjOWE3NDhkYWIyMjEzZWNiYjRlOTc5Y2EpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMzI3OTUzOTlkOWEwNDQwNmJjMjQ2ZDA5NTcwMjFhNDcgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42MzY4NDcyLC03OS40MjgxOTE0MDAwMDAwMl0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICIjMDBiNWViIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzAwYjVlYiIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8wYjg4ODRmMzIxNDk0ZTBlYjA1NjM2MmE0YmIzYTY1YiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF84YWNiMWM5YmQ5YWI0NTgyOWI4MjI4NGJjNGMwZDY1YiA9ICQoJzxkaXYgaWQ9Imh0bWxfOGFjYjFjOWJkOWFiNDU4MjliODIyODRiYzRjMGQ2NWIiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkJyb2NrdG9uLEV4aGliaXRpb24gUGxhY2UsUGFya2RhbGUgVmlsbGFnZSBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzBiODg4NGYzMjE0OTRlMGViMDU2MzYyYTRiYjNhNjViLnNldENvbnRlbnQoaHRtbF84YWNiMWM5YmQ5YWI0NTgyOWI4MjI4NGJjNGMwZDY1Yik7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl8zMjc5NTM5OWQ5YTA0NDA2YmMyNDZkMDk1NzAyMWE0Ny5iaW5kUG9wdXAocG9wdXBfMGI4ODg0ZjMyMTQ5NGUwZWIwNTYzNjJhNGJiM2E2NWIpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfMmY2YzQ2OTVhZmU5NGU4ZDhmZWY0MzVlOTAxOTk0MmMgPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NjE2MDgzLC03OS40NjQ3NjMyOTk5OTk5OV0sCiAgICAgICAgICAgICAgICB7CiAgImJ1YmJsaW5nTW91c2VFdmVudHMiOiB0cnVlLAogICJjb2xvciI6ICIjMDBiNWViIiwKICAiZGFzaEFycmF5IjogbnVsbCwKICAiZGFzaE9mZnNldCI6IG51bGwsCiAgImZpbGwiOiB0cnVlLAogICJmaWxsQ29sb3IiOiAiIzAwYjVlYiIsCiAgImZpbGxPcGFjaXR5IjogMC43LAogICJmaWxsUnVsZSI6ICJldmVub2RkIiwKICAibGluZUNhcCI6ICJyb3VuZCIsCiAgImxpbmVKb2luIjogInJvdW5kIiwKICAib3BhY2l0eSI6IDEuMCwKICAicmFkaXVzIjogNSwKICAic3Ryb2tlIjogdHJ1ZSwKICAid2VpZ2h0IjogMwp9CiAgICAgICAgICAgICAgICApLmFkZFRvKG1hcF9lYmUzNzM0MjdjYzI0ZmZjYTBmYWJkMDA4ODYzMmRlNyk7CiAgICAgICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBwb3B1cF8wOTNiYzk1ZjdmNWU0ZDQ2OTIxOWY5ZGUwZGU4MWZmYiA9IEwucG9wdXAoe21heFdpZHRoOiAnMzAwJ30pOwoKICAgICAgICAgICAgCiAgICAgICAgICAgICAgICB2YXIgaHRtbF8xMzQyNmYyNDUzMzk0YzQwYjkwZWFmYjIxZjFmYjNlMSA9ICQoJzxkaXYgaWQ9Imh0bWxfMTM0MjZmMjQ1MzM5NGM0MGI5MGVhZmIyMWYxZmIzZTEiIHN0eWxlPSJ3aWR0aDogMTAwLjAlOyBoZWlnaHQ6IDEwMC4wJTsiPkhpZ2ggUGFyayxUaGUgSnVuY3Rpb24gU291dGggQ2x1c3RlciAzPC9kaXY+JylbMF07CiAgICAgICAgICAgICAgICBwb3B1cF8wOTNiYzk1ZjdmNWU0ZDQ2OTIxOWY5ZGUwZGU4MWZmYi5zZXRDb250ZW50KGh0bWxfMTM0MjZmMjQ1MzM5NGM0MGI5MGVhZmIyMWYxZmIzZTEpOwogICAgICAgICAgICAKCiAgICAgICAgICAgIGNpcmNsZV9tYXJrZXJfMmY2YzQ2OTVhZmU5NGU4ZDhmZWY0MzVlOTAxOTk0MmMuYmluZFBvcHVwKHBvcHVwXzA5M2JjOTVmN2Y1ZTRkNDY5MjE5ZjlkZTBkZTgxZmZiKTsKCiAgICAgICAgICAgIAogICAgICAgIAogICAgCiAgICAgICAgICAgIHZhciBjaXJjbGVfbWFya2VyXzg3OTE4NTUyNjM1ZDRjYzRiOGRjOTYzZmY5YzkyZjE4ID0gTC5jaXJjbGVNYXJrZXIoCiAgICAgICAgICAgICAgICBbNDMuNjQ4OTU5NywtNzkuNDU2MzI1XSwKICAgICAgICAgICAgICAgIHsKICAiYnViYmxpbmdNb3VzZUV2ZW50cyI6IHRydWUsCiAgImNvbG9yIjogIiMwMGI1ZWIiLAogICJkYXNoQXJyYXkiOiBudWxsLAogICJkYXNoT2Zmc2V0IjogbnVsbCwKICAiZmlsbCI6IHRydWUsCiAgImZpbGxDb2xvciI6ICIjMDBiNWViIiwKICAiZmlsbE9wYWNpdHkiOiAwLjcsCiAgImZpbGxSdWxlIjogImV2ZW5vZGQiLAogICJsaW5lQ2FwIjogInJvdW5kIiwKICAibGluZUpvaW4iOiAicm91bmQiLAogICJvcGFjaXR5IjogMS4wLAogICJyYWRpdXMiOiA1LAogICJzdHJva2UiOiB0cnVlLAogICJ3ZWlnaHQiOiAzCn0KICAgICAgICAgICAgICAgICkuYWRkVG8obWFwX2ViZTM3MzQyN2NjMjRmZmNhMGZhYmQwMDg4NjMyZGU3KTsKICAgICAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIHBvcHVwXzlhOGI5NDNiN2YwZDQ4ZGU4YzAzMTNlYjA2ZmZjOTM0ID0gTC5wb3B1cCh7bWF4V2lkdGg6ICczMDAnfSk7CgogICAgICAgICAgICAKICAgICAgICAgICAgICAgIHZhciBodG1sX2RiYWRiMmMxOWI1NTRmMWM5YjZlZjYyMDk2NThhNmU0ID0gJCgnPGRpdiBpZD0iaHRtbF9kYmFkYjJjMTliNTU0ZjFjOWI2ZWY2MjA5NjU4YTZlNCIgc3R5bGU9IndpZHRoOiAxMDAuMCU7IGhlaWdodDogMTAwLjAlOyI+UGFya2RhbGUsUm9uY2VzdmFsbGVzIENsdXN0ZXIgMzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfOWE4Yjk0M2I3ZjBkNDhkZThjMDMxM2ViMDZmZmM5MzQuc2V0Q29udGVudChodG1sX2RiYWRiMmMxOWI1NTRmMWM5YjZlZjYyMDk2NThhNmU0KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyXzg3OTE4NTUyNjM1ZDRjYzRiOGRjOTYzZmY5YzkyZjE4LmJpbmRQb3B1cChwb3B1cF85YThiOTQzYjdmMGQ0OGRlOGMwMzEzZWIwNmZmYzkzNCk7CgogICAgICAgICAgICAKICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgY2lyY2xlX21hcmtlcl82Y2QyODBmMGY4ODE0MWVkOWE4YzUzOTk1MzRiZmI1NCA9IEwuY2lyY2xlTWFya2VyKAogICAgICAgICAgICAgICAgWzQzLjY1MTU3MDYsLTc5LjQ4NDQ0OTldLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfM2NlNzRhZGFjZWM5NDRhNjk4OWE3NGFlYWYxMTNmNDEgPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfMGExYTdlMGQ3MTgwNGVjMGE4Nzg1Mjc0Zjg1MDAwOGMgPSAkKCc8ZGl2IGlkPSJodG1sXzBhMWE3ZTBkNzE4MDRlYzBhODc4NTI3NGY4NTAwMDhjIiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5SdW5ueW1lZGUsU3dhbnNlYSBDbHVzdGVyIDM8L2Rpdj4nKVswXTsKICAgICAgICAgICAgICAgIHBvcHVwXzNjZTc0YWRhY2VjOTQ0YTY5ODlhNzRhZWFmMTEzZjQxLnNldENvbnRlbnQoaHRtbF8wYTFhN2UwZDcxODA0ZWMwYTg3ODUyNzRmODUwMDA4Yyk7CiAgICAgICAgICAgIAoKICAgICAgICAgICAgY2lyY2xlX21hcmtlcl82Y2QyODBmMGY4ODE0MWVkOWE4YzUzOTk1MzRiZmI1NC5iaW5kUG9wdXAocG9wdXBfM2NlNzRhZGFjZWM5NDRhNjk4OWE3NGFlYWYxMTNmNDEpOwoKICAgICAgICAgICAgCiAgICAgICAgCiAgICAKICAgICAgICAgICAgdmFyIGNpcmNsZV9tYXJrZXJfYzczODE0MDQ2Y2RiNDc2OGE1Mzc2ZDdmNTgyY2I3NzggPSBMLmNpcmNsZU1hcmtlcigKICAgICAgICAgICAgICAgIFs0My42NjI3NDM5LC03OS4zMjE1NThdLAogICAgICAgICAgICAgICAgewogICJidWJibGluZ01vdXNlRXZlbnRzIjogdHJ1ZSwKICAiY29sb3IiOiAiIzAwYjVlYiIsCiAgImRhc2hBcnJheSI6IG51bGwsCiAgImRhc2hPZmZzZXQiOiBudWxsLAogICJmaWxsIjogdHJ1ZSwKICAiZmlsbENvbG9yIjogIiMwMGI1ZWIiLAogICJmaWxsT3BhY2l0eSI6IDAuNywKICAiZmlsbFJ1bGUiOiAiZXZlbm9kZCIsCiAgImxpbmVDYXAiOiAicm91bmQiLAogICJsaW5lSm9pbiI6ICJyb3VuZCIsCiAgIm9wYWNpdHkiOiAxLjAsCiAgInJhZGl1cyI6IDUsCiAgInN0cm9rZSI6IHRydWUsCiAgIndlaWdodCI6IDMKfQogICAgICAgICAgICAgICAgKS5hZGRUbyhtYXBfZWJlMzczNDI3Y2MyNGZmY2EwZmFiZDAwODg2MzJkZTcpOwogICAgICAgICAgICAKICAgIAogICAgICAgICAgICB2YXIgcG9wdXBfZmQ4NGNkMTdlMWI5NGIwYjk4MDZiYjMxMTkxMWFkNDggPSBMLnBvcHVwKHttYXhXaWR0aDogJzMwMCd9KTsKCiAgICAgICAgICAgIAogICAgICAgICAgICAgICAgdmFyIGh0bWxfNjY2OGVkMTIxNzI2NDk0OWFiMzY3MGNmMmJkNWVjMzUgPSAkKCc8ZGl2IGlkPSJodG1sXzY2NjhlZDEyMTcyNjQ5NDlhYjM2NzBjZjJiZDVlYzM1IiBzdHlsZT0id2lkdGg6IDEwMC4wJTsgaGVpZ2h0OiAxMDAuMCU7Ij5CdXNpbmVzcyBSZXBseSBNYWlsIFByb2Nlc3NpbmcgQ2VudHJlIDk2OSBFYXN0ZXJuIENsdXN0ZXIgMzwvZGl2PicpWzBdOwogICAgICAgICAgICAgICAgcG9wdXBfZmQ4NGNkMTdlMWI5NGIwYjk4MDZiYjMxMTkxMWFkNDguc2V0Q29udGVudChodG1sXzY2NjhlZDEyMTcyNjQ5NDlhYjM2NzBjZjJiZDVlYzM1KTsKICAgICAgICAgICAgCgogICAgICAgICAgICBjaXJjbGVfbWFya2VyX2M3MzgxNDA0NmNkYjQ3NjhhNTM3NmQ3ZjU4MmNiNzc4LmJpbmRQb3B1cChwb3B1cF9mZDg0Y2QxN2UxYjk0YjBiOTgwNmJiMzExOTExYWQ0OCk7CgogICAgICAgICAgICAKICAgICAgICAKPC9zY3JpcHQ+" style="position:absolute;width:100%;height:100%;left:0;top:0;border:none !important;" allowfullscreen webkitallowfullscreen mozallowfullscreen></iframe></div></div>


