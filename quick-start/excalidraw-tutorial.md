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

# Excalidraw: Tutorial

In this tutorial, we'll walk through [Excalidraw's](https://excalidraw.com/) codebase's components and dependency structure.

***



{% tabs %}
{% tab title="Excalidraw" %}
<figure><img src="../.gitbook/assets/Sentry-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}



## Basic Setup

Retrieve all necessary assets from [Excalidraw's GitHub](https://github.com/excalidraw/excalidraw) and start using Agua.

***



### 1. Codebase setup[​](https://docs.agua.dev/installation#1-codebase-setup) <a href="#id-1-codebase-setup" id="id-1-codebase-setup"></a>

> Fork and clone the GitHub repository locally:

```
https://github.com/excalidraw/excalidraw.git
```



### 2. Agua setup[​](https://docs.agua.dev/installation#2-agua-setup) <a href="#id-2-agua-setup" id="id-2-agua-setup"></a>



#### 2.1 Sign Up

> Open Agua's [web editor](https://auth.agua.app/signin/):
>
> Register with your Google Account.&#x20;

```
https://auth.agua.app/signin/
```

{% tabs %}
{% tab title="Sign Up" %}
<figure><img src="../.gitbook/assets/Agua-Sign-Up-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
Agua is currently only supported in [**Google Chrome**](https://www.google.com/intl/es-419/chrome/).
{% endhint %}



#### 2.2. Terminal installation[​](https://docs.agua.dev/installation#21-terminal-installation) <a href="#id-21-terminal-installation" id="id-21-terminal-installation"></a>

> Go to the root folder of the Excalidraw repository and run:

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



#### 2.3. Welcome to Agua <a href="#id-23-folder-selection" id="id-23-folder-selection"></a>

{% tabs %}
{% tab title="Welcome to Agua" %}
<figure><img src="../.gitbook/assets/Component-List-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}



## Platform Tour[​](https://docs.agua.dev/installation#3-platform-tour) <a href="#id-3-platform-tour" id="id-3-platform-tour"></a>

***

### A. [UI Quick Access](../basics/ui-quick-access.md)

> Click and access an element's file, component structure, and dependencies.

{% tabs %}
{% tab title="Components tree" %}
<figure><img src="../.gitbook/assets/Component-Tree-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}



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



### D. [Integrated IDE](broken-reference)

> Edit Sentry's code in our web-based VS Code.

{% tabs %}
{% tab title="Welcome to Agua" %}
<figure><img src="../.gitbook/assets/Integrated-IDE-Reduced.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

