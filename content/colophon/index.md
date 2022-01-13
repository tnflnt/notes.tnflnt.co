---
title: "Colophon"
date: 2021-01-01T00:00:00+06:00
description: ""
tags: []
draft: false
---

[tnflnt.co](/) is built with Hugo and hosted on Netlify. It’s a work-in-progress. 😅 

**To Do:**

- ~~Responsive images~~ [*Done!*](http://localhost:1313/posts/2021/04/responsive-images-in-hugo/)
- ~~Auto dark mode~~ *Done!* Next: user-controlled dark mode
- Better image layouts: wide images, side-by-side images, etc.
- Better code blocks
- Full-text RSS feed
- Finish importing my portfolio of work
- SVG icons
- Better button styling
- Properly learn [go templating](https://gohugo.io/templates/introduction/)
- More writing

If you’d like to see samples of my work, or just want to chat, [say hi](mailto:hi@tnflnt.co). 

---

##### Typography

[tnflnt.co](/) uses two type families: body text and primary headings are set in Matthew Butterick's [Concourse](https://mbtype.com/fonts/concourse/), and small headings, meta text, and code are set in [VCTR Mono](https://www.vectrotype.com/vctr-mono) from Vectro Type.

# Heading 1

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Tortor aliquam nulla facilisi cras fermentum odio. Nunc pulvinar sapien et ligula ullamcorper malesuada. Lobortis mattis aliquam faucibus purus in massa tempor. Enim neque volutpat ac tincidunt vitae semper quis lectus nulla. Non arcu risus quis varius quam quisque. Tincidunt ornare massa eget egestas purus viverra accumsan in nisl. 

## Heading 2

Non curabitur gravida arcu ac tortor dignissim. Donec massa sapien faucibus et. Ac auctor augue mauris augue neque gravida. Donec pretium vulputate sapien nec sagittis aliquam malesuada bibendum. Massa eget egestas purus viverra accumsan in nisl nisi scelerisque. Eu consequat ac felis donec et odio. Feugiat scelerisque varius morbi enim nunc faucibus a pellentesque sit.

### Heading 3

Sed egestas egestas fringilla phasellus faucibus scelerisque eleifend donec pretium. Iaculis urna id volutpat lacus. Mattis aliquam faucibus purus in massa. Accumsan sit amet nulla facilisi morbi tempus. Eget est lorem ipsum dolor sit amet consectetur adipiscing. Iaculis nunc sed augue lacus viverra vitae congue. Interdum posuere lorem ipsum dolor. Viverra accumsan in nisl nisi scelerisque eu ultrices. In mollis nunc sed id semper risus in hendrerit. Lacus viverra vitae congue eu consequat ac felis. Ut lectus arcu bibendum at varius vel.


#### Heading 4

A erat nam at lectus urna duis convallis convallis. Tellus pellentesque eu tincidunt tortor aliquam nulla facilisi cras fermentum. At tellus at urna condimentum mattis pellentesque id nibh. Hendrerit gravida rutrum quisque non. Quam pellentesque nec nam aliquam sem. Id cursus metus aliquam eleifend mi. Accumsan lacus vel facilisis volutpat est velit egestas. Egestas maecenas pharetra convallis posuere morbi leo urna. 

##### Heading 5

Tortor id aliquet lectus proin nibh nisl condimentum id. Sem nulla pharetra diam sit amet nisl suscipit adipiscing. Porttitor leo a diam sollicitudin tempor id eu. Turpis in eu mi bibendum neque egestas. Amet venenatis urna cursus eget. Adipiscing tristique risus nec feugiat in fermentum posuere urna nec. Purus viverra accumsan in nisl nisi scelerisque eu ultrices vitae. Dignissim suspendisse in est ante in nibh. Lobortis mattis aliquam faucibus purus in. 

###### Heading 6

Phasellus faucibus scelerisque eleifend donec pretium vulputate sapien nec. Enim facilisis gravida neque convallis a cras semper auctor neque. Quam vulputate dignissim suspendisse in. Eu facilisis sed odio morbi quis commodo odio aenean sed. Montes nascetur ridiculus mus mauris vitae ultricies leo integer malesuada. Libero volutpat sed cras ornare arcu dui. Fermentum et sollicitudin ac orci phasellus. Tellus in hac habitasse platea dictumst vestibulum rhoncus est pellentesque. 

Lid est laborum et dolorum fuga, This is [an example](http://example.com/ "Title") inline link. Et harum quidem rerum facilis, **This is bold** and *emphasis* cumque nihilse impedit quo minus id quod amets untra dolor amet sad. While this is `code block()` and following is a `pre` tag

	print 'this is pre tag'

Following is the syntax highlighted code block

```go
func getCookie(name string, r interface{}) (*http.Cookie, error) {
	rd := r.(*http.Request)
	cookie, err := rd.Cookie(name)
	if err != nil {
		return nil, err
	}
	return cookie, nil
}

func setCookie(cookie *http.Cookie, w interface{}) error {
	// Get write interface registered using `Acquire` method in handlers.
	wr := w.(http.ResponseWriter)
	http.SetCookie(wr, cookie)
	return nil
}
```

This is blockquote, Will make it *better now*

> 'I want to do with you what spring does with the cherry trees.' <cite>cited ~Pablo Neruda</cite>*

> Et harum quidem *rerum facilis* est et expeditasi distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihilse impedit

Unordered list

*   Red
*   Green
*   Blue

Ordered list

1.	Red
2.  Green
3.  Blue

## Images

{{< figure class="" figcaption="This is fine." >}}
{{< imglink href="this-is-fine.jpg" >}}
{{< img src="this-is-fine.jpg" alt="A dog, surrounded by plants, saying 'this is fine'." >}}
{{< /imglink >}}
{{< /figure >}}