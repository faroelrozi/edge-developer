project_path: /web/tools/_project.yaml
book_path: /web/tools/_book.yaml
description: How to view Cache data from the Application panel of Microsoft Edge DevTools.

{# wf_updated_on: 2019-03-25 #}
{# wf_published_on: 2019-03-25 #}
{# wf_blink_components: Platform>DevTools #}

# View Cache Data With Microsoft Edge DevTools {: .page-title }

{% include "web/_shared/contributors/kaycebasques.html" %}

[MDN]: https://developer.mozilla.org/en-US/docs/Web/API/Cache

This guide shows you how to use [Microsoft Edge DevTools](/microsoft-edge/devtools-guide-chromium/chromium-devtools) to inspect
[Cache][MDN]{: .external } data.

[HTTP]: https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching
[log]: /microsoft-edge/devtools-guide-chromium/chromium-devtools/network/#load

If you're trying to inspect [HTTP cache][HTTP]{: .external } data, this is not the guide you want.
The **Size** column of the **Network Log** has the information you're looking for. See [Log network activity][log].

## View cache data {: #view }

1. Click the **Sources** tab to open the **Sources** panel. The **Manifest** pane usually opens
   by default.

     <figure>
       <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/storage/imgs/manifest.msft.png"
            alt="The Manifest pane."/>
       <figcaption>
         <b>Figure 1</b>. The Manifest pane.
       </figcaption>
     </figure>

1. Expand the **Cache Storage** section to view available caches.

     <figure>
       <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/storage/imgs/cache.msft.png"
            alt="Available caches."/>
       <figcaption>
         <b>Figure 2</b>. Available caches.
       </figcaption>
     </figure>

1. Click a cache to view its contents.

     <figure>
       <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/storage/imgs/cacheview.msft.png"
            alt="Viewing a cache's contents."/>
       <figcaption>
         <b>Figure 3</b>. Viewing the <b>airhorner-0.6.11</b> cache.
       </figcaption>
     </figure>

1. Click a resource to view its HTTP headers in the section below the table.

     <figure>
       <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/storage/imgs/viewcacheresource.msft.png"
            alt="Viewing a resource's HTTP headers."/>
       <figcaption>
         <b>Figure 4</b>. Viewing the HTTP headers of the <b>/index.html</b> resource.
       </figcaption>
     </figure>

1. Click **Preview** to view a resource's content.

     <figure>
       <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/storage/imgs/cachecontent.msft.png"
            alt="Viewing a resource's content."/>
       <figcaption>
         <b>Figure 5</b>. Viewing the content of the <b>/scripts.comlink.global.js</b> resource.
       </figcaption>
     </figure>


## Refresh a resource {: #refresh }

1. [View a cache's data](#view).
1. Click the resource that you want to refresh. DevTools highlights it blue to indicate that it's selected.

     <figure>
       <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/storage/imgs/cacheselected.msft.png"
            alt="Selecting a resource."/>
       <figcaption>
         <b>Figure 6</b>. Selecting the <b>/styles/main.css</b> resource.
       </figcaption>
     </figure>

1. Click **Refresh** ![Refresh](/microsoft-edge/devtools-guide-chromium/chromium-devtools/images/shared/reload.png){: .inline-icon }.

## Filter resources {: #filter }

1. [View a cache's data](#view).
1. Use the **Filter by Path** text box to filter out any resources that do not match the path that you provide.

     <figure>
       <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/storage/imgs/cachefilter.msft.png"
            alt="Filtering out resources that do not match the specified path."/>
       <figcaption>
         <b>Figure 7</b>. Filtering out resources that do not match the <code>/script</code> path.
       </figcaption>
     </figure>

## Delete a resource {: #deleteresource }

1. [View a cache's data](#view).
1. Click the resource that you want to delete. DevTools highlights it blue to indicate that it's selected.

     <figure>
       <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/storage/imgs/cacheselected.msft.png"
            alt="Selecting a resource."/>
       <figcaption>
         <b>Figure 8</b>. Selecting the <b>/styles/main.css</b> resource.
       </figcaption>
     </figure>

1. Click **Delete Selected** ![Delete Selected](/microsoft-edge/devtools-guide-chromium/chromium-devtools/images/shared/delete.png){: .inline-icon }.

## Delete all cache data {: #deletecache }

1. Open **Application** > **Clear Storage**.
1. Make sure that the **Cache Storage** checkbox is enabled.

     <figure>
       <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/storage/imgs/cachecheckbox.msft.png"
            alt="The Cache Storage checkbox."/>
       <figcaption>
         <b>Figure 9</b>. The <b>Cache Storage</b> checkbox.
       </figcaption>
     </figure>

1. Click **Clear site data**.

     <figure>
       <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/storage/imgs/cacheclearsite.msft.png"
            alt="The Clear Site Data button."/>
       <figcaption>
         <b>Figure 10</b>. The <b>Clear Site Data</b> button.
       </figcaption>
     </figure>

## Feedback {: #feedback }

{% include "web/_shared/helpful.html" %}
