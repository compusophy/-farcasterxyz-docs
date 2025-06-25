# Mini Apps

A mini app lets you turn any cast into an interactive app.

It’s a standard for creating interactive and authenticated experiences on Farcaster. Create polls, live feeds or interactive galleries inside Warpcast or any other FC client.

Mini apps extend the OpenGraph standard and turn static embeds into interactive experiences. The diagram below shows the difference between a standard OG and a Frame OG inside Warpcast.

![Frames vs OG](/assets/frame_og.png)

Creating a mini app is simple — choose an image to show and add buttons the user can click on. If a button is clicked, you get a callback and can send another image with more buttons.

## Resources

A collection of the most popular utilities for creating and managing mini apps.

### Learning

- [Specification](../../reference/frames/spec.md) - A formal specification for the Frame standard.
- [Video: Mini Apps 101](https://youtu.be/rp9X8rAPzPM?si=PWm3vBFCTtaoE_Ua) - A beginner's guide to mini apps.
- [Tutorial: Polls](../../developers/guides/frames/poll.md) - Create a simple poll with mini apps.

### Tools

- [Vercel OG](https://vercel.com/docs/functions/og-image-generation) - Use satori and resvg-js to generate PNG images from HTML and CSS.
- [Warpcast Frame Validator](https://warpcast.com/~/developers/frames) - A debugger for testing mini apps in Warpcast UI.
- [Neynar](https://docs.neynar.com/docs/how-to-build-farcaster-frames-with-neynar) - Infrastructure and tools for mini app servers.

### Frameworks

- [onchainkit](https://github.com/coinbase/onchainkit) - A React toolkit to create mini apps.
- [frames.js](https://framesjs.org/) - A Next.js template for building and debugging mini apps.
- [Simplest Frame](https://github.com/depatchedmode/simplest-frame) - A zero-framework mini app template.
- [frog](https://frog.fm) - framework for mini apps.

### Examples

- [Linktree](https://replit.com/@soren/Linktree-Frame?v=1) - A simple mini app that links to four other pages.
- [Onchain Cow](https://github.com/WillPapper/On-Chain-Cow-Farcaster-Frame) - A cow clicker-like game.
- [FC Polls](https://github.com/farcasterxyz/fc-polls) - Create and run polls within mini apps.
- [Claim or Mint](https://github.com/horsefacts/base-mint-with-warps) - Lets users claim an NFT if they meet certain criteria.

<br/>

A more detailed list of resources can be found at [awesome-frames](https://github.com/davidfurlong/awesome-frames).
