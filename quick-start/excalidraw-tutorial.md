---
description: Discover what you can do with Agua!
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Sentry: Tutorial

In this tutorial, we'll walk through [Sentry's](https://sentry.io/) codebase's components and dependency structure.

***



{% tabs %}
{% tab title="Sentry" %}
<figure><img src="../.gitbook/assets/Sentry-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}



## Basic Setup

Retrieve all necessary assets from [Sentry's GitHub](https://github.com/getsentry) and start using Agua.

***



### 1. Codebase setup[​](https://docs.agua.dev/installation#1-codebase-setup) <a href="#id-1-codebase-setup" id="id-1-codebase-setup"></a>

> Fork and clone the GitHub repository locally:

```
https://github.com/getsentry/sentry.git
```



### 2. Agua setup[​](https://docs.agua.dev/installation#2-agua-setup) <a href="#id-2-agua-setup" id="id-2-agua-setup"></a>



#### 2.1 Sign Up

> Open Agua's [web editor](https://auth.agua.app/signin/):

```
https://auth.agua.app/signin/
```

> Register with your [Google Account](https://www.google.com/account/about/).&#x20;

{% tabs %}
{% tab title="Sign Up" %}
<figure><img src="../.gitbook/assets/Agua-Sign-Up-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
Agua is currently only supported in [**Google Chrome**](https://www.google.com/intl/es-419/chrome/).
{% endhint %}



#### 2.2. Terminal installation[​](https://docs.agua.dev/installation#21-terminal-installation) <a href="#id-21-terminal-installation" id="id-21-terminal-installation"></a>

> Go to the root folder of the Sentry repository and run:

```
npx --yes agua-server
```

{% tabs %}
{% tab title="Terminal installation" %}
<figure><img src="../.gitbook/assets/Agua-Install-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
Agua is currently only supported in [**Node.js 18**](https://nodejs.org/en/download).
{% endhint %}



#### 2.3. Welcome menu[​](https://docs.agua.dev/installation#22-welcome-menu) <a href="#id-22-welcome-menu" id="id-22-welcome-menu"></a>

> Select the \[**Open folder]** button and connect your local GitHub repository with Agua.

{% tabs %}
{% tab title="Welcome menu​" %}
<figure><img src="../.gitbook/assets/Agua-Menu-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

> You can also access:
>
> * Our Documentation \[[_Read the docs_](https://docs.agua.dev/)].
> * Out Tutorials \[[_Watch our courses_](https://www.youtube.com/@aguafordevs)].
> * Our WhatsApp contact \[[_Contact us for support_](https://wa.me/12396883277)].
> * Our one-to-one onboarding \[[_Book a call with our founders_](https://agua.tools/meetings/developers/onboarding)].



#### 2.4. Locate your Folder <a href="#id-23-folder-selection" id="id-23-folder-selection"></a>

> Navigate through your file manager and select your repository's folder.

{% tabs %}
{% tab title="Locate your Folder" %}
<figure><img src="../.gitbook/assets/Agua-Finder-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}



#### 2.5. Grant Files permissions <a href="#id-23-folder-selection" id="id-23-folder-selection"></a>

> Allow our web app to securely access and edit files in the selected folder.

{% tabs %}
{% tab title="Locate your Folder" %}
<figure><img src="../.gitbook/assets/Agua-Edit-Files-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

{% hint style="success" %}
For the sake of your privacy and the integrity of your files, access permissions to your code must be renewed each time the project tab is refreshed.
{% endhint %}



#### 2.6. Welcome to Agua <a href="#id-23-folder-selection" id="id-23-folder-selection"></a>

{% tabs %}
{% tab title="Welcome to Agua" %}
<figure><img src="../.gitbook/assets/Component-List-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}



## Platform Tour[​](https://docs.agua.dev/installation#3-platform-tour) <a href="#id-3-platform-tour" id="id-3-platform-tour"></a>

***



### A. [Components Tree](../basics/components-tree.md)

> Visualize component hierarchies and locate Sentry's files.

{% tabs %}
{% tab title="Components tree" %}
<figure><img src="../.gitbook/assets/Component-Tree-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}



### B. [Dependencies Tree](../basics/dependencies-tree.md)

> Visualize component dependencies.

{% tabs %}
{% tab title="Dependencies Tree" %}
<figure><img src="../.gitbook/assets/Dependency-Tree-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}



### C. [Component Preview](../basics/component-preview.md)

> Visualize each of Sentry's components and their props.

{% tabs %}
{% tab title="Component Preview" %}
<figure><img src="../.gitbook/assets/Component-Preview-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}



### D. [Integrated IDE](../basics/integrated-ide.md)

> Edit Sentry's code in our web-based VS Code.

{% tabs %}
{% tab title="Welcome to Agua" %}
<figure><img src="../.gitbook/assets/Integrated-IDE-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

