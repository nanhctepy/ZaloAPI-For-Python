![Logo](https://i.imgur.com/CMnA5Sh.jpeg "Logo")

## ``zlapi`` - Zalo API (UnOffical) for Python CopyRight Lê Ngọc Anh
A powerful and efficient library to interact with Zalo Website. 
This is *not* an official API, Zalo has that `over here <https://developers.zalo.me/docs>`__ for chat bots. This library differs by using a normal Zalo account instead (More flexible).

``zlapi`` currently support:

- Custom style for message.
- Sending many types of messages, with files, stickers, mentions, etc.
- Fetching messages, threads and users info.
- Creating groups, setting the group, creating polls, etc.
- Listening for, an reacting to messages and other events in real-time.
- And there are many other things.
- ``async``/``await`` (Coming Soon).

Essentially, everything you need to make an amazing Zalo Bot!

### Language

- Language is support soon. Thanks!!!

### What is ``zlapi``?

A powerful and efficient library to interact with Zalo Website. 
This is *not* an official API, Zalo has that [over here](https://developers.zalo.me/docs) for chat bots. This library differs by using a normal Zalo account instead (More flexible).

``zlapi`` currently support:

- Custom style for message.
- Sending many types of messages, with files, stickers, mentions, etc.
- Fetching messages, threads and users info.
- Creating groups, setting the group, creating polls, etc.
- Listening for, an reacting to messages and other events in real-time.
- And there are many other things.
- ``async``/``await`` (Updated).

Essentially, everything you need to make an amazing Zalo Bot!


### Caveats

``zlapi`` works by imitating what the browser does, and thereby tricking Zalo into thinking it's accessing the website normally.

However, there's a catch! **Using this library may not comply with Zalo's Terms Of Service**, so be! We are not responsible if your account gets banned or disabled!


### What's New?

This is an updated version for ``zlapi`` to improve features and fix bugs (v1.0.2)

**Improvements**

- Various typo fixes and doc improvements.
- Add simple code style for module. Like ``telebot``, ``discord``, ...
- Add ``async``/``await`` for module.
- Add ``websocket`` type to listen function.
- Add ``run forever`` for listen function.
- Add send ``gif``, ``video``, ``voice``, ``business card``, ``multi image``.
- Add ``Block/Unblock`` members when kicked out of group.
- Add ``Pin/Unpin`` message in group.
- Add ``On Event`` function to handle group and user events.
- Add ``Parse Mode`` for [Message](#messages).

</br>

## Installation

```bash
https://github.com/nanhctepy/ZaloAPI-For-Python
```

If you don't have zlapi, [this guide](https://github.com/nanhctepy/ZaloAPI-For-Python) can guide you through the process. This is Github to Downloads

You can also install directly from source, provided you have ``pip>=19.0``:

```bash
pip install git+https://github.com/nanhctepy/ZaloAPI-For-Python
```

</br>

## How to get IMEI and Cookies?

### Download Extension

- [Click Here](https://drive.google.com/file/d/18_-8ruYOVa89JkHdr3muGj3kGWxwt6mc/view?usp=drive_link) to download the extension support getting IMEI & Cookies more conveniently.

### Extension Usage Tutorial

1. Enable the extension downloaded above.
2. Go to [https://chat.zalo.me](https://chat.zalo.me), Sign in to your account.
3. After successfully logging in, go back to extension and get IMEI, Cookies.

> [!TIP]
If you have opened the website ``chat.zalo.me`` but the extension does not have IMEI & Cookies, please click ``Refresh Page``.

#### Windows

[![](https://previews.jumpshare.com/thumb/815bc01b796dd6f1733c957c5af19493968eb06ccf48b6a5036cf7916c0a83965899fb056fe88c29f2bcb2f9f0f5ed5832801eede43aa22e94d5c7bc545ef9448bfbfd14044e807555841b406fdf069aa3acda441ff8675390fa0ff601ff0bcd)](https://jumpshare.com/embed/8SjFyd3EQlCMx1V7N1UQ)

</br>

#### Android

> - Use ``kiwibrowser`` instead of ``chrome`` to be able to use the extension.
> - If you are redirect when accessing ``https://chat.zalo.me``. [Watch this video](https://jumpshare.com/embed/l3LLjAWSAR8KQxvh9dzz)

[![](https://previews.jumpshare.com/thumb/815bc01b796dd6f1733c957c5af194938966297dbb29c75d038ac93e0691be4c741e5e2cbb689c41b8dfebde4ded3316844e23ec82425f377c248f1a57861470e76e9fe268bdf0803c7c14a61c9dc50769f92efb3803e5ae68c46d260d3407db)](https://jumpshare.com/embed/n56jtVQ7pwZDfR5ZtPft)

</br>

## Basic Usage

### Login Account Using Cookies
Example Usage
-------------

.. code:: py

    from zlapi import ZaloAPI
    from zlapi.models import *
    
    imei = "<imei>"
    cookies = "<cookies>"
    client = ZaloAPI("<phone>", "<password>", imei=imei, session_cookies=cookies)
    client.send(Message(text="Hi Myself!"), thread_id=client.uid, thread_type=ThreadType.USER)

More examples are available `here <https://github.com/nanhctepy/ZaloAPI-For-Python>`__.

This project is a relocation
============================

This project is a project to be relocated from ``zaloapi`` because this module has been removed from Pypi and the reason is unknown.



## Example

See [examples](examples) folder to learn more about ``zlapi``.

</br>

- Thanks for support:
  - [Lê Quốc Việt](https://www.facebook.com/profile.php?id=100094031375075) for Source Code zlapi.

## Contact For Help
- <img src="https://raw.githubusercontent.com/dheereshagrwal/colored-icons/master/public/logos/facebook/facebook.svg" alt="Facebook Icon" width=20 height=15/> Facebook: [Lê Ngọc Anh](https://www.facebook.com/nanh.nlmn/)
