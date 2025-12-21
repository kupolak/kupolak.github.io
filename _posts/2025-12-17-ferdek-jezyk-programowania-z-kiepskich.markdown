---
layout: post
title:  "Ferdek - An Esoteric Programming Language Inspired by 'The World According to the Kiepskis'"
date:   2025-12-17 20:00:00 +0100
categories: programming fun
---

![Ferdek Kiepski](https://media.tenor.com/8Vh7qYE8RskAAAAC/ferdek-kiepski-swiat-wedlug-kiepskich.gif)

## What is Ferdek?

**Ferdek** is a humorous, esoteric programming language based on the cult Polish TV series "The World According to the Kiepskis" (Świat według Kiepskich). Similar to how [ArnoldC][arnoldc-url] uses quotes from Arnold Schwarzenegger movies, Ferdek uses colorful Polish expressions from the show as programming language keywords.

This is obviously **a joke and programming experiment** - but it actually works! The language was implemented in OCaml and has both an interpreter and a compiler to C.

## Project Philosophy

![Kiepscy rodzina](https://media.tenor.com/YqHfZ5nAr1MAAAAC/swiat-wedlug-kiepskich-arnold.gif)

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

![Ferdek mówi](https://media.tenor.com/M8ZqYPqXCd0AAAAC/swiat-wedlug-kiepskich-ferdynand-kiepski.gif)

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

![Kiepski confused](https://media.tenor.com/7hBJR8gk42YAAAAC/swiat-wedlug-kiepskich-ferdynand-kiepski.gif)

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

![Kiepski thinking](https://media.tenor.com/XUTwbvhxmTEAAAAC/swiat-wedlug-kiepskich-mysli.gif)

## Development Tools

### VS Code Extension

Ferdek has full support in Visual Studio Code! [Ferdek Language Support][vscode-ext] offers:

- Syntax highlighting
- Auto-completion
- Code snippets
- IntelliSense

You can install it directly from the [VS Code Marketplace][vscode-ext].

### Package Manager - Boczek

The project also includes **Boczek** - a package manager for Ferdek that allows you to create and manage libraries in this language.

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

## Summary

![Kiepski dance](https://media.tenor.com/5SYJ8h8uJqsAAAAC/swiat-wedlug-kiepskich-taniec.gif)

Ferdek is proof that programming can be fun! It's a tribute to the cult Polish TV series and an experiment showing that a programming language can be built on any set of keywords - even quotes from Ferdek Kiepski.

Is it practical? No. Is it funny? Absolutely! Does it work? Yes!

The project is open source and available on [GitHub][github-url]. If you have ideas for new features or just want to experiment with your own esoteric language, contributions are welcome!

**MOJA NOGA JUŻ TUTAJ NIE POSTANIE** 🎉

---

*P.S. All rights to the characters and quotes from "The World According to the Kiepskis" series belong to their rightful owners. This project was created solely for educational and entertainment purposes.*

[arnoldc-url]: https://github.com/lhartikk/ArnoldC
[github-url]: https://github.com/kupolak/ferdek
[vscode-ext]: https://marketplace.visualstudio.com/items?itemName=JakubPolak.vscode-ferdek
