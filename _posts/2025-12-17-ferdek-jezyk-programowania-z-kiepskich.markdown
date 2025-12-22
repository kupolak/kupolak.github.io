---
layout: post
title:  "Ferdek - An Esoteric Programming Language Inspired by 'The Lousy World' TV Series"
date:   2025-12-17 20:00:00 +0100
categories: programming fun
---

<div style="text-align: center;">
<div class="tenor-gif-embed" data-postid="7517382" data-share-method="host" data-aspect-ratio="1" data-width="400px"><a href="https://tenor.com/view/happy-dancing-happy-dance-gif-7517382">Happy Dancing GIF</a>from <a href="https://tenor.com/search/happy-gifs">Happy GIFs</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
</div>

## What is Ferdek?

**Ferdek** is a humorous, esoteric programming language based on the cult Polish TV series "[The Lousy World](https://en.wikipedia.org/wiki/The_Lousy_World)" ([Świat według Kiepskich](https://pl.wikipedia.org/wiki/%C5%9Awiat_wed%C5%82ug_Kiepskich)). Similar to how [ArnoldC](https://github.com/lhartikk/ArnoldC) uses quotes from Arnold Schwarzenegger movies, Ferdek uses colorful Polish expressions from the show as programming language keywords.

This is obviously **a joke and programming experiment** - but it actually works! The language was implemented in OCaml and has both an interpreter and a compiler to C.

## Project Philosophy

<div style="text-align: center;">
<div class="tenor-gif-embed" data-postid="3368927164324148871" data-share-method="host" data-aspect-ratio="1.14943" data-width="400px"><a href="https://tenor.com/view/kiepscy-ferdek-halina-lampa-kiepski-gif-3368927164324148871">Kiepscy Ferdek GIF</a>from <a href="https://tenor.com/search/kiepscy-gifs">Kiepscy GIFs</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
</div>

The inspiration for Ferdek was [ArnoldC][arnoldc-url] - a programming language that replaces standard keywords with quotes from Arnie's movies. I thought to myself: "Why not create something similar in Polish?" And so Ferdek was born - a language where instead of boring `while` we write `CHLUŚNIEM BO UŚNIEM` (roughly: "I splashed because I fell asleep"), and instead of `print` we use `PANIE SENSACJA REWELACJA` ("Sir, what a sensation, what a revelation").

## Syntax Examples

### Hello World

The simplest program in Ferdek looks like this:

{% highlight shell %}
CO JEST KURDE

RYM CYM CYM Hello World program in Ferdek language

PANIE SENSACJA REWELACJA "Cześć, tu Ferdek!"

MOJA NOGA JUŻ TUTAJ NIE POSTANIE
{% endhighlight %}

<div style="text-align: center;">
<div class="tenor-gif-embed" data-postid="2268914002221963711" data-share-method="host" data-aspect-ratio="1.14286" data-width="400px"><a href="https://tenor.com/view/waldek-ferdek-kiepski-kiepscy-taniec-gif-2268914002221963711">Waldek Ferdek GIF</a>from <a href="https://tenor.com/search/waldek-gifs">Waldek GIFs</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
</div>

### Basic Constructs

Here are some examples of Ferdek syntax:

- **`CO JEST KURDE`** - program start
- **`PANIE SENSACJA REWELACJA`** - print to screen
- **`CYCU PRZYNIEŚ NO`** - variable declaration
- **`CHLUŚNIEM BO UŚNIEM`** - while loop
- **`NO JAK NIE JAK TAK`** - if statement
- **`A DUPA TAM`** - else
- **`PASZOŁ WON`** - subtraction operator
- **`BABKA DAWAJ RENTĘ`** - addition operator
- **`MOJA NOGA JUŻ TUTAJ NIE POSTANIE`** - program end

### FizzBuzz the Kiepski Way

The classic FizzBuzz in Ferdek looks like this:

{% highlight shell %}
CO JEST KURDE

PANIE SENSACJA REWELACJA "=== FizzBuzz ==="

CYCU PRZYNIEŚ NO i
TO NIE SĄ TANIE RZECZY 1

CHLUŚNIEM BO UŚNIEM i ŁYSA PAŁA 16
    CYCU PRZYNIEŚ NO mod15
    O KURDE MAM POMYSŁA mod15
    A PROSZĘ BARDZO i
    PROSZĘ MNIE NATYCHMIAST OPUŚCIĆ 15
    NO I GITARA

    NO JAK NIE JAK TAK mod15 TO PANU SIĘ CHCE WTEDY KIEDY MNIE 0
        PANIE SENSACJA REWELACJA "FizzBuzz"
    A DUPA TAM
        NO JAK NIE JAK TAK mod3 TO PANU SIĘ CHCE WTEDY KIEDY MNIE 0
            PANIE SENSACJA REWELACJA "Fizz"
        A DUPA TAM
            NO JAK NIE JAK TAK mod5 TO PANU SIĘ CHCE WTEDY KIEDY MNIE 0
                PANIE SENSACJA REWELACJA "Buzz"
            A DUPA TAM
                PANIE SENSACJA REWELACJA i
            DO CHAŁUPY ALE JUŻ
        DO CHAŁUPY ALE JUŻ
    DO CHAŁUPY ALE JUŻ

    O KURDE MAM POMYSŁA i
    A PROSZĘ BARDZO i
    BABKA DAWAJ RENTĘ 1
    NO I GITARA

A ROBIĆ NI MA KOMU

MOJA NOGA JUŻ TUTAJ NIE POSTANIE
{% endhighlight %}

<div style="text-align: center;">
<div class="tenor-gif-embed" data-postid="9778260284991345088" data-share-method="host" data-aspect-ratio="1.03093" data-width="400px"><a href="https://tenor.com/view/kiepscy-ferdynand-ferdek-%C5%9Bwiat-wed%C5%82ug-kiepskich-kac-gif-9778260284991345088">Kiepscy Ferdynand GIF</a>from <a href="https://tenor.com/search/kiepscy-gifs">Kiepscy GIFs</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
</div>

## Advanced Features

Ferdek is not just fun - the language has genuinely advanced features:

### Exception Handling

{% highlight shell %}
HELENA MUSZĘ CI COŚ POWIEDZIEĆ
    PANIE SENSACJA REWELACJA "Trying to do something..."
    O KARWASZ TWARZ "Something went wrong!"
HELENA MAM ZAWAŁ blad
    PANIE SENSACJA REWELACJA "I caught an error!"
{% endhighlight %}

### Classes and Objects

{% highlight shell %}
ALE JAJA Osoba
    CYCU PRZYNIEŚ NO imie
    TO NIE SĄ TANIE RZECZY "None"

    ALE WIE PAN JA ZASADNICZO przedstawSie
        PANIE SENSACJA REWELACJA "Hello, I'm "
        PANIE SENSACJA REWELACJA imie
    DO WIDZENIA PANU
DO WIDZENIA PANU

CYCU PRZYNIEŚ NO osoba
TO NIE SĄ TANIE RZECZY DZIAD ZDZIADZIAŁY JEDEN Osoba
{% endhighlight %}

### Arrays

{% highlight shell %}
PANIE TO JEST PRYWATNA PUBLICZNA TABLICA liczby
TO NIE SĄ TANIE RZECZY [1, 2, 3, 4, 5]
{% endhighlight %}

### Importing Modules

{% highlight shell %}
O KOGO MOJE PIĘKNE OCZY WIDZĄ MojModul
{% endhighlight %}

### Break and Continue

{% highlight shell %}
A POCAŁUJCIE MNIE WSZYSCY W DUPĘ   RYM CYM CYM break
AKUKARACZA                          RYM CYM CYM continue
{% endhighlight %}

### Null Value

{% highlight shell %}
W TYM KRAJU NIE MA PRACY DLA LUDZI Z MOIM WYKSZTAŁCENIEM
{% endhighlight %}

<div style="text-align: center;">
<div class="tenor-gif-embed" data-postid="7699448" data-share-method="host" data-aspect-ratio="1.30081" data-width="400px"><a href="https://tenor.com/view/funny-smile-crazy-waldus-kiepski-gif-7699448">Funny Smile GIF</a>from <a href="https://tenor.com/search/funny-gifs">Funny GIFs</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
</div>

## Development Tools

### VS Code Extension

Ferdek has full support in Visual Studio Code! [Ferdek Language Support](https://github.com/kupolak/ferdek-vscode) offers:

- Syntax highlighting
- Auto-completion
- Code snippets
- IntelliSense

You can install it directly from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=JakubPolak.vscode-ferdek).

## Installation and Usage

### Quick Installation

{% highlight bash %}
curl -fsSL https://raw.githubusercontent.com/kupolak/ferdek/main/scripts/install-remote.sh | bash
{% endhighlight %}

### Running Programs

{% highlight bash %}
# Interpreter
ferdek hello.ferdek

# REPL (interactive mode)
ferdek --repl

# Compile to executable
ferdek -c hello.ferdek -o hello
./hello
{% endhighlight %}

More examples can be found in the [examples directory](https://github.com/kupolak/ferdek/tree/main/examples) on GitHub.

## Summary

<div style="text-align: center;">
<div class="tenor-gif-embed" data-postid="12396302701009616732" data-share-method="host" data-aspect-ratio="1.33155" data-width="400px"><a href="https://tenor.com/view/u%C5%9Bmiech-losu-ferdek-waldek-kiepscy-dolar-gif-12396302701009616732">Uśmiech Losu Ferdek GIF</a>from <a href="https://tenor.com/search/u%C5%9Bmiech+losu-gifs">Uśmiech Losu GIFs</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
</div>

Ferdek is proof that programming can be fun! It's a tribute to the cult Polish TV series and an experiment showing that a programming language can be built on any set of keywords - even quotes from Ferdek Kiepski.

Is it practical? No. Is it funny? Absolutely! Does it work? Yes!

The project is open source and available on [GitHub](https://github.com/kupolak/ferdek). If you have ideas for new features or just want to experiment with your own esoteric language, contributions are welcome!

**MOJA NOGA JUŻ TUTAJ NIE POSTANIE** 🎉

---

*P.S. All rights to the characters and quotes from "The Lousy World" series belong to their rightful owners. This project was created solely for educational and entertainment purposes.*

[arnoldc-url]: https://github.com/lhartikk/ArnoldC
[github-url]: https://github.com/kupolak/ferdek
[vscode-ext]: https://marketplace.visualstudio.com/items?itemName=JakubPolak.vscode-ferdek
