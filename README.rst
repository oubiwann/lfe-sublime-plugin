##################################################
Sublime Text Plugin for LFE (Lisp Flavored Erlang)
##################################################

This `Sublime Text`_ package provides support for syntax highlighting of
`LFE`_ and is intended to be installed via `Package Control`_.

If you would like to use the stand-alone package and install it manually, visit
the `other project home`_.


Installation
============

#. Be sure to have `Package Control`_ installed.

#. Go to Sublime Text -> Preferences -> Package Control -> install package

#. Type "LFE"

#. Select it and restart Sublime after it has installed


Configuration
=============

If you would like to dim the parenthesis down visually, you can use the
`VimBlackboard`_ Sublime Text package. This will give you a look such as this:

.. image:: https://raw.github.com/wiki/oubiwann/lfe-sublime-plugin/images/SublimeText2-LFE-Screenshot-small.png
   :target: https://raw.github.com/wiki/oubiwann/lfe-sublime-plugin/images/SublimeText2-LFE-Screenshot.png

If you'd just like to continue using your own theme, you can update it to use
dimmed parens with the following snippet:

.. code:: xml

    <dict>
        <key>name</key>
        <string>Lisp Parens</string>
        <key>scope</key>
        <string>source.parens.lfe</string>
        <key>settings</key>
        <dict>
            <key>foreground</key>
            <string>#666666</string>
        </dict>
    </dict>


.. Links
.. =====
.. _Sublime Text: http://www.sublimetext.com/2
.. _LFE: http://lfe.io/
.. _Package Control: https://sublime.wbond.net/
.. _other project home: https://github.com/lfe/sublime-lfe
.. _VimBlackboard: https://github.com/oubiwann/Theme-VimBlackboard
