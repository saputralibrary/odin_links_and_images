# odin_links_and_images
You may have noticed that we snuck in the rel attribute above. This attribute is used to describe the relation between the current page and the linked document and can take multiple values. The most relevant ones to discuss right now are:

noopener: Prevents the new tab from accessing the original page, which would have opened the possibility of phishing attacks like tabnabbing. Modern browsers all set this automatically for any links that have target="_blank", but you will often still see this manually set for historic browser compatibility.

noreferrer: The same as noopener but also prevents certain details about the original page from being passed to the new page; referrer information is not always desirable to share.

Absolute links
Links to pages on other websites on the internet are called absolute links. A typical absolute link will be made up of the following parts: scheme://domain/path. An absolute link will always contain the scheme and domain of the destination.

We’ve already seen an absolute link in action. The link we created to The Odin Project’s About page earlier was an absolute link as it contains the scheme and domain.

https://www.theodinproject.com/about

Relative links
Links to other pages within our own website are called relative links. Relative links do not include the domain name, since it is another page on the same site, it assumes the domain name will be the same as the page we created the link on.

Relative links only include the file path to the other page, relative to the page you are creating the link on. This is quite abstract, let’s see this in action using an example.

practice image source by charlesdeluvio
https://unsplash.com/photos/Mv9hjnEUHR4/