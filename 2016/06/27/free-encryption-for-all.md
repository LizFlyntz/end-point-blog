---
title: 
 - "Free Encryption for All, In Our Time"
date: 2016-06-27 20:56:37 UTC
tags:
- Encryption
- Development
author: Lee Azzarello
image: 
- '/images/blog-images/LAblog.png'
published: true
description:
- "In which Lee Azzarello tells us how security can indeed be free."
keywords:
- "encryption, security, lee azzarello, development" 
---
The <a href="https://en.wikipedia.org/wiki/Cryptography#Export_controls" target="_blank">commodification of encryption algorithms</a> happened in the 1990s. The conversation prior to this event was rife with controversy. Here are some paraphrased FAQs from the era:

"If encryption is free how will national security continue to be assured?"
"If these ideas become a commodity, bad people will use them to become worse!"
or one of my favorites, "These ideas are dangerous because I do not understand them."

Fortunately, history was on the side of the algorithm authors and now we have commodified encryption and can securely buy stuff from amazon.com. Mission accomplished. <em>pats own back.</em>

Unfortunately, everything didn't go as planned. SSL certificate vendors built small empires on asymmetric knowledge about a complicated process. In the USA, the National Security Agency built a business to influence vendors to inject secret backdoors into their security products. Web browsers were installed with poorly implemented SSL certificate management. Academics wrote papers about experiments to break various kinds of security, then published them.

So where does the casual web developer stand in this world? There's too much chaos for any rational thought -- besides, <em>all I want is a secure webpage that just works!</em>
This story typically ends with the casual web developer paying some US dollars (usually around $30 to $80) to a company to sell them a single SSL certificate which is only good for a couple of years and only works for a single URL. The process to perform this transaction is esoteric, confusing and requires a pretty decent understanding of the underlying infrastructure to comprehend, let alone transact.

This created a business culture of "SSL experts," to which the author belongs. These are usually people who know enough about encryption to bring existing applied cryptography to any software application. These people understood that their title was an illusion and the only reason they are considered expert is because OpenSSL was authored as a monolithic Swiss Army chainsaw and they took the time to read the operations manual in order to use it without killing themselves. We thought: "THERE MUST BE A BETTER WAY!"

<a href="http://www.cacert.org" target="_blank">CAcert</a> was a swing and a miss, in part because their political clout didn't reach deep into the Illuminati of <a href="http://www.cacert.org/index.php?id=3" target="_blank">root level</a> Certificate Authority holders.

So-called "self-signed" certificates are worthless because they carry with them no authenticity. You needn't waste your time using encryption when you don't even know if the encrypted thing originated from the author you so desperately want to protect.
Turns out, in 2016, there is a better way. It's called...

<a href="https://letsencrypt.org" target="_blank"><b>Let's Encrypt!</b></a>  

Through <a href="https://letsencrypt.org/isrg/ " target="_blank">good partners</a>, the <a href="https://www.eff.org" target="_blank">Electronic Frontier Foundation</a> managed a project to build a software pipeline to issue valid, signed SSL certificates in a programatic way for free to anyone in the world.

They've got sick <a href="https://letsencrypt.readthedocs.io/en/latest/" target="_blank">APIs</a>!

This means that casual web developer can now use the same software tools they have for developing websites to give those websites security. For free.

Now, when someone asks me to provide expert services for SSL, I will use Let's Encrypt. I strongly encourage anyone who makes webpages to use Let's Encrypt. You lose nothing and gain assurances of security.

<a href="https://encryptallthethings.net" target="_blank">Encrypt all the things.</a>  Ensure your rights online!
