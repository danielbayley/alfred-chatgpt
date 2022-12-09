<img src="logo.svg" width="18%" align="right">

_[ChatGPT]_ + _[Alfred]_
=========================
Query _[OpenAI]_ [ChatGPT] with [Alfred]. [Workflows] require the paid _[Powerpack]_ upgrade.

[_Action_ Modifier]s
--------------------
[<kbd>⌘</kbd>]<kbd>⏎</kbd>: Copy to Clipboard.  
<kbd>⌥</kbd><kbd>⏎</kbd>: Open ChatGPT in your default browser.  
<kbd>⌃</kbd><kbd>⏎</kbd>/<kbd>→</kbd>: [Text Actions].

Install
-------
easily with _[Homebrew]_[-alfred]:
~~~ sh
brew tap danielbayley/alfred
brew alfred install chatgpt
# or
brew install --cask alfred-chatgpt
~~~
or with [`brew bundle`] using a _[Brewfile]_:
~~~ rb
# Brewfile
tap "danielbayley/alfred"
cask "alfred-chatgpt"
~~~

Contribute
----------
~~~ sh
git config include.path ../.gitconfig
~~~

License
-------
[MIT] © [Daniel Bayley]

[MIT]:                LICENSE.md
[Daniel Bayley]:      https://github.com/danielbayley

[alfred]:             https://alfredapp.com
[powerpack]:          https://alfredapp.com/powerpack
[workflows]:          https://alfredapp.com/workflows

[_action_ modifier]:  https://alfredapp.com/help/workflows/advanced/alternative-actions
[text actions]:       https://alfredapp.com/help/features/universal-actions#using

[OpenAI]:             https://openai.com
[ChatGPT]:            https://chat.openai.com/chat

[homebrew]:           https://brew.sh
[-alfred]:            https://github.com/danielbayley/homebrew-alfred#readme
[`brew bundle`]:      https://docs.brew.sh/Manpage#bundle-subcommand
[brewfile]:           https://github.com/Homebrew/homebrew-bundle#usage
