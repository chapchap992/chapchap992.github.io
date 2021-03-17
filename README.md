# My Project Storage

**장완선의 프로젝트 블로그** 말 그대로 프로젝트를 정리해둔 블로그입니다. 정말 정리를 위해서 사용했기 때문에, 댓글 기능부터 조회수 이런건 다 빼고 심플하게 제작되었습니다.

> 여기는 [웹사이트 바로가기](https://chapchap992.github.io/website/).

**My project Storage** 제 프로젝트 저장소는 이렇게 생겼습니다.


**위에 펭귄프로필의 출저는 https://amatesura.tumblr.com/post/168189054921 입니다. 이미지는 제가...gif를 따로 만들게 되면 바꿀예정입니다.**
## Demo
It's best to just [see it in action](https://qwtel.com/hydejack/).

## Features
Both versions include these features:

* Full in-app page loading, powered by [hy-push-state]
* A customizable sidebar that turns into a drawer menu on mobile, powered by [hy-drawer]
* Advanced FLIP animations, inspired by Material Design
* Good [Google PageSpeed Score][gpss][^3]
* Higher *perceived speed* thanks to content pre-fetching
* [Syntax highlighting][syntax], powered by [Rouge]
* [LaTeX math blocks][latex], powered by [KaTeX]
* Change the wording of built-in strings and possibly translate in other languages
* Support for categories and tags
* Built-in icons for many social networks
* Simple and semantic HTML — can be viewed even with text-based browsers
* Author section below each article and support for multiple authors
* Progressive enhancement — sacrifice features, not content
* Google Analytics and Google Fonts support
* Disqus comments
* Print layout — Used to render Hydejack's [PDF documentation][pdf]
* Blog layout via `jekyll-paginate` (optional)
* SEO meta tags via `jekyll-seo-tag` (optional)
* Github avatars via `jekyll-avatar` (optional)
* Gist support via `jekyll-gist` (optional)

## Documentation
Hydejack is well documented. You can read the docs [on the Jekyll site][docs], or [on GitHub][wiki], or [download the PDF][pdf].

## Download
There are two versions of **Hydejack**: The *free version* includes basic blogging functionality,
as did previous versions of the theme.
The *PRO version* includes additional features for professionals:
A [portfolio], a [resume] layout and a [welcome] page to feature your favorite projects and posts.

This table details what is and isn't included in each respective version.

|                                     | Free                                   | PRO                                          |
|:------------------------------------|:--------------------------------------:|:--------------------------------------------:|
| Blog                                | &#x2714;                               | &#x2714;                                     |
| [Features][feat]                    | &#x2714;                               | &#x2714;                                     |
| [Portfolio] Layout                  |                                        | &#x2714;                                     |
| [Resume] Layout                     |                                        | &#x2714;                                     |
| [Welcome] Layout                    |                                        | &#x2714;                                     |
| [Newsletter Box][news]              |                                        | &#x2714;                                     |
| [Custom Forms][forms]               |                                        | &#x2714;                                     |
| No Hydejack Branding                |                                        | &#x2714;                                     |
| License                             | [GPL-3.0][license]                     | [PRO]                                        |
| Source                              | [GitHub][src]                          | Included                                     |
| Support[^1]                         | No                                     | No                                           |
| Price                               | Free                                   | $29                                          |
|                                     | [**Download**][kit]                    | [**Buy Now - $29**][buy] [^2]                |
{:.stretch-table}

[^1]: You MAY open an issue on GitHub, but no response and/or fix is guaranteed.
      You understand that using Jekyll requires technical know-how, and is NOT comparable to Wordpress in terms of usability.
      Please use the free version to confirm that Hydejack works for you.
      For more, see the [PRO] license.

[^2]: Transactions secured by [Stripe](https://stripe.com). Downloads handled by [Simple Goods](https://simplegoods.co/).  

[^3]: Actual page load speed depends on your hosting provider, resolution of embedded images and usage of 3rd party plugins.  

~~~
 __  __                __                                     __
/\ \/\ \              /\ \             __                    /\ \
\ \ \_\ \   __  __    \_\ \      __   /\_\      __       ___ \ \ \/'\
 \ \  _  \ /\ \/\ \   /'_` \   /'__`\ \/\ \   /'__`\    /'___\\ \ , <
  \ \ \ \ \\ \ \_\ \ /\ \L\ \ /\  __/  \ \ \ /\ \L\.\_ /\ \__/ \ \ \\`\
   \ \_\ \_\\/`____ \\ \___,_\\ \____\ _\ \ \\ \__/.\_\\ \____\ \ \_\ \_\
    \/_/\/_/ `/___/> \\/__,_ / \/____//\ \_\ \\/__/\/_/ \/____/  \/_/\/_/
                /\___/                \ \____/
                \/__/                  \/___/
~~~

[blog]: https://qwtel.com/hydejack/blog/
[portfolio]: https://qwtel.com/hydejack/variations/
[resume]: https://qwtel.com/hydejack/resume/
[download]: https://qwtel.com/download/
[welcome]: https://qwtel.com/hydejack/
[forms]: https://qwtel.com/hydejack/forms-by-example/

[feat]: https://qwtel.com/hydejack/#features
[news]: https://qwtel.com/hydejack/#newsletter-subscription-box
[syntax]: https://qwtel.com/hydejack/#syntax-highlighting
[latex]: https://qwtel.com/hydejack/#latex-math-blocks

[license]: LICENSE.md
[pro]: licenses/PRO.md
[docs]: docs/7.5.2/index.md

[kit]: https://github.com/qwtel/hydejack-starter-kit/archive/v7.5.2.zip
[src]: https://github.com/qwtel/hydejack
[git]: https://github.com/qwtel/hydejack-starter-kit
[gem]: https://rubygems.org/gems/jekyll-theme-hydejack
[buy]: https://app.simplegoods.co/i/AQTTVBOE

[gpss]: https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fqwtel.com%2Fhydejack%2F
[wiki]: https://github.com/qwtel/hydejack/blob/master/docs/7.5.2/index.md
[pdf]: https://github.com/qwtel/hydejack/releases/download/v7.5.2/Documentation._.Hydejack.pdf
[hy-push-state]: https://qwtel.com/hy-push-state/
[hy-drawer]: https://qwtel.com/hy-drawer/
[rouge]: http://rouge.jneen.net
[katex]: https://khan.github.io/KaTeX/
[tinyletter]: https://tinyletter.com/

*[FLIP]: First-Last-Invert-Play. A coding technique to achieve performant page transition animations.
