# Phonefree

**TL;DR:** Phones are bad, here is the alternative.

## Why?

Phones have become dangerous for a number of reasons.

**1. Psychology:** Phones make you sick. Instead of choosing to enter cyberspace consciously you are pulled into it at every moment. On the toilet? Pull out the phone. In the elevator? Pull out the phone. On a date and it buzzes? Pull out the phone. Even the most self-disciplined among us cannot resist the temptation.

Life is all about putting fences around the values you want to protect (Pirkei Avot 1:1). Once you are in a position to transgress, it is already too late. The trick is to stop yourself miles before, by retooling and implementing sane practices.

Your phone as a frictionless gateway to cyberspace removes all fences. It will pull you towards all things counter to your inherently noble soul. Porn, binge watching and distraction are just a click away.

**2. Complexity:** Having a phone drastically increases the complexity of your life. More maintenance work, more expenses, more apps you need to understand. Now all of a sudden you have multiple devices that need to stay in sync. In comes the "cloud" and all associated bloat. I ask you: "All this, for what?"

**3. Security:** A phone's attack surface is drastically larger than that of a properly secured computer.

Baseband modules, microphones, GPS, camera, apps offer a myriad of entry points into your device and subsequently your life.

A corebooted ThinkPad without microphone, camera, GSM or network card, by contrast, offers almost no such entry points. Of course, you may want to find a balance between practically airgapping your computer and a phone, but the point is exactly that laptops _allow_ you to find that balance. With a phone it's just take it or leave it. I recommend you leave it.

**4. Privacy:** Privacy follows from security. Hence, phones cannot be private. Furthermore, they are always on your body, allowing tracking your every move, conversation and private moment.

**5. Compartmentalization:** Any self-respecting privacy software developer has multiple nyms. Laptops, specifically with Qubes, allow you to compartmentalize these identities. Phones, however, suck at this, unless you want to carry around multiple devices and maintain rigid discipline.

## But it's so hard to give up your phone

No. If you're working in the IT field it's quite easy and you'll find that your productivity even increases. No more distractions, declutter your mind.

If you're in a job that requires a phone, I don't know what to tell you. Maybe strive for something better than being a [qualified bell boy](https://www.vice.com/en_au/article/xdvd7w/karl-lagerfeld-369-v17n3).

Anyway, for ease of transitioning to a phonefree life I have included a list of decisions I've made myself. These are fairly extreme, so see them as an example not an instruction.

**Hardware:** Corebooted Thinkpad without microphone, camera or WiFi/GSM card. Sounds extreme but actually very usable. Use Ethernet for internet connectivity and plug in headphones to call. If you need a Camera occasionally, leave it in and tape it over.

**Operating System:** QubesOS 4 with Heads.

**Text-based Communication:** PGP E-mail, IRC+OTR, XMPP+OMEMO, Signal desktop, Threema Web, and if you're getting adventurous WhatsApp web. All in different Qubes.

**AV communication:** [Jitsi](https://meet.fulmo.org/)

**Payments:** nix-bitcoin from ssh terminal, spark wallet, electrum.

**Hardware Security Module:** Yubikey and Trezor.

**Browser:** Firefox in dedicated Qube

**VPN:** [OpenVPN Qube](https://www.qubes-os.org/doc/vpn/) or [Wireguard Qube](https://github.com/tasket/Qubes-vpn-support/wiki/Wireguard-VPN-connections-in-Qubes-OS)

I recommend getting a cheap WiFi hotspot if you need internet connectivity on the go. Use with anonymous SIMs. Discard both SIM and Hotspot regularly.

That's it. It's easier than you think.
