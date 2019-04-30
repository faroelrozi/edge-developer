project_path: /web/tools/_project.yaml
book_path: /web/tools/_book.yaml
description: All of the ways that you can open Microsoft Edge DevTools.

{# wf_updated_on: 2018-12-14 #}
{# wf_published_on: 2018-12-14 #}
{# wf_blink_components: Platform>DevTools #}

# Open Microsoft Edge DevTools {: .page-title }

{% include "web/_shared/contributors/kaycebasques.html" %}

There are many ways to open Microsoft Edge DevTools, because different users want fast access to different
parts of the DevTools UI.

## Open the Elements panel to inspect the DOM or CSS {: #elements }

When you want to inspect a DOM node's styles or attributes, right-click the element
and select **Inspect**.

<figure>
  <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/images/inspect.msft.png"
       alt="The Inspect option"/>
  <figcaption>
    <b>Figure 1</b>. The <b>Inspect</b> option
  </figcaption>
</figure>

Or press <kbd>Command</kbd>+<kbd>Option</kbd>+<kbd>C</kbd> (Mac) or
<kbd>Control</kbd>+<kbd>Shift</kbd>+<kbd>C</kbd> (Windows, Linux, Microsoft Edge OS).

See [Get Started With Viewing And Changing CSS](/microsoft-edge/devtools-guide-chromium/chromium-devtools/css/).

## Open the Console panel to view logged messages or run JavaScript {: #console }

Press <kbd>Command</kbd>+<kbd>Option</kbd>+<kbd>J</kbd>
(Mac) or <kbd>Control</kbd>+<kbd>Shift</kbd>+<kbd>J</kbd> (Windows, Linux, Microsoft Edge OS) to
jump straight into the **Console** panel.

See [Get Started With The Console](/microsoft-edge/devtools-guide-chromium/chromium-devtools/console/get-started).

## Open the last panel you had open {: #last }

Press <kbd>Command</kbd>+<kbd>Option</kbd>+<kbd>I</kbd> (Mac) or
<kbd>Control</kbd>+<kbd>Shift</kbd>+<kbd>I</kbd>.

## Open DevTools from Microsoft Edge's main menu {: #chrome }

[main]: /microsoft-edge/devtools-guide-chromium/chromium-devtools/images/shared/main-menu.png

Click **Customize and control Microsoft Edge** ![Customize and control Microsoft Edge][main]{: .inline-icon }
and then select **More Tools** > **Developer Tools**.

<figure>
  <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/images/open-from-main.msft.png"
       alt="Opening DevTools from Microsoft Edge's main menu."/>
  <figcaption>
    <b>Figure 2</b>. Opening DevTools from Microsoft Edge's main menu
  </figcaption>
</figure>

## Auto-open DevTools on every new tab {: #auto }

Open Microsoft Edge from the command line and pass the `--auto-open-devtools-for-tabs` flag.

Mac:

    /Applications/Microsoft\ Edge\ MSEdge.app/Contents/MacOS/Microsoft\ Edge\ MSEdge --auto-open-devtools-for-tabs

## Feedback {: #feedback .hide-from-toc }

{% include "web/_shared/helpful.html" %}
