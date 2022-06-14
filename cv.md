# Olha Diakiv


## Contacts
* [GitHub](https://github.com/olyadyakiw)
* [Telegram](https://t.me/olyadyakiw)
* [Linkedin](https://www.linkedin.com/in/olga-diakiv-199899195/)


## About me

 _I have been doing layout for over 2 years. I am attentive to details and know how to work in a team. I love what I do and therefore am always ready to learn something new!_


## My skills:
* HTML5, CSS3, JS (JQuery)
* SASS/SCSS
* Gulp
* BEM
* Adaptability and cross-browser compatibility
* PSD, Figma, Sketch, Zeplin, Adobe XD
* Pixel Perfect
* Compliance with W3C standards.

## Code example:
```
 function initHeaderScroll() {
    let lastScroll = 0;
    const defaultOffset = 200;
    const header = document.querySelector(".page-header");

    const scrollPosition = () => window.pageYOffset || document.documentElement.scrollTop;
    const containHide = () => header.classList.contains("hide");

    window.addEventListener("scroll", () => {
        if (scrollPosition() > lastScroll && !containHide() && scrollPosition() > defaultOffset) {
            //scroll down
            header.classList.add("hide");
        } else if (scrollPosition() < lastScroll && containHide()) {
            //scroll up
            header.classList.remove("hide");
        }

        lastScroll = scrollPosition();
    });
}
```


## Experience

* Frontend Developer - **Reliable, USA** - March 2022 - now
* Frontend Developer - **Upwork** - March 2021 - March 2022
* HTML Developer - **Studio 1, Latvia** - December 2020 - March 2021 


## Education

* cource **[From 0 to 1](http://from0to1.com.ua/)** by _Vadym Prokopchuk_

## Languages:
* **English** - Conversational (A2)
* Ukranian - Native
* Polish - Basic (A1)
