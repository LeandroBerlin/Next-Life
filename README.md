
# Conway's Game of Life in NextJS

The Game of Life, also known simply as Life, is a [cellular automation](https://en.wikipedia.org/wiki/Cellular_automaton)   devised by the British mathematician [John Horton Conway](https://en.wikipedia.org/wiki/John_Horton_Conway) in 1970.

 It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Game of Life by creating an initial configuration and observing how it evolves. It is Turing complete and can simulate a universal constructor or any other Turing machine.

## How does it work

Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent.

## Rules that govern the game

Any live cell with fewer than two live neighbours dies, as if by underpopulation.
Any live cell with two or three live neighbours lives on to the next generation.
Any live cell with more than three live neighbours dies, as if by overpopulation.
Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.



### References
[Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)  
[John Horton Conway](https://en.wikipedia.org/wiki/John_Horton_Conway)  
[Cellular Automation](https://en.wikipedia.org/wiki/Cellular_automaton)  
[Tutorial Game of Life with React and TypeScript ](https://dev.to/toluagboola/build-the-game-of-life-with-react-and-typescript-5e0d) - Toluwanimi Isaiah

<br><br>





# Development

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) and TailwindCSS

## Getting Started

First, clone this repo and install deps. 

```bash
npm install
# or
yarn
# or
pnpm install
```

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
