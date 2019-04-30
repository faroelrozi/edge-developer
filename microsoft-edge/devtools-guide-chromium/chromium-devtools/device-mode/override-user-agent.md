project_path: /web/tools/_project.yaml
book_path: /web/tools/_book.yaml
description: Open the Network conditions tab, disable "Select automatically", and choose from the list or enter a custom string.

{# wf_updated_on: 2018-12-18 #}
{# wf_published_on: 2018-12-14 #}
{# wf_blink_components: Platform>DevTools #}

# Override The User Agent String From Microsoft Edge DevTools {: .page-title }

{% include "web/_shared/contributors/kaycebasques.html" %}

[ua]: https://developer.mozilla.org/en-US/docs/Glossary/User_agent

To override the [user agent][ua]{: .external } string from Microsoft Edge DevTools:

1. Press <kbd>Command</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> (Mac) or
   <kbd>Control</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> (Windows, Linux, Microsoft Edge OS) to open the **Command Menu**.

     <figure>
       <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/images/shared/command-menu.msft.png"
            alt="The Command Menu."/>
       <figcaption>
         <b>Figure 1</b>. The Command Menu
       </figcaption>
     </figure>

1. Type `network conditions`, select **Show Network conditions**, and press <kbd>Enter</kbd>
   to open the **Network conditions** tab.
1. In the **User agent** section disable the **Select automatically** checkbox.

     <figure>
       <img src="/microsoft-edge/devtools-guide-chromium/chromium-devtools/device-mode/imgs/user-agent.msft.png"
            alt="Disabling 'Select automatically'."/>
       <figcaption>
         <b>Figure 2</b>. Disabling <b>Select automatically</b>
       </figcaption>
     </figure>

1. Select a user agent string from the list, or enter your own custom string.

## Feedback {: #feedback .hide-from-toc }

{% include "web/_shared/helpful.html" %}
