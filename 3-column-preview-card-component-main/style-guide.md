# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Bright orange: hsl(31, 77%, 52%)
Dark cyan: hsl(184, 100%, 22%)
Very dark cyan: hsl(179, 100%, 13%)

### Neutral

Transparent white (paragraphs): hsla(0, 0%, 100%, 0.75)
Very light gray (background, headings, buttons): hsl(0, 0%, 95%)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400

- Family: [Big Shoulders Display](https://fonts.google.com/specimen/Big+Shoulders+Display)
- Weights: 700



 body {
        background: linear-gradient(hsl(0, 0%, 95%), hsl(0, 0%, 95%));
    }

    main {
        margin-top: 2em;
        line-height: 1em;
        font-size: 15px;
        flex-direction: column;
        flex-wrap: nowrap;

    }

    section {
        box-sizing: border-box;
        width: 300px;
        overflow: hidden;
    }

    section h1 {
        color: hsl(0, 0%, 95%);
        margin: .5em 0 .5em 0;
        text-transform: uppercase;
        font-size: 1.5rem;
        font-family: 'Big Shoulders Display',
            cursive;
        font-weight: 700;
    }

    section p {
        color: hsla(0, 0%, 100%, 0.75);
        padding: 1.5em 1em 1.5em 0;
        font-family: 'Lexend Deca',
            sans-serif;
        font-weight: 400;
    }

    .sedans {
        padding-left: 2em;
        padding-right: 1.5em;
        border-top-left-radius: 0;
        border-bottom-left-radius: 0;
    }

    .suvs {
        padding-left: 2em;
        padding-right: 1.5em;
        border: 1px solid hsl(184, 100%, 22%);
        background-color: hsl(184, 100%, 22%);
    }

    .luxury {
        padding-left: 2em;
        padding-right: 1.5em;
        border-top-right-radius: 0;
        border-bottom-right-radius: 0;
        border: 1px solid hsl(179, 100%, 13%);
        background-color: hsl(179, 100%, 13%);
    }

    div {
        margin: 1.5em 0;
    }

    input {
        padding: .5em 1.5em;
        border-radius: 25px;
        margin: .5em 0 1em 0;
        background-color: hsl(0, 0%, 95%);
    }