# Emojifind

### Install

    git clone https://github.com/siadat/emojifind.git ~/emojifind
    alias emojifind=~/emojifind/emojifind

### Usage

    emojifind [-l] PERL_REGEXP
    emojifind --text=ALIAS...

### Examples

    $ emojifind smile
    😄 😃 😀 😅 😺 😸 😼

    $ emojifind monkey
    🙈 🙉 🙊 🐵 🐒

    $ emojifind birthday
    🎁 🎈 🎂

    $ emojifind 'birth|tada|sparkl|confetti|cake'
    ✨ 💖 🎇 🎁 🎉 🎊 🎈 🍥 🎂 🍰

    $ emojifind chart
    📊 📈 📉 💹

    $ emojifind earth
    🌍 🌎 🌏

    $ emojifind 'bloss|flower'
    💐 🌸 🌷 🌹 🌻 🌼 🎴 💮

    $ emojifind tenderlove
    💛 💙 💜 💚 ❤️ 💗 💓 💘

Convert aliases to emoji

    $ emojifind --text='thumbsup thumbsup thumbsup'
    👍 👍 👍

Use `-l` to see aliases and tags

    $ emojifind -l bell
    🔔  :bell:     #sound,#notification  bell
    🔕  :no_bell:  #volume,#off          bell_with_cancellation
