# Filter Unique Requests

Burp extender

**ちょっと色々改良中です。**

---

- `filter-graphql-request.py`
    - GraphQL専用
- `filter-unique-requests.py`
    - 全ての通信において1回のみハイライトしたい...
    - バグります

### Manual Installation

1. Clone this repository to your machine
1. Go to **Extender > Extensions** tab
1. Click on the **Add**
1. On the window, browse the location of **filter-unique-requests.py** and click the **Next**

### Usage

1. Go to **Extender > Extensions** tab
1. Check **Filter Unique Requests**
1. Go to **Proxy > HTTP history** tab
1. Click on the **Filter**
1. Check **Show only highlighted items**

### Reference

* [Filter OPTIONS Method](https://github.com/capt-meelo/filter-options-method)
* [Hiding OPTIONS - An Adventure in Dealing with Burp Proxy in an Extension](https://parsiya.net/blog/2019-04-06-hiding-options-an-adventure-in-dealing-with-burp-proxy-in-an-extension/)